# Master Acceptance Checklist — UpgradeHub Team Management Portal v3.0

**Controls:** 300 · **Sections:** 25 · **Module workspaces:** 40

This is a traceable acceptance checklist, not a claim that all 300 controls are already implemented or production-verified. Every row starts at **Not run**. Assign a tester, record dated evidence, and change the status only after the test actually passes. The filterable CSV is the source of truth.

Suggested validation values: `Not run`, `Pass`, `Fail`, `Blocked`, `Not applicable (with approved reason)`. Do not mark a control complete just because a module, button or field exists.

## Identity, onboarding and member lifecycle

**Related modules:** org_directory, onboarding, offboarding, policies, assets

**Suggested owner:** Founder / HR

### UH-001 — Each person has a unique account, stable member ID and unique work email.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Each person has a unique account, stable member ID and unique work email. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-002 — New accounts start as pending and cannot sign in until approved.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: New accounts start as pending and cannot sign in until approved. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-003 — Member profile stores name, designation, department and work contact.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Member profile stores name, designation, department and work contact. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-004 — Joining date, reporting manager and project assignment can be recorded.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Joining date, reporting manager and project assignment can be recorded. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-005 — Onboarding checklist covers identity verification, policy reading and equipment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Onboarding checklist covers identity verification, policy reading and equipment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-006 — Policy acknowledgements capture member, policy version and timestamp.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy acknowledgements capture member, policy version and timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-007 — Email verification token is generated and delivered before activation.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Email verification token is generated and delivered before activation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-008 — Role/designation transfers record before/after values, reason, approver and date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Role/designation transfers record before/after values, reason, approver and date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-009 — Suspension disables the account without deleting the member row.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Suspension disables the account without deleting the member row. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-010 — Exit status revokes access and preserves required history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit status revokes access and preserves required history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-011 — Digital ID shows only minimal public member data and can be revoked.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Digital ID shows only minimal public member data and can be revoked. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-012 — Profile photo changes are private, validated and auditable.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Profile photo changes are private, validated and auditable. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Roles, permissions and least privilege

**Related modules:** permissions_access, sessions_devices, org_directory

**Suggested owner:** Founder / Super Admin

### UH-013 — Founder can access all platform modules and administrative settings.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Founder can access all platform modules and administrative settings. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-014 — Super Admin can administer platform operations without silently replacing the Founder.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Super Admin can administer platform operations without silently replacing the Founder. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-015 — Admin permissions are restricted to explicitly assigned operational modules.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Admin permissions are restricted to explicitly assigned operational modules. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-016 — HR can view and change only authorised HR/member data.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: HR can view and change only authorised HR/member data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-017 — Project Lead can access only assigned project records and permitted shared content.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Project Lead can access only assigned project records and permitted shared content. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-018 — Employee sees own records, assigned work and company-approved directory fields.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee sees own records, assigned work and company-approved directory fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-019 — Security Reviewer sees relevant security/audit data without general HR or finance access.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security Reviewer sees relevant security/audit data without general HR or finance access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-020 — Every API checks permissions server-side; hidden buttons are not treated as security.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Every API checks permissions server-side; hidden buttons are not treated as security. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-021 — Access defaults to deny for unknown roles, modules and record scopes.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Access defaults to deny for unknown roles, modules and record scopes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-022 — Privileged role grants are restricted and require recorded business reason.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged role grants are restricted and require recorded business reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-023 — High-risk grants use two distinct approvers and prevent self-approval.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk grants use two distinct approvers and prevent self-approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-024 — Access review records include owner, scope, recertification date and revocation.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Access review records include owner, scope, recertification date and revocation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Projects, milestones, tasks and submissions

**Related modules:** projects, milestones, tasks, task_submissions, decisions

**Suggested owner:** Project Lead / Admin

### UH-025 — Project records include objective, owner, department, priority and acceptance criteria.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Project records include objective, owner, department, priority and acceptance criteria. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-026 — Projects track dependencies, risks, budget references and closure state.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Projects track dependencies, risks, budget references and closure state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-027 — Milestones have owners, target dates, evidence and acceptance decisions.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Milestones have owners, target dates, evidence and acceptance decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-028 — Tasks support assignee, priority, due date, status and project linkage.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Tasks support assignee, priority, due date, status and project linkage. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-029 — Task dependency references are validated and blocked dependencies are visible.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Task dependency references are validated and blocked dependencies are visible. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-030 — Task submissions retain evidence references and revision numbers.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Task submissions retain evidence references and revision numbers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-031 — Reviewer can accept, reject or request revisions with written notes.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Reviewer can accept, reject or request revisions with written notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-032 — Overdue tasks are detected by a scheduled reminder job.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Overdue tasks are detected by a scheduled reminder job. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-033 — Task reassignment records the old owner, new owner, reason and timestamp.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Task reassignment records the old owner, new owner, reason and timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-034 — Project Lead task visibility is scoped to assigned project or owned records.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Project Lead task visibility is scoped to assigned project or owned records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-035 — Blocked tasks include a blocker and employee clarification path.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Blocked tasks include a blocker and employee clarification path. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-036 — Project closure checks open tasks, approvals, assets and document handover.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Project closure checks open tasks, approvals, assets and document handover. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Work status, availability and attendance

