# UpgradeHub Team Management Portal — v4.0.0 source package

This is a local-development source package for the UpgradeHub internal team portal, branded from the supplied UpgradeHub Team logo (royal blue, black and white). It includes a responsive web UI, Node/Express API, SQLite database, server-side sessions, role-aware records, audit/history/comments, approvals, private attachment storage, in-app notifications, operational reminder jobs, encrypted backup/restore utilities, and a traceable 732-control acceptance checklist.

> **Honest status:** The package has 67 role-filtered module workspaces and 732 acceptance controls across 79 sections. It is not a claim that all 300 production controls are implemented or verified. Some specialist modules use the shared record engine and need their own business rules. Read `docs/IMPLEMENTATION_MATRIX.md` and `docs/RELEASE_READINESS.md` before using it with real data.

## See the UI immediately (no server needed)

Open `preview/UpgradeHub_UI_Preview.html` in a browser to see the dashboard, side navigation, task Kanban, team directory, approvals and operations screens. It contains sample/demo data and lightweight preview interactions only; it does **not** connect to the live database or save changes. PNG screenshots for desktop and mobile are in the same folder.

The actual working portal is the `public/` + `src/` application and needs the Node.js setup below. Opening `public/index.html` directly is not the correct way to run the app because its API and authenticated session come from the server.

## v4.0 branding and tracking upgrade

- Uses the uploaded UpgradeHub Team logo in the sign-in screen, navigation brand mark and favicon assets.
- Royal-blue/black/white theme with responsive navigation and an **Advanced Tracker Hub** for work, project, KPI and security workspaces.
- Expands the module catalogue from 40 to **67** workspaces, with a dedicated field schema for each.
- Adds specialist workspaces for departments, capacity planning, shift coverage, OKRs, surveys, recognition, purchase orders, expenses, budgets, sprint planning, QA, bugs, code reviews, API inventory, secret-rotation metadata, retention, legal holds, reporting rules and digital member IDs.
- Expands the traceable acceptance checklist to **732 controls across 79 sections**. Each row has related modules, suggested owner, acceptance test, source status, validation status and evidence field.

**Important:** the 432 additional controls are expanded requirements, not a claim that all specialist workflows are implemented. Any feature that needs an external provider, malware scanning, MFA, actual QR issuance, scheduled delivery, immutable logs, remote storage or legal review remains a deployment/implementation gate until it is built and tested.

## Main deliverables in this ZIP

- **67 module workspaces** with distinct structured field schemas.
- **7 application roles**: Founder, Super Admin, Admin, HR/Member Admin, Project Lead, Employee and Security Reviewer.
- **732 requirement controls / 79 sections** in both Markdown and CSV, with related modules, suggested owner, acceptance checks, source status, validation status and evidence columns.
- **Member lifecycle baseline**: pending onboarding, authorised activation, role/status protections, suspension/exit without a hard-delete endpoint, directory view, and audit history.
- **Shared record workflow**: create/update/archive-with-reason, due dates, project association, structured fields, change history, comments and acknowledgements.
- **Security baseline**: bcrypt password hashing, server-side session storage, session rotation at login, login rate limiting, secure cookie flags, same-origin mutation checks, Helmet headers, per-role module gates, sensitive-field allowlists for employee submissions, and audit events.
- **Approvals**: self-approval is blocked; selected high-risk requests require two different authorised approvers. Approval does not silently execute the underlying action.
- **Private attachments**: files are stored outside the public web root with access checks, basic file-signature checks, size limits and SHA-256 metadata. Malware scanning is not configured.
- **Operational reminders**: in-app reminders for overdue tasks, near-term renewal dates and stale portal activity; the stale-activity alert requires human review and is not an automatic disciplinary action.
- **Encrypted backup/restore tooling**: database snapshot + private uploads, AES-256-GCM authenticated encryption and database integrity checks. Restore is deliberately an offline/server-operator action.

## Module workspaces

### People and access
`org_directory`, `departments`, `onboarding`, `offboarding`, `permissions_access`, `sessions_devices`, `hr_cases`, `recruitment`, `training`, `capacity_planning`, `shift_planning`, `digital_id_cards`

### Delivery and collaboration
`projects`, `milestones`, `tasks`, `task_submissions`, `employee_status`, `attendance`, `time_tracking`, `sprint_planning`, `qa_test_cases`, `bug_tracker`, `code_reviews`, `release_calendar`, `goals`, `meetings`, `decisions`, `announcements`, `communication_templates`, `knowledge`, `policies`

