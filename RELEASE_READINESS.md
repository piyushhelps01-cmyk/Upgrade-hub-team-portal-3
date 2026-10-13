# Release Readiness and Acceptance Plan

## Current release status

**Development package only. Do not expose it publicly or load real confidential people, legal, finance or security incident data yet.** Syntax/source checks can pass while runtime dependencies, database behaviour, permission boundaries or browser workflows still fail. The current automated suite is a lightweight source-level suite, not a full security certification.

## P0 gates before any real-data pilot

- [ ] Install dependencies on the target Node 20+ environment and record `npm install`, `npm run check` and `npm test` output.
- [ ] Run the app against a disposable test DB and verify first Founder bootstrap, login, logout, password change and session rotation.
- [ ] Build an API authorization matrix for all seven roles and all 67 modules, including guessed record IDs, hidden comments, export, archive, approval decision and private file download.
- [ ] Verify employee cannot edit reviewer decisions, approval fields, other-member IDs or restricted records; verify Project Lead cannot read/write another project by changing a project/record ID.
- [ ] Verify suspended/exited accounts are denied on the very next authenticated request and that existing sessions cease working.
- [ ] Verify Founder/Super Admin account protection, privileged role grant restrictions, approval requester self-approval denial and two-approver separation.
- [ ] Test private uploads for malformed signature, wrong extension, oversize file, forbidden type, cross-user download, assigned HR grievance access and inaccessible confidential files.
- [ ] Add and test malware scanning before using private uploads with real documents; verify upload storage is not served as static content.
- [ ] Verify encrypted backup includes all required files/data, a wrong key fails, modified ciphertext fails, manifest hash mismatch fails, restore is refused when target is non-empty, and a test restore works end-to-end.
- [ ] Copy at least one backup to separate/isolated storage; test restore from that copy. Confirm encryption key recovery is possible without placing it beside the backup.
- [ ] Replace local-only SQLite operations with a deployment-appropriate persistence/backup design if there will be multiple instances or concurrent production use.
- [ ] Configure HTTPS, secure reverse proxy, secret management, monitoring/alerting, filesystem permissions, log redaction and backup retention.
- [ ] Decide the applicable privacy/retention policy; document data subject requests and legal-hold handling, with qualified legal review where needed.

## P1 specialist workflow gates

- [ ] Email verification, managed password reset, enforced MFA, recovery codes and privileged break-glass workflow are implemented and verified.
- [ ] Onboarding / transfer / suspension / exit workflows produce complete, auditable checklist records.
- [ ] Task submission review, ownership transfer, dependencies, deadlines and SLA escalation are verified.
- [ ] Work-status logic uses configurable periods, leave-aware handling, blocker/context and appeal; it never triggers automatic discipline based solely on a score.
- [ ] KPI formulas, quality and deadline weighting, baselines, targets, change reasons, review history and appeals are documented and tested.
- [ ] Leave approval/balance/calendar, attendance/time review and notification routing are tested.
- [ ] Asset issue/return/repair/retire and inventory stock reconciliation preserve a consistent ledger.
- [ ] Knowledge/policy versioning, acknowledgements and review reminders work end-to-end.
- [ ] Grievance triage, conflict checks, confidentiality, case ownership, recusal, appeals and anti-retaliation policy are defined and tested.
- [ ] Contract approval, signature/renewal, legal hold and retention workflows are implemented or integrated with a trusted provider.
- [ ] Real integration connectors use minimal scopes, protected secrets, rotation, retry/dead-letter behaviour and auditable revoke controls.
- [ ] Email/push notifications and delivery failures are observed, retried and escalated.

## P2 operating gates

- [ ] Restore drills prove actual RPO/RTO; logs record dataset, checksum, result, time and owner.
- [ ] Database migrations, staging tests and rollback are repeatable and documented.
- [ ] Dependency scanning, SAST/secret scan, container scan, API fuzzing and penetration tests are complete.
- [ ] Cross-browser, responsive/mobile, accessibility and performance tests are complete.
- [ ] Security incidents have named owner, timeline, containment, root cause, notification decision, corrective actions and post-incident review.
- [ ] Team permission reviews are scheduled, time-bound grants expire, exits transfer project ownership, and old sessions/integrations are revoked.

## Minimum manual test walkthrough

1. Create Founder in an isolated environment; confirm there is no default/shared password.
2. Create an employee and Project Lead. Confirm they cannot sign in while pending. Approve with a reason.
3. Create two projects and assign the Project Lead to only one. Confirm access to the other project is denied by API, not only hidden in the UI.
4. Submit task evidence as employee. Confirm the employee cannot set `decision=accepted`, approve leave, change another person's attendance or set their own reviewer result.
5. Submit a grievance with a test attachment. Confirm only the complainant, permitted case owner, Founder/Super Admin can access according to configured rules; validate download attempts via a second unrelated user.
6. Request a high-risk approval. Confirm the requester cannot approve, the first approver cannot serve as second approver, and approval does not execute any separate action until that workflow has been explicitly linked.
7. Suspend the employee and verify the existing session is refused on the next API call. Confirm audit history remains.
8. Create an encrypted backup with a reason, verify the output file is `.uhbak`, restore into a new empty test location, run the app and reconcile member/record/private-file counts.
9. Attach evidence and a tester/date to the relevant checklist rows. Do not mark items complete based on the UI alone.

## Checklist ownership

For each `UH-001` through `UH-300`, record source status, test result, evidence link, accountable owner, date, reviewer and exception/expiry if any. The source CSV currently marks all validation results `Not run` intentionally.


## v4.0 additions to acceptance

- [ ] Verify the supplied logo renders correctly on sign-in, sidebar brand mark and small-screen viewport without stretching or obscuring navigation.
- [ ] Verify Tracker Hub cards are shown only when the signed-in role can read the corresponding module.
- [ ] Verify the API config returns only the current role's module definitions and field schemas.
- [ ] Verify all 67 modules have distinct keys and structured schemas; confirm unsupported specialist automation is visibly marked as not yet configured.
- [ ] Execute controls `UH-301` through `UH-732` from `MASTER_CHECKLIST_732.csv`; all start as `Not run`.