**Related modules:** employee_status, attendance, time_tracking, leave, tasks

**Suggested owner:** HR / Project Lead

### UH-037 — Work-status cards distinguish active, blocked, awaiting review, at risk and overdue.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Work-status cards distinguish active, blocked, awaiting review, at risk and overdue. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-038 — On-leave, suspended and exited states remain separate from performance risk.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: On-leave, suspended and exited states remain separate from performance risk. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-039 — Last work activity is derived from recorded actions rather than login alone.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Last work activity is derived from recorded actions rather than login alone. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-040 — Configurable inactivity reminders prompt human review rather than automatic discipline.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Configurable inactivity reminders prompt human review rather than automatic discipline. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-041 — Employee can add context or appeal a status classification.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee can add context or appeal a status classification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-042 — Weekly work summaries use completed-task and approved worklog evidence.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Weekly work summaries use completed-task and approved worklog evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-043 — Availability and attendance notes can be entered by authorised members.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Availability and attendance notes can be entered by authorised members. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-044 — Attendance changes have a reason and approval trail where applicable.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Attendance changes have a reason and approval trail where applicable. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-045 — Private leave reasons are not exposed on broad calendars.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Private leave reasons are not exposed on broad calendars. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-046 — Work-status review records identify reviewer and review date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Work-status review records identify reviewer and review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-047 — No single KPI or inactivity signal automatically terminates or disciplines a member.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: No single KPI or inactivity signal automatically terminates or disciplines a member. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-048 — Attendance integrations are disabled until the specific provider and privacy review are configured.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Attendance integrations are disabled until the specific provider and privacy review are configured. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## KPI, reviews and fair performance management

**Related modules:** kpis, performance_reviews, goals, employee_status

**Suggested owner:** Founder / HR / Project Lead

### UH-049 — KPI definitions include owner, target, actual, unit and review period.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI definitions include owner, target, actual, unit and review period. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-050 — KPI direction specifies whether higher or lower values are preferred.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI direction specifies whether higher or lower values are preferred. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-051 — KPI attainment is calculated consistently and displays the formula used.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI attainment is calculated consistently and displays the formula used. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-052 — Quality and timeliness are not hidden behind one unexplained composite score.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Quality and timeliness are not hidden behind one unexplained composite score. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-053 — KPI targets and actuals retain version and reason history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI targets and actuals retain version and reason history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-054 — Performance review has goals, outcomes, support needs and reviewer ownership.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Performance review has goals, outcomes, support needs and reviewer ownership. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-055 — Employee can acknowledge a review and submit a response or appeal.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee can acknowledge a review and submit a response or appeal. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-056 — Reviewer cannot silently rewrite employee responses or evidence.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Reviewer cannot silently rewrite employee responses or evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-057 — Department comparison is permission-filtered and context-aware.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Department comparison is permission-filtered and context-aware. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-058 — Review reminders and due dates are visible to responsible owners.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Review reminders and due dates are visible to responsible owners. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-059 — A score alone cannot trigger automatic suspension, demotion or termination.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: A score alone cannot trigger automatic suspension, demotion or termination. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-060 — KPI formula configuration is reviewed and tested before company-wide use.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI formula configuration is reviewed and tested before company-wide use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Company goals and executive dashboard

**Related modules:** goals, kpis, risks, decisions, projects

**Suggested owner:** Founder / Admin

### UH-061 — Company, department and project goals have accountable owners and periods.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Company, department and project goals have accountable owners and periods. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-062 — Goal progress can be rolled up from approved milestone/task evidence.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Goal progress can be rolled up from approved milestone/task evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-063 — Executive dashboard shows overdue approvals, blocked work and major risks.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Executive dashboard shows overdue approvals, blocked work and major risks. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-064 — Goals include dependencies and mitigation notes.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Goals include dependencies and mitigation notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-065 — Monthly and quarterly progress snapshots can be retained for comparison.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Monthly and quarterly progress snapshots can be retained for comparison. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-066 — Restricted HR, grievance and finance records do not leak into broad summaries.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Restricted HR, grievance and finance records do not leak into broad summaries. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-067 — Dashboard totals match the underlying permission-filtered records.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Dashboard totals match the underlying permission-filtered records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-068 — Leadership summaries cite source date and data freshness.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Leadership summaries cite source date and data freshness. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-069 — Owners can update progress with an explanation and evidence reference.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Owners can update progress with an explanation and evidence reference. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-070 — Goal changes capture original target, new target, reason and approver.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Goal changes capture original target, new target, reason and approver. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-071 — Company-level exports are permission-gated and audited.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Company-level exports are permission-gated and audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-072 — Executive metrics are labelled as unavailable when source data is missing.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Executive metrics are labelled as unavailable when source data is missing. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Assets, inventory and procurement