### Performance and service operations
`kpis`, `okr_cycles`, `performance_reviews`, `surveys`, `recognition`, `helpdesk`, `sla_policies`, `service_catalog`, `grievances`, `assets`, `inventory`, `purchase_orders`, `expense_claims`, `budget_planning`, `finance`, `vendors`, `contracts`, `legal_holds`, `client_accounts`, `customer_feedback`, `document_vault`

### Security, systems and governance
`incidents`, `risks`, `compliance`, `releases`, `integrations`, `api_registry`, `secret_rotation_register`, `continuity`, `backup_jobs`, `data_requests`, `data_retention`, `notification_rules`, `report_schedules`, `event_calendar`

Each role only receives the modules mapped for it by the server. A visible UI control is not the security boundary: API routes enforce the checks again. Project-level access remains scoped to the assignment field and linked record. Review and test the access matrix before real deployment.

## Requirements

- Node.js 20 or newer
- npm 10 or newer
- GNU `tar` for encrypted bundle backup/restore utilities

## Local setup

1. Extract the ZIP to a local development folder and open a terminal there.
2. Copy `.env.example` to `.env`.
3. Generate a random session secret, for example `openssl rand -base64 48`, and paste it into `SESSION_SECRET`. It must be at least 32 characters.
4. Keep `APP_ORIGIN=http://localhost:3000` for local-only use.
5. Install dependencies with `npm install`.
6. Configure `FOUNDER_EMAIL`, `FOUNDER_NAME` and a unique `FOUNDER_PASSWORD` of at least 16 characters in `.env`.
7. Create the initial Founder account with `npm run setup:founder`.
8. Remove `FOUNDER_PASSWORD` from `.env` after successful bootstrap.
9. Start the app with `npm start`, then visit `http://localhost:3000`.
10. Sign in with the initial Founder account. Create a Project record before assigning a Project Lead to a project record ID.

The default app database is `./data/upgradehub.sqlite`; session storage is held separately under `./data`. Set `DATABASE_PATH` and `UPLOAD_DIR` explicitly before deploying. Never commit `.env`, database files, member data, uploads, credentials, OTPs, session secrets, or backups.

## Encrypted backups

The encrypted backup requires a separate 32-byte key encoded as Base64:

```bash
openssl rand -base64 32
```

Place the generated value in `BACKUP_ENCRYPTION_KEY` in `.env`. Set `BACKUP_DIR` to a protected local directory. Never store the key in the backup directory or the same storage location as the only backup copy.

- CLI backup: `npm run backup`
- Founder/Super Admin: use **System operations → Create encrypted backup**. A reason is required and recorded in the audit trail.
- CLI restore: stop the app first, move the current database plus any `-wal` / `-shm` files out of the way, ensure the target database path does not exist, and run `npm run restore -- ./backups/your-backup.uhbak`.
- Restore refuses to overwrite a database or merge into a non-empty upload directory. Test restores in a separate, empty environment before relying on a backup.
- Session state is intentionally excluded from backup; rotate `SESSION_SECRET` and require fresh authentication after recovery.
- Copy backups to an isolated/off-host location separately. The local utility does **not** provide off-site replication, immutable storage or a proven recovery SLA.

## Validation commands

```bash
npm run check
npm test
npm run validate:package
```

The included test suite currently checks the module catalogue, schema coverage, seven role definitions, absence of a member hard-delete API, public/static upload separation, the 732-control checklist count, employee field allowlists, selected high-risk approval guards, and backup role/reason gates.

See `docs/ACCEPTANCE_TEST_REPORT.md` for the checks that passed and the dependency-install/runtime limitation observed while this ZIP was built. The standalone demo UI was rendered and its main preview navigation/search interactions were smoke-tested in Chromium. These source-level/regression checks are **not** authenticated live-app end-to-end, load, penetration, integration, migration or recovery-drill tests. A successful syntax check does not prove runtime readiness. Install dependencies and run the app in a test environment before using it.

## API overview

