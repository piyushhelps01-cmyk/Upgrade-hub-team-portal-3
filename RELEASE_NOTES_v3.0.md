# Release Notes — UpgradeHub Team Management Portal v3.0.0

## Package contents

- A 40-workspace module catalogue with individual field schemas.
- Seven defined roles and server-enforced module/record access checks.
- Member onboarding/approval/status management; member hard-delete is intentionally not exposed.
- Structured records with history, comments, acknowledgements, notifications and soft archive for records.
- Selected high-risk approval requests require a reason, cannot be self-approved, and use two distinct approvers where configured.
- Private local file uploads with file-size/type-signature checks, record-level access checks and download auditing. Malware scanning and encryption-at-rest for these files are not included.
- In-app operational reminders for overdue tasks, renewals and inactivity needing human review.
- AES-256-GCM encrypted backup and offline restore utilities for SQLite + private uploads; a backup key is configured separately.
- A 300-control acceptance checklist across 25 sections, mapped to modules and suggested accountable roles.
- Role matrix, implementation matrix, release gates, setup and acceptance test report.

## Hardening in this build

- Project Leads are scoped to their assigned project for project-scoped records; they cannot create projects themselves.
- Project assignments must resolve to a live project record.
- Employee attendance/time identity is assigned server-side, not trusted from incoming form data.
- Employee helpdesk/grievance forms allow descriptions while the requesting/complainant identity remains server-controlled.
- Task submissions must reference an existing task visible to the requester; linked projects must exist and be consistent.
- Security Reviewer write access is limited to incident, risk and compliance records; approval decision scope is separately enforced.
- Health endpoint performs a database query rather than returning unconditional success.

## Release status

**Development source package — not production-certified.** Syntax checks and source-level regression tests pass. Installing dependencies was blocked by an npm registry DNS/network error in the build environment, so the app was not booted and end-to-end API/browser/security/backup-restore tests were not run here. Unfinished or provider-dependent items are detailed in `IMPLEMENTATION_MATRIX.md`, `RELEASE_READINESS.md` and `MASTER_CHECKLIST_300.csv`.