**Related modules:** assets, inventory, vendors, finance, offboarding

**Suggested owner:** Admin / HR

### UH-073 — Each trackable asset has a unique asset tag or QR identifier.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Each trackable asset has a unique asset tag or QR identifier. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-074 — Assets include condition, purchase date, warranty and ownership fields.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Assets include condition, purchase date, warranty and ownership fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-075 — Issue, return, repair, loss and handover events have a movement history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Issue, return, repair, loss and handover events have a movement history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-076 — Inventory tracks stock quantity and reorder thresholds.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Inventory tracks stock quantity and reorder thresholds. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-077 — Stock adjustments require a reason and authorised approval.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Stock adjustments require a reason and authorised approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-078 — Software licences track seats, assignment and renewal date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Software licences track seats, assignment and renewal date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-079 — Purchase requests capture amount, cost centre, vendor and justification.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Purchase requests capture amount, cost centre, vendor and justification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-080 — Financial approvals use configured thresholds and distinct approvers.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Financial approvals use configured thresholds and distinct approvers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-081 — Low-stock and warranty reminders go to accountable owners.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Low-stock and warranty reminders go to accountable owners. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-082 — Exited-member assets appear on the handover checklist until reconciled.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Exited-member assets appear on the handover checklist until reconciled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-083 — Asset deletion is replaced with retirement/archiving while history is retained.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Asset deletion is replaced with retirement/archiving while history is retained. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-084 — Inventory reconciliation compares ledger quantities to a physical count.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Inventory reconciliation compares ledger quantities to a physical count. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Authentication, account security and sessions

**Related modules:** sessions_devices, permissions_access, onboarding, incidents

**Suggested owner:** Founder / Super Admin

### UH-085 — Passwords are stored only as a salted adaptive hash, never in plaintext.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Passwords are stored only as a salted adaptive hash, never in plaintext. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-086 — Login attempts are rate-limited and failure events are recorded safely.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Login attempts are rate-limited and failure events are recorded safely. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-087 — Session identifiers rotate after login and password change.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Session identifiers rotate after login and password change. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-088 — Session cookies are HttpOnly, SameSite and Secure behind HTTPS.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Session cookies are HttpOnly, SameSite and Secure behind HTTPS. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-089 — Logout destroys the server-side session and clears the browser cookie.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Logout destroys the server-side session and clears the browser cookie. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-090 — Suspended or exited accounts are denied on the next authenticated request.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Suspended or exited accounts are denied on the next authenticated request. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-091 — Password change requires the existing password and a strong replacement.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Password change requires the existing password and a strong replacement. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-092 — Privileged accounts enforce MFA before production access.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged accounts enforce MFA before production access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-093 — Email verification and password-reset links use expiring, single-use tokens.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Email verification and password-reset links use expiring, single-use tokens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-094 — Recovery workflows prevent account takeover and are audited.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Recovery workflows prevent account takeover and are audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-095 — Device/session listing supports individual and global session revocation.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Device/session listing supports individual and global session revocation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-096 — Secrets are stored outside source control and rotated after exposure or recovery.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Secrets are stored outside source control and rotated after exposure or recovery. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Knowledge base, policies and document vault

**Related modules:** knowledge, policies, document_vault, compliance

**Suggested owner:** HR / Project Lead

### UH-097 — Knowledge items have owner, version, classification and review date.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Knowledge items have owner, version, classification and review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-098 — Knowledge search respects module and document access permissions.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Knowledge search respects module and document access permissions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-099 — Policy acknowledgements capture exact version and time.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy acknowledgements capture exact version and time. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-100 — Private files are stored outside the public web root.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Private files are stored outside the public web root. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-101 — File downloads re-check user role, record scope and classification.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: File downloads re-check user role, record scope and classification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-102 — Uploaded files have size/type limits and content-signature checks.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Uploaded files have size/type limits and content-signature checks. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-103 — File upload records include SHA-256 checksum and uploader.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: File upload records include SHA-256 checksum and uploader. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-104 — Malware scanning/quarantine runs before a file becomes trusted.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Malware scanning/quarantine runs before a file becomes trusted. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-105 — Confidential documents use expiring access links and audited downloads.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Confidential documents use expiring access links and audited downloads. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-106 — Document version history retains prior versions under a retention policy.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Document version history retains prior versions under a retention policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-107 — Downloaded copies cannot be remotely recalled and are labelled accordingly.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Downloaded copies cannot be remotely recalled and are labelled accordingly. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-108 — Vault keys and storage credentials are separate from application and backup keys.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Vault keys and storage credentials are separate from application and backup keys. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Helpdesk and confidential grievances