- `GET /api/health`, `GET /api/config`, `GET /api/modules`
- `POST /api/auth/login`, `POST /api/auth/logout`, `GET /api/auth/me`, `POST /api/auth/change-password`
- `GET /api/dashboard`, `GET /api/records/:module`, `POST /api/records/:module`, `PATCH /api/records/:module/:id`
- `GET /api/records/:module/:id/history`, `GET/POST /api/records/:module/:id/comments`, `POST /api/records/:module/:id/acknowledge`
- `POST /api/records/:module/:id/archive` — soft archive, Founder/Super Admin only, reason required
- `GET/POST /api/members`, `PATCH /api/members/:id`, `POST /api/members/:id/approve`
- `GET/POST /api/approvals`, `POST /api/approvals/:id/decide`
- `POST /api/files/upload`, `GET /api/files`, `GET /api/files/:id/download`
- `GET /api/operations/status`, `POST /api/operations/run-jobs`
- `GET /api/operations/backups`, `POST /api/operations/backups/run`, `GET /api/operations/backups/:filename/download` — Founder/Super Admin only, reason required for creation/download
- `GET /api/audit`, `GET /api/security/events`, `POST /api/security/events/:id/resolve`
- `POST /api/policies/:key/acknowledge`, `GET /api/policies/acknowledgements`
- `GET /api/export/records/:module` — Founder/Super Admin only, audited reason required

The exact route rules are defined in `src/server.js`; do not infer role permissions from this overview alone.

## Member-data protections

- No ordinary hard-delete endpoint exists for member records or member history.
- Suspending or exiting a member changes account status and triggers an access-revocation security event; the history remains.
- Passwords are hashed with bcrypt and password hashes are not returned by member APIs.
- The directory exposes limited work-contact/profile fields; the full member-management list requires an authorised role.
- Record archives are soft archives and require Founder/Super Admin plus a reason.
- Audit rows are append-only through normal app routes, but local SQLite is not tamper-proof against a host/database administrator. Production requires separate infrastructure controls and preferably remote immutable logging.
- “Do not allow unauthorised deletion” is not a policy of retaining personal information forever. Retention, legal hold and legally valid access/correction/deletion requests need an approved policy and applicable-law review.

## Known gaps / production gates

The source includes structures and partial workflows across 67 module workspaces, but these items remain unfinished, externally dependent, or unverified. Do not describe them as fully implemented:

1. **Identity/security:** email verification delivery, enforced MFA, recovery codes, forced password rotation at first sign-in, managed reset and break-glass recovery.
2. **People lifecycle:** digital-ID QR issuance/revocation, member profile-photo workflow, joining/transfer checklist automation and complete exit handover orchestration.
3. **Specialist logic:** custom task dependencies and review SLAs; automatic fair KPI rollups/quality weighting; leave balances and calendar; inventory accounting and reconciliation; robust grievance case assignment/appeal workflow; contract e-signature/legal hold enforcement; training certificates; goal rollups; finance/accounting controls.
4. **Documents:** malware scanning, encrypted-at-rest document storage, expiring signed URLs, object storage, robust version control and legal retention automation. Private uploads in this build are access-checked local files, not a malware-scanned vault.
5. **Integrations and notifications:** real OAuth/provider connectors, credential vault and rotation, external sync, email/push delivery, delivery retry/dead-letter handling and external alert routes.
6. **Resilience:** automated off-host backup replication, immutable backup/audit store, tested RPO/RTO, monitored disk/capacity, production database migration path, HA and rollback automation.
7. **Testing and compliance:** full API/role/IDOR/integration/browser test matrix, dependency and security scans, penetration testing, load tests, incident-response drills, accessibility review and privacy/legal review.
8. **Deployment:** production HTTPS/reverse proxy, secret manager, storage policies, monitoring, alerting, runbooks and operational owners.

See `docs/MASTER_CHECKLIST_732.md` (readable) or `.csv` (filterable) for the exact acceptance controls. All rows currently show **Validation: Not run** by default; change a status only when actual evidence is attached.


## UI/UX update — v4.0.0

The web client now includes a premium responsive SaaS shell with a branded sign-in screen, persistent desktop navigation and mobile horizontal navigation, Founder/team overview, role-filtered module search and category chips, data-driven work-pulse bars, recent-project summaries, due-date task focus, shortcut actions, searchable member directory and status filters, and a four-lane task Kanban view. Existing record, comment, history, private-file, approval, audit and encrypted-backup routes remain connected to the app client. Dashboard numbers and project/task summaries are derived from data returned by the authenticated APIs; no demo business metrics are injected in the production UI.

### UI verification boundary

HTML IDs referenced by the client were cross-checked, JavaScript syntax checks passed, and package validation plus the source-level test suite pass. A full browser screenshot / authenticated end-to-end test was not completed in this environment; live behaviour still requires dependency installation and a locally configured server/database. Review `docs/UI_UX_RELEASE_REPORT_v4.0.md` for controls and known limits.