**Related modules:** helpdesk, grievances, hr_cases, incidents

**Suggested owner:** HR / Security Reviewer

### UH-109 — Helpdesk tickets record requester, owner, priority, status and due date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Helpdesk tickets record requester, owner, priority, status and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-110 — Ticket SLA reminders escalate to the current owner and manager.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Ticket SLA reminders escalate to the current owner and manager. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-111 — Resolution notes explain what was done and when.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Resolution notes explain what was done and when. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-112 — Closed tickets can be reopened with a reason.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Closed tickets can be reopened with a reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-113 — Confidential grievances are isolated from ordinary support tickets.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Confidential grievances are isolated from ordinary support tickets. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-114 — Case owners complete conflict-of-interest checks and can be reassigned.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Case owners complete conflict-of-interest checks and can be reassigned. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-115 — Complainants can track status without seeing restricted internal notes.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Complainants can track status without seeing restricted internal notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-116 — Appeals have a separate owner and due date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Appeals have a separate owner and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-117 — Anti-retaliation and confidentiality guidance is visible to authorised reviewers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Anti-retaliation and confidentiality guidance is visible to authorised reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-118 — Case access and export events are logged without leaking complaint text.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Case access and export events are logged without leaking complaint text. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-119 — HR complaint access is limited to assigned, impartial roles.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: HR complaint access is limited to assigned, impartial roles. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-120 — External reporting or emergency contact procedures are configured to company policy.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: External reporting or emergency contact procedures are configured to company policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Contracts, legal approvals and retention

**Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting)

**Suggested owner:** Founder / HR

### UH-121 — Agreements record type, counterparty, owner, status and effective dates.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Agreements record type, counterparty, owner, status and effective dates. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-122 — Expiry and renewal reminders are sent before the deadline.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Expiry and renewal reminders are sent before the deadline. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-123 — Legal documents are linked to restricted vault references, not public URLs.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal documents are linked to restricted vault references, not public URLs. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-124 — NDA and contract acknowledgements retain version and signature status.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: NDA and contract acknowledgements retain version and signature status. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-125 — Legal hold prevents scheduled disposal of relevant content.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal hold prevents scheduled disposal of relevant content. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-126 — High-risk contract approvals require distinct approvers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk contract approvals require distinct approvers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-127 — Signature provider integration verifies signer identity and final document hash.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Signature provider integration verifies signer identity and final document hash. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-128 — Contract downloads are permission-gated and audited.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract downloads are permission-gated and audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-129 — Retention periods are documented by record class and business purpose.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Retention periods are documented by record class and business purpose. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-130 — Legal requests are reviewed by qualified counsel where required.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal requests are reviewed by qualified counsel where required. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-131 — Contract corrections retain prior values and reason.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract corrections retain prior values and reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-132 — The product never claims legal compliance without jurisdiction-specific review.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: The product never claims legal compliance without jurisdiction-specific review. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Announcements, leave, meetings and collaboration

**Related modules:** announcements, leave, meetings, decisions, task_submissions

**Suggested owner:** HR / Project Lead

### UH-133 — Announcements support audience, publish date and expiry date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Announcements support audience, publish date and expiry date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-134 — Read receipts are recorded by member and announcement version.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Read receipts are recorded by member and announcement version. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-135 — Corrections link to the original announcement and retain history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Corrections link to the original announcement and retain history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-136 — Leave requests have dates, type, approver and decision reason.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Leave requests have dates, type, approver and decision reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-137 — Leave balances update through an approved ledger, not manual hidden edits.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Leave balances update through an approved ledger, not manual hidden edits. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-138 — Overlapping leave requests are detected before approval.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Overlapping leave requests are detected before approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-139 — Shared calendars expose availability without unnecessary private details.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Shared calendars expose availability without unnecessary private details. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-140 — Meetings store agenda, attendees, minutes and decisions.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Meetings store agenda, attendees, minutes and decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-141 — Action items include owner, due date and current state.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Action items include owner, due date and current state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-142 — Notifications have read state, severity and a relevant record link.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Notifications have read state, severity and a relevant record link. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-143 — Email/push delivery uses a configured provider with retry and delivery status.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Email/push delivery uses a configured provider with retry and delivery status. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-144 — Meeting or comment moderation is auditable and does not hard-delete member history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Meeting or comment moderation is auditable and does not hard-delete member history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Audit trails, incidents and governance

**Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access

**Suggested owner:** Security Reviewer / Founder

### UH-145 — Sensitive actions capture actor, target, time, outcome and reason.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive actions capture actor, target, time, outcome and reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-146 — Record create/update/archive events have a before/after history.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Record create/update/archive events have a before/after history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-147 — Comment hiding preserves the original text and the moderation reason.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Comment hiding preserves the original text and the moderation reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-148 — Security incidents track severity, owner, containment, remediation and closure.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security incidents track severity, owner, containment, remediation and closure. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-149 — Critical incidents notify the Founder/Super Admin through configured channels.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical incidents notify the Founder/Super Admin through configured channels. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-150 — Audit viewing is restricted by role and domain.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit viewing is restricted by role and domain. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-151 — Permission changes include the previous and new values.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Permission changes include the previous and new values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-152 — Audit storage is append-only for application users and protected from ordinary admins.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit storage is append-only for application users and protected from ordinary admins. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-153 — Remote immutable audit storage is configured for production.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Remote immutable audit storage is configured for production. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-154 — Incident postmortems record root cause and assigned corrective actions.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident postmortems record root cause and assigned corrective actions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-155 — High-risk actions can require two-person approval.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk actions can require two-person approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-156 — Audit exports are scope-limited, reasoned and logged.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit exports are scope-limited, reasoned and logged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Backups, recovery and continuity

**Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting)

**Suggested owner:** Founder / Super Admin

### UH-157 — Backup scope includes database records and private attachments.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup scope includes database records and private attachments. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-158 — Backup archive is encrypted with authenticated encryption.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup archive is encrypted with authenticated encryption. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-159 — Backup encryption key is stored separately from backup files.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup encryption key is stored separately from backup files. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-160 — Backup filename, manifest and timestamps are recorded.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup filename, manifest and timestamps are recorded. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-161 — Session state is excluded from restore to force fresh authentication.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Session state is excluded from restore to force fresh authentication. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-162 — Backup schedule has an explicit owner and failure alert path.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup schedule has an explicit owner and failure alert path. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-163 — An isolated or immutable copy exists outside the production host.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: An isolated or immutable copy exists outside the production host. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-164 — Restore refuses to overwrite a live database by default.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Restore refuses to overwrite a live database by default. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-165 — Restored database passes integrity checks before service startup.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Restored database passes integrity checks before service startup. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-166 — Private file hashes/counts are verified during restore drills.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Private file hashes/counts are verified during restore drills. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-167 — RPO and RTO are documented for each critical service.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: RPO and RTO are documented for each critical service. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-168 — A restore drill is completed and signed off on a recurring schedule.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: A restore drill is completed and signed off on a recurring schedule. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Privacy requests and data lifecycle

**Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting)

**Suggested owner:** Founder / HR

### UH-169 — Privacy requests cover access, correction, export and deletion review.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Privacy requests cover access, correction, export and deletion review. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-170 — Requester identity and authority are verified before disclosing data.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Requester identity and authority are verified before disclosing data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-171 — Each request has owner, legal basis, due date, status and audit history.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Each request has owner, legal basis, due date, status and audit history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-172 — Correction creates a traceable change instead of silently overwriting history.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Correction creates a traceable change instead of silently overwriting history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-173 — Deletion requests are reviewed against legal holds and retention obligations.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Deletion requests are reviewed against legal holds and retention obligations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-174 — No ordinary route hard-deletes member accounts or member history.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: No ordinary route hard-deletes member accounts or member history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-175 — Retention schedules are approved for each record category.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Retention schedules are approved for each record category. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-176 — Expired content is disposed through an approved, logged retention job when lawful.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Expired content is disposed through an approved, logged retention job when lawful. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-177 — Backups age out under a documented retention policy.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backups age out under a documented retention policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-178 — Data-subject exports are scoped to the verified requester.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Data-subject exports are scoped to the verified requester. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-179 — Data minimisation applies to directory and public digital ID fields.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Data minimisation applies to directory and public digital ID fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-180 — Applicable Indian privacy obligations are reviewed by qualified counsel before launch.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Applicable Indian privacy obligations are reviewed by qualified counsel before launch. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Integrations, vendors and system operations

**Related modules:** integrations, vendors, releases, continuity, backup_jobs

**Suggested owner:** Founder / Admin

### UH-181 — Integration register names provider, owner, purpose and data exchanged.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Integration register names provider, owner, purpose and data exchanged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-182 — Integration scopes use least privilege and are documented.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Integration scopes use least privilege and are documented. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-183 — Access tokens are stored in a secret manager and never rendered to users.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Access tokens are stored in a secret manager and never rendered to users. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-184 — Credential rotation dates and owners are tracked.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Credential rotation dates and owners are tracked. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-185 — Sync jobs record last success, last failure and retry state.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Sync jobs record last success, last failure and retry state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-186 — Repeated integration failures create an alert and incident reference.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Repeated integration failures create an alert and incident reference. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-187 — Vendors have risk rating, contract and review dates.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendors have risk rating, contract and review dates. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-188 — Vendor access expires when no longer needed.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendor access expires when no longer needed. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-189 — Schema migrations are versioned and tested before deployment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Schema migrations are versioned and tested before deployment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-190 — Staging environment is separate from production data.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Staging environment is separate from production data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-191 — Releases include health checks and a tested rollback procedure.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Releases include health checks and a tested rollback procedure. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-192 — Cost, rate limits and provider outages are monitored with alert thresholds.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Cost, rate limits and provider outages are monitored with alert thresholds. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Exit, handover and ownership transfer

**Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices

**Suggested owner:** HR / Project Lead

### UH-193 — Exit is a workflow with approver, exit date and completion checklist.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit is a workflow with approver, exit date and completion checklist. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-194 — Active sessions are revoked and future logins blocked on suspension/exit.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Active sessions are revoked and future logins blocked on suspension/exit. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-195 — Project ownership transfers before a project lead exits.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Project ownership transfers before a project lead exits. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-196 — Open tasks are reassigned with the reason and new owner.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Open tasks are reassigned with the reason and new owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-197 — Private files, documents and knowledge articles retain an accountable owner.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Private files, documents and knowledge articles retain an accountable owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-198 — Issued assets and software seats are returned or reassigned.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Issued assets and software seats are returned or reassigned. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-199 — Vendor/service accounts are rotated or revoked on exit.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendor/service accounts are rotated or revoked on exit. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-200 — Legal hold and retention checks run before an account is finalised.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal hold and retention checks run before an account is finalised. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-201 — Final access checklist is acknowledged by accountable reviewers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Final access checklist is acknowledged by accountable reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-202 — Employee history remains linked to a stable member ID.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee history remains linked to a stable member ID. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-203 — Exit completion reports identify blocked tasks and unresolved items.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit completion reports identify blocked tasks and unresolved items. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-204 — Offboarding requires a second reviewer for privileged accounts.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Offboarding requires a second reviewer for privileged accounts. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Reports, exports and data quality

**Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting)

**Suggested owner:** Founder / Super Admin

### UH-205 — Reports are filtered to the requesting user’s role and scope.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Reports are filtered to the requesting user’s role and scope. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-206 — Exports require a business reason and are logged.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Exports require a business reason and are logged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-207 — Large exports are rate-limited and visible to security reviewers.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Large exports are rate-limited and visible to security reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-208 — CSV/JSON outputs encode data safely and avoid spreadsheet formula injection.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: CSV/JSON outputs encode data safely and avoid spreadsheet formula injection. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-209 — Dashboard metrics reconcile with source records.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Dashboard metrics reconcile with source records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-210 — KPI reports include period, formula version and refresh timestamp.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI reports include period, formula version and refresh timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-211 — Missing data is labelled rather than silently treated as zero.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Missing data is labelled rather than silently treated as zero. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-212 — Data fields use consistent timezones and ISO timestamps.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Data fields use consistent timezones and ISO timestamps. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-213 — Duplicate identifiers and invalid state changes are rejected.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Duplicate identifiers and invalid state changes are rejected. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-214 — Records have a clear owner and an accountable review date.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Records have a clear owner and an accountable review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-215 — Aged records can be flagged for review without auto-deletion.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Aged records can be flagged for review without auto-deletion. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-216 — Report consumers can trace a metric back to approved source records.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Report consumers can trace a metric back to approved source records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Notifications and SLA automation

**Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting)

**Suggested owner:** Admin / HR / Project Lead

### UH-217 — In-app notifications are personal to the intended recipient.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: In-app notifications are personal to the intended recipient. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-218 — Unread counts are consistent with the notification table.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Unread counts are consistent with the notification table. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-219 — Overdue task reminders are idempotent within the configured window.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Overdue task reminders are idempotent within the configured window. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-220 — Contract/vendor/asset renewal warnings are generated before expiry.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract/vendor/asset renewal warnings are generated before expiry. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-221 — Inactive-work alerts prompt human review instead of automatic punishment.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Inactive-work alerts prompt human review instead of automatic punishment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-222 — Scheduled jobs record started time, finish time, details and failure state.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Scheduled jobs record started time, finish time, details and failure state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-223 — Job failures create a visible security/operations event.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Job failures create a visible security/operations event. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-224 — Notification text excludes passwords, OTPs and secret tokens.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Notification text excludes passwords, OTPs and secret tokens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-225 — External email delivery retries safely and records provider response.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: External email delivery retries safely and records provider response. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-226 — Critical notification routing has a documented backup route.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical notification routing has a documented backup route. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-227 — SLA escalation policies are configurable by ticket category and severity.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: SLA escalation policies are configurable by ticket category and severity. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-228 — Operators can trigger a manual reminder run and see its job history.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Operators can trigger a manual reminder run and see its job history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## UI, mobile, accessibility and usability

**Related modules:** portal UI (cross-cutting), all module workspaces

**Suggested owner:** Product Owner / QA

### UH-229 — Portal navigation only shows modules allowed to the signed-in role.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Portal navigation only shows modules allowed to the signed-in role. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-230 — The 40-module catalogue can be searched by module name and description.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: The 40-module catalogue can be searched by module name and description. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-231 — Layout supports narrow mobile screens without losing key actions.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Layout supports narrow mobile screens without losing key actions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-232 — Forms have visible labels and clear validation errors.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Forms have visible labels and clear validation errors. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-233 — Dialogs can be closed without saving and cannot silently discard unsaved data.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Dialogs can be closed without saving and cannot silently discard unsaved data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-234 — Status labels use text, not colour alone.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Status labels use text, not colour alone. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-235 — Long records and audit values wrap safely without running off-screen.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Long records and audit values wrap safely without running off-screen. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-236 — Tables are horizontally scrollable on small screens.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Tables are horizontally scrollable on small screens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-237 — Buttons have clear action labels and visible focus states.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Buttons have clear action labels and visible focus states. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-238 — Loading, empty, error and success states are visible.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Loading, empty, error and success states are visible. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-239 — The interface avoids displaying secrets in profile cards or error traces.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: The interface avoids displaying secrets in profile cards or error traces. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-240 — Screen-reader and keyboard navigation tests pass before release.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Screen-reader and keyboard navigation tests pass before release. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## API, application security and secure coding

**Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes

**Suggested owner:** Developer / Security Reviewer

### UH-241 — Unknown API routes return safe errors without stack traces.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Unknown API routes return safe errors without stack traces. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-242 — Input lengths, content types, enum values and dates are validated server-side.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Input lengths, content types, enum values and dates are validated server-side. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-243 — Parameterised database calls are used for user-controlled values.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Parameterised database calls are used for user-controlled values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-244 — Security headers and a restrictive content security policy are enabled.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security headers and a restrictive content security policy are enabled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-245 — Private uploads never resolve through a static public route.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Private uploads never resolve through a static public route. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-246 — Downloads use attachment disposition and nosniff protection.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Downloads use attachment disposition and nosniff protection. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-247 — Rate limits cover login and sensitive high-cost operations.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Rate limits cover login and sensitive high-cost operations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-248 — CSRF/origin protections match the selected session-cookie deployment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: CSRF/origin protections match the selected session-cookie deployment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-249 — Record IDs cannot bypass module access checks (IDOR test).
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Record IDs cannot bypass module access checks (IDOR test). Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-250 — Logs redact secrets and avoid storing submitted passwords.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Logs redact secrets and avoid storing submitted passwords. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-251 — Dependencies are reviewed for known vulnerabilities before production.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Dependencies are reviewed for known vulnerabilities before production. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-252 — Production secrets are injected through a secret manager or protected environment.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Production secrets are injected through a secret manager or protected environment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Testing, quality gates and release readiness

**Related modules:** releases, continuity, all module workflows

**Suggested owner:** Developer / QA / Security Reviewer

### UH-253 — Unit tests cover module definitions, required fields and allowed statuses.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Unit tests cover module definitions, required fields and allowed statuses. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-254 — API tests cover happy path and invalid input for every module.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: API tests cover happy path and invalid input for every module. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-255 — Role tests verify allowed and denied access for every role/module pair.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Role tests verify allowed and denied access for every role/module pair. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-256 — IDOR tests attempt to access another member’s record by changing record ID.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: IDOR tests attempt to access another member’s record by changing record ID. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-257 — Session tests verify login rotation, logout and suspension.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Session tests verify login rotation, logout and suspension. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-258 — File tests cover size limits, signature mismatch and access denial.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: File tests cover size limits, signature mismatch and access denial. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-259 — Backup/restore tests verify encryption failure and integrity failure paths.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup/restore tests verify encryption failure and integrity failure paths. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-260 — Approval tests verify self-approval and same-person second approval are rejected.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Approval tests verify self-approval and same-person second approval are rejected. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-261 — Database migrations run on a clean install and an older database snapshot.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Database migrations run on a clean install and an older database snapshot. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-262 — Build has a reproducible lockfile and CI checks on each change.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Build has a reproducible lockfile and CI checks on each change. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-263 — Critical/high security findings are resolved before launch.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical/high security findings are resolved before launch. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-264 — End-to-end test report records test date, version, result and tester.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: End-to-end test report records test date, version, result and tester. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Production deployment, monitoring and support

**Related modules:** releases, continuity, integrations, vendors, operational jobs

**Suggested owner:** Technical Owner / Founder

### UH-265 — Production runs behind HTTPS with secure cookies enabled.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Production runs behind HTTPS with secure cookies enabled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-266 — Database and uploads use protected persistent storage with least-privilege OS access.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Database and uploads use protected persistent storage with least-privilege OS access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-267 — Database WAL/SHM and backup handling are included in operational procedures.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Database WAL/SHM and backup handling are included in operational procedures. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-268 — Health endpoint reports status without exposing secrets or sensitive configuration.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Health endpoint reports status without exposing secrets or sensitive configuration. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-269 — Uptime, latency, error rate and disk capacity are monitored.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Uptime, latency, error rate and disk capacity are monitored. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-270 — Logs have retention, access control, redaction and alerting.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Logs have retention, access control, redaction and alerting. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-271 — Container runs as a non-root user with a reviewed image.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Container runs as a non-root user with a reviewed image. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-272 — Deployment supports environment-specific configuration and secret rotation.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Deployment supports environment-specific configuration and secret rotation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-273 — Rollback procedure is tested with a recent backup.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Rollback procedure is tested with a recent backup. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-274 — Incident-response contacts and escalation rota are documented.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident-response contacts and escalation rota are documented. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-275 — Public deployment waits until unresolved security gates are signed off.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Public deployment waits until unresolved security gates are signed off. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-276 — Production readiness owner signs off every blocker with attached evidence.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Production readiness owner signs off every blocker with attached evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Company governance, fairness and continuous improvement

**Related modules:** goals, performance_reviews, compliance, decisions, grievances

**Suggested owner:** Founder / HR / Security Reviewer

### UH-277 — Every module has an accountable owner and an explicit intended use.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Every module has an accountable owner and an explicit intended use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-278 — Role matrix is version-controlled and reviewed after team changes.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Role matrix is version-controlled and reviewed after team changes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-279 — No shared Founder or Super Admin accounts are used.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: No shared Founder or Super Admin accounts are used. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-280 — Access grants are time-bound where practical and removed when expired.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Access grants are time-bound where practical and removed when expired. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-281 — Self-approval and conflict-of-interest rules are applied consistently.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Self-approval and conflict-of-interest rules are applied consistently. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-282 — Employee-facing explanations describe work-status and KPI calculations.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee-facing explanations describe work-status and KPI calculations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-283 — Employees have a way to provide context and appeal decisions.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Employees have a way to provide context and appeal decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-284 — Sensitive HR and grievance content is restricted to need-to-know roles.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive HR and grievance content is restricted to need-to-know roles. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-285 — Policy changes retain version, effective date and acknowledgement state.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy changes retain version, effective date and acknowledgement state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-286 — Release feedback is captured with prioritisation and owner.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Release feedback is captured with prioritisation and owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-287 — A quarterly review updates checklist status and evidence links.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: A quarterly review updates checklist status and evidence links. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-288 — No feature is marked complete until behaviour, permission tests and operational ownership are evidenced.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: No feature is marked complete until behaviour, permission tests and operational ownership are evidenced. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

## Analytics, incident drills and security operations

**Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access

**Suggested owner:** Security Reviewer / Founder

### UH-289 — Security events can be triaged by severity, owner and due date.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security events can be triaged by severity, owner and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-290 — Incident response exercises test detection, escalation, containment and recovery.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident response exercises test detection, escalation, containment and recovery. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-291 — Sensitive exports and unusually high record access generate reviewable events.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive exports and unusually high record access generate reviewable events. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-292 — Authentication logs exclude password contents, session IDs and OTP values.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Authentication logs exclude password contents, session IDs and OTP values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-293 — Privileged account recovery has a documented break-glass process.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged account recovery has a documented break-glass process. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-294 — Break-glass use alerts the Founder and is reviewed after use.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Break-glass use alerts the Founder and is reviewed after use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-295 — Backups and restore credentials are tested independently from day-to-day logins.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Backups and restore credentials are tested independently from day-to-day logins. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-296 — Operational job runtimes and failures are measurable over time.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Operational job runtimes and failures are measurable over time. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-297 — Security controls have named owners, review dates and exception records.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security controls have named owners, review dates and exception records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-298 — Post-incident corrective actions have owners and closure evidence.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Post-incident corrective actions have owners and closure evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-299 — Data retention and access reviews are recorded on a calendar.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Data retention and access reviews are recorded on a calendar. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.

### UH-300 — Security dashboards disclose only data appropriate to the viewer role.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Acceptance check:** In a disposable test environment, execute this scenario: Security dashboards disclose only data appropriate to the viewer role. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence / notes:** Add tester, test date, evidence link and any approved exception.
