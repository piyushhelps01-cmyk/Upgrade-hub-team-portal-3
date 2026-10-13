# UpgradeHub Team Management Portal — Master Acceptance Checklist v4.0

**Controls:** 732 · **Sections:** 79 · **Module workspaces:** 67 · **Roles:** 7

> Important: checklist size is not an implementation-completion claim. The original 300 controls are retained for traceability. The additional 432 controls define expanded requirements; they are marked proposed/not run until the actual workflow has been implemented and tested.

## How to use this checklist

- Keep `Validation result` at `Not run` until the required behaviour is demonstrated in a test environment.
- For security controls, test an authorised user and at least one unauthorised role/record ID.
- Record build version, tester, date, evidence link, exception reason and accountable approver.
- UI presence, a module name, or a database field alone does not pass a control.

## Sections

01. Identity, onboarding and member lifecycle — 12 controls
02. Roles, permissions and least privilege — 12 controls
03. Projects, milestones, tasks and submissions — 12 controls
04. Work status, availability and attendance — 12 controls
05. KPI, reviews and fair performance management — 12 controls
06. Company goals and executive dashboard — 12 controls
07. Assets, inventory and procurement — 12 controls
08. Authentication, account security and sessions — 12 controls
09. Knowledge base, policies and document vault — 12 controls
10. Helpdesk and confidential grievances — 12 controls
11. Contracts, legal approvals and retention — 12 controls
12. Announcements, leave, meetings and collaboration — 12 controls
13. Audit trails, incidents and governance — 12 controls
14. Backups, recovery and continuity — 12 controls
15. Privacy requests and data lifecycle — 12 controls
16. Integrations, vendors and system operations — 12 controls
17. Exit, handover and ownership transfer — 12 controls
18. Reports, exports and data quality — 12 controls
19. Notifications and SLA automation — 12 controls
20. UI, mobile, accessibility and usability — 12 controls
21. API, application security and secure coding — 12 controls
22. Testing, quality gates and release readiness — 12 controls
23. Production deployment, monitoring and support — 12 controls
24. Company governance, fairness and continuous improvement — 12 controls
25. Analytics, incident drills and security operations — 12 controls
26. Department structures & cost centres — 8 controls
27. Capacity forecasting & workload balance — 8 controls
28. Shift coverage & handover — 8 controls
29. OKRs & quarterly cycles — 8 controls
30. Anonymous team surveys & pulse — 8 controls
31. Recognition & contribution evidence — 8 controls
32. Communications & brand templates — 8 controls
33. Internal service catalogue & ownership — 8 controls
34. SLA & escalation matrix — 8 controls
35. Purchase-order governance — 8 controls
36. Expense claims & reimbursement — 8 controls
37. Budget & forecasting — 8 controls
38. Client & partner data boundaries — 8 controls
39. Customer feedback triage — 8 controls
40. Sprint planning & capacity — 8 controls
41. QA test-case management — 8 controls
42. Defect triage & regression — 8 controls
43. Code review & change approval — 8 controls
44. Release calendar & freeze windows — 8 controls
45. API inventory & endpoint ownership — 8 controls
46. Secret rotation metadata & ownership — 8 controls
47. Data retention schedule & disposal — 8 controls
48. Legal hold register & custodians — 8 controls
49. Notification routing, deduplication & quiet hours — 8 controls
50. Scheduled reports & export governance — 8 controls
51. Company events, calendar & RSVP — 8 controls
52. Digital member IDs, QR references & revocation — 8 controls
53. Team workload and daily check-ins — 8 controls
54. Blocker escalation & clarification — 8 controls
55. Task dependencies and milestone risk — 8 controls
56. Submission evidence & reviewer quality — 8 controls
57. Project portfolio management — 8 controls
58. Project health score transparency — 8 controls
59. Worklog approvals & hour anomalies — 8 controls
60. Leave-aware planning and coverage — 8 controls
61. Fair inactivity detection and appeal — 8 controls
62. Configurable department KPI formulas — 8 controls
63. Performance review approval and appeals — 8 controls
64. Quarterly company planning & OKR rollups — 8 controls
65. Incident postmortems and corrective actions — 8 controls
66. Business continuity exercise tracking — 8 controls
67. Backup recovery and restore assurance — 8 controls
68. Database integrity and schema migrations — 8 controls
69. Environment configuration and secret management — 8 controls
70. Data classification and document lifecycle — 8 controls
71. Private file scanning and download controls — 8 controls
72. Member photo and digital ID privacy — 8 controls
73. Remote access and device-risk review — 8 controls
74. Audit tamper evidence and retention — 8 controls
75. Security incident communications and breach assessment — 8 controls
76. Role lifecycle approvals and periodic review — 8 controls
77. Onboarding training and policy acknowledgement — 8 controls
78. Offboarding ownership and reconciliation — 8 controls
79. Mobile accessibility and responsive QA — 8 controls

## Identity, onboarding and member lifecycle

### UH-001 — Each person has a unique account, stable member ID and unique work email.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Each person has a unique account, stable member ID and unique work email. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-002 — New accounts start as pending and cannot sign in until approved.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: New accounts start as pending and cannot sign in until approved. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-003 — Member profile stores name, designation, department and work contact.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Member profile stores name, designation, department and work contact. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-004 — Joining date, reporting manager and project assignment can be recorded.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Joining date, reporting manager and project assignment can be recorded. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-005 — Onboarding checklist covers identity verification, policy reading and equipment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Onboarding checklist covers identity verification, policy reading and equipment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-006 — Policy acknowledgements capture member, policy version and timestamp.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy acknowledgements capture member, policy version and timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-007 — Email verification token is generated and delivered before activation.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Email verification token is generated and delivered before activation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-008 — Role/designation transfers record before/after values, reason, approver and date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Role/designation transfers record before/after values, reason, approver and date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-009 — Suspension disables the account without deleting the member row.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Suspension disables the account without deleting the member row. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-010 — Exit status revokes access and preserves required history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit status revokes access and preserves required history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-011 — Digital ID shows only minimal public member data and can be revoked.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Digital ID shows only minimal public member data and can be revoked. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-012 — Profile photo changes are private, validated and auditable.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** org_directory, onboarding, offboarding, policies, assets · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Profile photo changes are private, validated and auditable. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Roles, permissions and least privilege

### UH-013 — Founder can access all platform modules and administrative settings.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Founder can access all platform modules and administrative settings. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-014 — Super Admin can administer platform operations without silently replacing the Founder.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Super Admin can administer platform operations without silently replacing the Founder. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-015 — Admin permissions are restricted to explicitly assigned operational modules.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Admin permissions are restricted to explicitly assigned operational modules. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-016 — HR can view and change only authorised HR/member data.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: HR can view and change only authorised HR/member data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-017 — Project Lead can access only assigned project records and permitted shared content.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Project Lead can access only assigned project records and permitted shared content. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-018 — Employee sees own records, assigned work and company-approved directory fields.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee sees own records, assigned work and company-approved directory fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-019 — Security Reviewer sees relevant security/audit data without general HR or finance access.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Security Reviewer sees relevant security/audit data without general HR or finance access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-020 — Every API checks permissions server-side; hidden buttons are not treated as security.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Every API checks permissions server-side; hidden buttons are not treated as security. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-021 — Access defaults to deny for unknown roles, modules and record scopes.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Access defaults to deny for unknown roles, modules and record scopes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-022 — Privileged role grants are restricted and require recorded business reason.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged role grants are restricted and require recorded business reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-023 — High-risk grants use two distinct approvers and prevent self-approval.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk grants use two distinct approvers and prevent self-approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-024 — Access review records include owner, scope, recertification date and revocation.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** permissions_access, sessions_devices, org_directory · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Access review records include owner, scope, recertification date and revocation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Projects, milestones, tasks and submissions

### UH-025 — Project records include objective, owner, department, priority and acceptance criteria.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Project records include objective, owner, department, priority and acceptance criteria. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-026 — Projects track dependencies, risks, budget references and closure state.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Projects track dependencies, risks, budget references and closure state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-027 — Milestones have owners, target dates, evidence and acceptance decisions.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Milestones have owners, target dates, evidence and acceptance decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-028 — Tasks support assignee, priority, due date, status and project linkage.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Tasks support assignee, priority, due date, status and project linkage. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-029 — Task dependency references are validated and blocked dependencies are visible.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Task dependency references are validated and blocked dependencies are visible. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-030 — Task submissions retain evidence references and revision numbers.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Task submissions retain evidence references and revision numbers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-031 — Reviewer can accept, reject or request revisions with written notes.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Reviewer can accept, reject or request revisions with written notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-032 — Overdue tasks are detected by a scheduled reminder job.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Overdue tasks are detected by a scheduled reminder job. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-033 — Task reassignment records the old owner, new owner, reason and timestamp.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Task reassignment records the old owner, new owner, reason and timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-034 — Project Lead task visibility is scoped to assigned project or owned records.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Project Lead task visibility is scoped to assigned project or owned records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-035 — Blocked tasks include a blocker and employee clarification path.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Blocked tasks include a blocker and employee clarification path. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-036 — Project closure checks open tasks, approvals, assets and document handover.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, task_submissions, decisions · **Suggested owner:** Project Lead / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Project closure checks open tasks, approvals, assets and document handover. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Work status, availability and attendance

### UH-037 — Work-status cards distinguish active, blocked, awaiting review, at risk and overdue.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Work-status cards distinguish active, blocked, awaiting review, at risk and overdue. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-038 — On-leave, suspended and exited states remain separate from performance risk.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: On-leave, suspended and exited states remain separate from performance risk. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-039 — Last work activity is derived from recorded actions rather than login alone.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Last work activity is derived from recorded actions rather than login alone. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-040 — Configurable inactivity reminders prompt human review rather than automatic discipline.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Configurable inactivity reminders prompt human review rather than automatic discipline. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-041 — Employee can add context or appeal a status classification.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee can add context or appeal a status classification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-042 — Weekly work summaries use completed-task and approved worklog evidence.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Weekly work summaries use completed-task and approved worklog evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-043 — Availability and attendance notes can be entered by authorised members.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Availability and attendance notes can be entered by authorised members. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-044 — Attendance changes have a reason and approval trail where applicable.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Attendance changes have a reason and approval trail where applicable. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-045 — Private leave reasons are not exposed on broad calendars.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Private leave reasons are not exposed on broad calendars. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-046 — Work-status review records identify reviewer and review date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Work-status review records identify reviewer and review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-047 — No single KPI or inactivity signal automatically terminates or disciplines a member.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: No single KPI or inactivity signal automatically terminates or disciplines a member. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-048 — Attendance integrations are disabled until the specific provider and privacy review are configured.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** employee_status, attendance, time_tracking, leave, tasks · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Attendance integrations are disabled until the specific provider and privacy review are configured. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## KPI, reviews and fair performance management

### UH-049 — KPI definitions include owner, target, actual, unit and review period.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI definitions include owner, target, actual, unit and review period. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-050 — KPI direction specifies whether higher or lower values are preferred.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI direction specifies whether higher or lower values are preferred. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-051 — KPI attainment is calculated consistently and displays the formula used.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI attainment is calculated consistently and displays the formula used. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-052 — Quality and timeliness are not hidden behind one unexplained composite score.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Quality and timeliness are not hidden behind one unexplained composite score. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-053 — KPI targets and actuals retain version and reason history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI targets and actuals retain version and reason history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-054 — Performance review has goals, outcomes, support needs and reviewer ownership.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Performance review has goals, outcomes, support needs and reviewer ownership. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-055 — Employee can acknowledge a review and submit a response or appeal.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee can acknowledge a review and submit a response or appeal. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-056 — Reviewer cannot silently rewrite employee responses or evidence.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Reviewer cannot silently rewrite employee responses or evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-057 — Department comparison is permission-filtered and context-aware.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Department comparison is permission-filtered and context-aware. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-058 — Review reminders and due dates are visible to responsible owners.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Review reminders and due dates are visible to responsible owners. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-059 — A score alone cannot trigger automatic suspension, demotion or termination.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: A score alone cannot trigger automatic suspension, demotion or termination. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-060 — KPI formula configuration is reviewed and tested before company-wide use.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** kpis, performance_reviews, goals, employee_status · **Suggested owner:** Founder / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI formula configuration is reviewed and tested before company-wide use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Company goals and executive dashboard

### UH-061 — Company, department and project goals have accountable owners and periods.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Company, department and project goals have accountable owners and periods. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-062 — Goal progress can be rolled up from approved milestone/task evidence.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Goal progress can be rolled up from approved milestone/task evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-063 — Executive dashboard shows overdue approvals, blocked work and major risks.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Executive dashboard shows overdue approvals, blocked work and major risks. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-064 — Goals include dependencies and mitigation notes.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Goals include dependencies and mitigation notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-065 — Monthly and quarterly progress snapshots can be retained for comparison.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Monthly and quarterly progress snapshots can be retained for comparison. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-066 — Restricted HR, grievance and finance records do not leak into broad summaries.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Restricted HR, grievance and finance records do not leak into broad summaries. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-067 — Dashboard totals match the underlying permission-filtered records.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Dashboard totals match the underlying permission-filtered records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-068 — Leadership summaries cite source date and data freshness.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Leadership summaries cite source date and data freshness. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-069 — Owners can update progress with an explanation and evidence reference.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Owners can update progress with an explanation and evidence reference. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-070 — Goal changes capture original target, new target, reason and approver.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Goal changes capture original target, new target, reason and approver. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-071 — Company-level exports are permission-gated and audited.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Company-level exports are permission-gated and audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-072 — Executive metrics are labelled as unavailable when source data is missing.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, kpis, risks, decisions, projects · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Executive metrics are labelled as unavailable when source data is missing. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Assets, inventory and procurement

### UH-073 — Each trackable asset has a unique asset tag or QR identifier.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Each trackable asset has a unique asset tag or QR identifier. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-074 — Assets include condition, purchase date, warranty and ownership fields.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Assets include condition, purchase date, warranty and ownership fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-075 — Issue, return, repair, loss and handover events have a movement history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Issue, return, repair, loss and handover events have a movement history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-076 — Inventory tracks stock quantity and reorder thresholds.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Inventory tracks stock quantity and reorder thresholds. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-077 — Stock adjustments require a reason and authorised approval.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Stock adjustments require a reason and authorised approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-078 — Software licences track seats, assignment and renewal date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Software licences track seats, assignment and renewal date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-079 — Purchase requests capture amount, cost centre, vendor and justification.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Purchase requests capture amount, cost centre, vendor and justification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-080 — Financial approvals use configured thresholds and distinct approvers.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Financial approvals use configured thresholds and distinct approvers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-081 — Low-stock and warranty reminders go to accountable owners.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Low-stock and warranty reminders go to accountable owners. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-082 — Exited-member assets appear on the handover checklist until reconciled.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Exited-member assets appear on the handover checklist until reconciled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-083 — Asset deletion is replaced with retirement/archiving while history is retained.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Asset deletion is replaced with retirement/archiving while history is retained. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-084 — Inventory reconciliation compares ledger quantities to a physical count.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** assets, inventory, vendors, finance, offboarding · **Suggested owner:** Admin / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Inventory reconciliation compares ledger quantities to a physical count. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Authentication, account security and sessions

### UH-085 — Passwords are stored only as a salted adaptive hash, never in plaintext.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Passwords are stored only as a salted adaptive hash, never in plaintext. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-086 — Login attempts are rate-limited and failure events are recorded safely.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Login attempts are rate-limited and failure events are recorded safely. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-087 — Session identifiers rotate after login and password change.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Session identifiers rotate after login and password change. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-088 — Session cookies are HttpOnly, SameSite and Secure behind HTTPS.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Session cookies are HttpOnly, SameSite and Secure behind HTTPS. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-089 — Logout destroys the server-side session and clears the browser cookie.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Logout destroys the server-side session and clears the browser cookie. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-090 — Suspended or exited accounts are denied on the next authenticated request.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Suspended or exited accounts are denied on the next authenticated request. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-091 — Password change requires the existing password and a strong replacement.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Password change requires the existing password and a strong replacement. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-092 — Privileged accounts enforce MFA before production access.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged accounts enforce MFA before production access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-093 — Email verification and password-reset links use expiring, single-use tokens.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Email verification and password-reset links use expiring, single-use tokens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-094 — Recovery workflows prevent account takeover and are audited.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Recovery workflows prevent account takeover and are audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-095 — Device/session listing supports individual and global session revocation.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Device/session listing supports individual and global session revocation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-096 — Secrets are stored outside source control and rotated after exposure or recovery.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, onboarding, incidents · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Secrets are stored outside source control and rotated after exposure or recovery. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Knowledge base, policies and document vault

### UH-097 — Knowledge items have owner, version, classification and review date.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Knowledge items have owner, version, classification and review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-098 — Knowledge search respects module and document access permissions.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Knowledge search respects module and document access permissions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-099 — Policy acknowledgements capture exact version and time.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy acknowledgements capture exact version and time. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-100 — Private files are stored outside the public web root.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Private files are stored outside the public web root. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-101 — File downloads re-check user role, record scope and classification.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: File downloads re-check user role, record scope and classification. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-102 — Uploaded files have size/type limits and content-signature checks.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Uploaded files have size/type limits and content-signature checks. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-103 — File upload records include SHA-256 checksum and uploader.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: File upload records include SHA-256 checksum and uploader. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-104 — Malware scanning/quarantine runs before a file becomes trusted.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Malware scanning/quarantine runs before a file becomes trusted. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-105 — Confidential documents use expiring access links and audited downloads.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Confidential documents use expiring access links and audited downloads. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-106 — Document version history retains prior versions under a retention policy.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Document version history retains prior versions under a retention policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-107 — Downloaded copies cannot be remotely recalled and are labelled accordingly.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Downloaded copies cannot be remotely recalled and are labelled accordingly. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-108 — Vault keys and storage credentials are separate from application and backup keys.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** knowledge, policies, document_vault, compliance · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Vault keys and storage credentials are separate from application and backup keys. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Helpdesk and confidential grievances

### UH-109 — Helpdesk tickets record requester, owner, priority, status and due date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Helpdesk tickets record requester, owner, priority, status and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-110 — Ticket SLA reminders escalate to the current owner and manager.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Ticket SLA reminders escalate to the current owner and manager. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-111 — Resolution notes explain what was done and when.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Resolution notes explain what was done and when. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-112 — Closed tickets can be reopened with a reason.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Closed tickets can be reopened with a reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-113 — Confidential grievances are isolated from ordinary support tickets.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Confidential grievances are isolated from ordinary support tickets. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-114 — Case owners complete conflict-of-interest checks and can be reassigned.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Case owners complete conflict-of-interest checks and can be reassigned. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-115 — Complainants can track status without seeing restricted internal notes.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Complainants can track status without seeing restricted internal notes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-116 — Appeals have a separate owner and due date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Appeals have a separate owner and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-117 — Anti-retaliation and confidentiality guidance is visible to authorised reviewers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Anti-retaliation and confidentiality guidance is visible to authorised reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-118 — Case access and export events are logged without leaking complaint text.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Case access and export events are logged without leaking complaint text. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-119 — HR complaint access is limited to assigned, impartial roles.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: HR complaint access is limited to assigned, impartial roles. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-120 — External reporting or emergency contact procedures are configured to company policy.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** helpdesk, grievances, hr_cases, incidents · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: External reporting or emergency contact procedures are configured to company policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Contracts, legal approvals and retention

### UH-121 — Agreements record type, counterparty, owner, status and effective dates.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Agreements record type, counterparty, owner, status and effective dates. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-122 — Expiry and renewal reminders are sent before the deadline.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Expiry and renewal reminders are sent before the deadline. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-123 — Legal documents are linked to restricted vault references, not public URLs.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal documents are linked to restricted vault references, not public URLs. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-124 — NDA and contract acknowledgements retain version and signature status.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: NDA and contract acknowledgements retain version and signature status. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-125 — Legal hold prevents scheduled disposal of relevant content.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal hold prevents scheduled disposal of relevant content. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-126 — High-risk contract approvals require distinct approvers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk contract approvals require distinct approvers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-127 — Signature provider integration verifies signer identity and final document hash.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Signature provider integration verifies signer identity and final document hash. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-128 — Contract downloads are permission-gated and audited.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract downloads are permission-gated and audited. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-129 — Retention periods are documented by record class and business purpose.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Retention periods are documented by record class and business purpose. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-130 — Legal requests are reviewed by qualified counsel where required.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal requests are reviewed by qualified counsel where required. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-131 — Contract corrections retain prior values and reason.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract corrections retain prior values and reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-132 — The product never claims legal compliance without jurisdiction-specific review.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** contracts, document_vault, policies, compliance, approvals (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: The product never claims legal compliance without jurisdiction-specific review. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Announcements, leave, meetings and collaboration

### UH-133 — Announcements support audience, publish date and expiry date.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Announcements support audience, publish date and expiry date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-134 — Read receipts are recorded by member and announcement version.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Read receipts are recorded by member and announcement version. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-135 — Corrections link to the original announcement and retain history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Corrections link to the original announcement and retain history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-136 — Leave requests have dates, type, approver and decision reason.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Leave requests have dates, type, approver and decision reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-137 — Leave balances update through an approved ledger, not manual hidden edits.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Leave balances update through an approved ledger, not manual hidden edits. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-138 — Overlapping leave requests are detected before approval.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Overlapping leave requests are detected before approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-139 — Shared calendars expose availability without unnecessary private details.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Shared calendars expose availability without unnecessary private details. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-140 — Meetings store agenda, attendees, minutes and decisions.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Meetings store agenda, attendees, minutes and decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-141 — Action items include owner, due date and current state.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Action items include owner, due date and current state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-142 — Notifications have read state, severity and a relevant record link.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Notifications have read state, severity and a relevant record link. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-143 — Email/push delivery uses a configured provider with retry and delivery status.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Email/push delivery uses a configured provider with retry and delivery status. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-144 — Meeting or comment moderation is auditable and does not hard-delete member history.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** announcements, leave, meetings, decisions, task_submissions · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Meeting or comment moderation is auditable and does not hard-delete member history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Audit trails, incidents and governance

### UH-145 — Sensitive actions capture actor, target, time, outcome and reason.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive actions capture actor, target, time, outcome and reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-146 — Record create/update/archive events have a before/after history.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Record create/update/archive events have a before/after history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-147 — Comment hiding preserves the original text and the moderation reason.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Comment hiding preserves the original text and the moderation reason. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-148 — Security incidents track severity, owner, containment, remediation and closure.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Security incidents track severity, owner, containment, remediation and closure. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-149 — Critical incidents notify the Founder/Super Admin through configured channels.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical incidents notify the Founder/Super Admin through configured channels. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-150 — Audit viewing is restricted by role and domain.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit viewing is restricted by role and domain. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-151 — Permission changes include the previous and new values.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Permission changes include the previous and new values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-152 — Audit storage is append-only for application users and protected from ordinary admins.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit storage is append-only for application users and protected from ordinary admins. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-153 — Remote immutable audit storage is configured for production.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Remote immutable audit storage is configured for production. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-154 — Incident postmortems record root cause and assigned corrective actions.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident postmortems record root cause and assigned corrective actions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-155 — High-risk actions can require two-person approval.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: High-risk actions can require two-person approval. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-156 — Audit exports are scope-limited, reasoned and logged.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** incidents, risks, compliance, audit logs (cross-cutting), permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Audit exports are scope-limited, reasoned and logged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Backups, recovery and continuity

### UH-157 — Backup scope includes database records and private attachments.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup scope includes database records and private attachments. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-158 — Backup archive is encrypted with authenticated encryption.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup archive is encrypted with authenticated encryption. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-159 — Backup encryption key is stored separately from backup files.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup encryption key is stored separately from backup files. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-160 — Backup filename, manifest and timestamps are recorded.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup filename, manifest and timestamps are recorded. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-161 — Session state is excluded from restore to force fresh authentication.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Session state is excluded from restore to force fresh authentication. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-162 — Backup schedule has an explicit owner and failure alert path.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup schedule has an explicit owner and failure alert path. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-163 — An isolated or immutable copy exists outside the production host.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: An isolated or immutable copy exists outside the production host. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-164 — Restore refuses to overwrite a live database by default.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Restore refuses to overwrite a live database by default. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-165 — Restored database passes integrity checks before service startup.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Restored database passes integrity checks before service startup. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-166 — Private file hashes/counts are verified during restore drills.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Private file hashes/counts are verified during restore drills. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-167 — RPO and RTO are documented for each critical service.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: RPO and RTO are documented for each critical service. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-168 — A restore drill is completed and signed off on a recurring schedule.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, sessions_devices, audit logs (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: A restore drill is completed and signed off on a recurring schedule. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Privacy requests and data lifecycle

### UH-169 — Privacy requests cover access, correction, export and deletion review.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Privacy requests cover access, correction, export and deletion review. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-170 — Requester identity and authority are verified before disclosing data.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Requester identity and authority are verified before disclosing data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-171 — Each request has owner, legal basis, due date, status and audit history.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Each request has owner, legal basis, due date, status and audit history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-172 — Correction creates a traceable change instead of silently overwriting history.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Correction creates a traceable change instead of silently overwriting history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-173 — Deletion requests are reviewed against legal holds and retention obligations.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Deletion requests are reviewed against legal holds and retention obligations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-174 — No ordinary route hard-deletes member accounts or member history.
- **Priority:** P0 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: No ordinary route hard-deletes member accounts or member history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-175 — Retention schedules are approved for each record category.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Retention schedules are approved for each record category. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-176 — Expired content is disposed through an approved, logged retention job when lawful.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Expired content is disposed through an approved, logged retention job when lawful. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-177 — Backups age out under a documented retention policy.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Backups age out under a documented retention policy. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-178 — Data-subject exports are scoped to the verified requester.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Data-subject exports are scoped to the verified requester. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-179 — Data minimisation applies to directory and public digital ID fields.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Data minimisation applies to directory and public digital ID fields. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-180 — Applicable Indian privacy obligations are reviewed by qualified counsel before launch.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** data_requests, document_vault, compliance, audit logs (cross-cutting) · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable test environment, execute this scenario: Applicable Indian privacy obligations are reviewed by qualified counsel before launch. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Integrations, vendors and system operations

### UH-181 — Integration register names provider, owner, purpose and data exchanged.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Integration register names provider, owner, purpose and data exchanged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-182 — Integration scopes use least privilege and are documented.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Integration scopes use least privilege and are documented. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-183 — Access tokens are stored in a secret manager and never rendered to users.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Access tokens are stored in a secret manager and never rendered to users. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-184 — Credential rotation dates and owners are tracked.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Credential rotation dates and owners are tracked. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-185 — Sync jobs record last success, last failure and retry state.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Sync jobs record last success, last failure and retry state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-186 — Repeated integration failures create an alert and incident reference.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Repeated integration failures create an alert and incident reference. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-187 — Vendors have risk rating, contract and review dates.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendors have risk rating, contract and review dates. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-188 — Vendor access expires when no longer needed.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendor access expires when no longer needed. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-189 — Schema migrations are versioned and tested before deployment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Schema migrations are versioned and tested before deployment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-190 — Staging environment is separate from production data.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Staging environment is separate from production data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-191 — Releases include health checks and a tested rollback procedure.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Releases include health checks and a tested rollback procedure. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-192 — Cost, rate limits and provider outages are monitored with alert thresholds.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** integrations, vendors, releases, continuity, backup_jobs · **Suggested owner:** Founder / Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Cost, rate limits and provider outages are monitored with alert thresholds. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Exit, handover and ownership transfer

### UH-193 — Exit is a workflow with approver, exit date and completion checklist.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit is a workflow with approver, exit date and completion checklist. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-194 — Active sessions are revoked and future logins blocked on suspension/exit.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Active sessions are revoked and future logins blocked on suspension/exit. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-195 — Project ownership transfers before a project lead exits.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Project ownership transfers before a project lead exits. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-196 — Open tasks are reassigned with the reason and new owner.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Open tasks are reassigned with the reason and new owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-197 — Private files, documents and knowledge articles retain an accountable owner.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Private files, documents and knowledge articles retain an accountable owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-198 — Issued assets and software seats are returned or reassigned.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Issued assets and software seats are returned or reassigned. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-199 — Vendor/service accounts are rotated or revoked on exit.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Vendor/service accounts are rotated or revoked on exit. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-200 — Legal hold and retention checks run before an account is finalised.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Legal hold and retention checks run before an account is finalised. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-201 — Final access checklist is acknowledged by accountable reviewers.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Final access checklist is acknowledged by accountable reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-202 — Employee history remains linked to a stable member ID.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee history remains linked to a stable member ID. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-203 — Exit completion reports identify blocked tasks and unresolved items.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Exit completion reports identify blocked tasks and unresolved items. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-204 — Offboarding requires a second reviewer for privileged accounts.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** offboarding, projects, tasks, assets, document_vault, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Offboarding requires a second reviewer for privileged accounts. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Reports, exports and data quality

### UH-205 — Reports are filtered to the requesting user’s role and scope.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Reports are filtered to the requesting user’s role and scope. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-206 — Exports require a business reason and are logged.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Exports require a business reason and are logged. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-207 — Large exports are rate-limited and visible to security reviewers.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Large exports are rate-limited and visible to security reviewers. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-208 — CSV/JSON outputs encode data safely and avoid spreadsheet formula injection.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: CSV/JSON outputs encode data safely and avoid spreadsheet formula injection. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-209 — Dashboard metrics reconcile with source records.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Dashboard metrics reconcile with source records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-210 — KPI reports include period, formula version and refresh timestamp.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: KPI reports include period, formula version and refresh timestamp. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-211 — Missing data is labelled rather than silently treated as zero.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Missing data is labelled rather than silently treated as zero. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-212 — Data fields use consistent timezones and ISO timestamps.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Data fields use consistent timezones and ISO timestamps. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-213 — Duplicate identifiers and invalid state changes are rejected.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Duplicate identifiers and invalid state changes are rejected. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-214 — Records have a clear owner and an accountable review date.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Records have a clear owner and an accountable review date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-215 — Aged records can be flagged for review without auto-deletion.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Aged records can be flagged for review without auto-deletion. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-216 — Report consumers can trace a metric back to approved source records.
- **Priority:** P2 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** kpis, goals, decisions, data_requests, audited exports (cross-cutting) · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable test environment, execute this scenario: Report consumers can trace a metric back to approved source records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Notifications and SLA automation

### UH-217 — In-app notifications are personal to the intended recipient.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: In-app notifications are personal to the intended recipient. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-218 — Unread counts are consistent with the notification table.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Unread counts are consistent with the notification table. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-219 — Overdue task reminders are idempotent within the configured window.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Overdue task reminders are idempotent within the configured window. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-220 — Contract/vendor/asset renewal warnings are generated before expiry.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Contract/vendor/asset renewal warnings are generated before expiry. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-221 — Inactive-work alerts prompt human review instead of automatic punishment.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Inactive-work alerts prompt human review instead of automatic punishment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-222 — Scheduled jobs record started time, finish time, details and failure state.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Scheduled jobs record started time, finish time, details and failure state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-223 — Job failures create a visible security/operations event.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Job failures create a visible security/operations event. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-224 — Notification text excludes passwords, OTPs and secret tokens.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Notification text excludes passwords, OTPs and secret tokens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-225 — External email delivery retries safely and records provider response.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: External email delivery retries safely and records provider response. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-226 — Critical notification routing has a documented backup route.
- **Priority:** P1 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical notification routing has a documented backup route. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-227 — SLA escalation policies are configurable by ticket category and severity.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: SLA escalation policies are configurable by ticket category and severity. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-228 — Operators can trigger a manual reminder run and see its job history.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** announcements, tasks, helpdesk, leave, contracts, notifications (cross-cutting) · **Suggested owner:** Admin / HR / Project Lead
- **Acceptance check:** In a disposable test environment, execute this scenario: Operators can trigger a manual reminder run and see its job history. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## UI, mobile, accessibility and usability

### UH-229 — Portal navigation only shows modules allowed to the signed-in role.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Portal navigation only shows modules allowed to the signed-in role. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-230 — The 40-module catalogue can be searched by module name and description.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: The 40-module catalogue can be searched by module name and description. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-231 — Layout supports narrow mobile screens without losing key actions.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Layout supports narrow mobile screens without losing key actions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-232 — Forms have visible labels and clear validation errors.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Forms have visible labels and clear validation errors. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-233 — Dialogs can be closed without saving and cannot silently discard unsaved data.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Dialogs can be closed without saving and cannot silently discard unsaved data. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-234 — Status labels use text, not colour alone.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Status labels use text, not colour alone. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-235 — Long records and audit values wrap safely without running off-screen.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Long records and audit values wrap safely without running off-screen. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-236 — Tables are horizontally scrollable on small screens.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Tables are horizontally scrollable on small screens. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-237 — Buttons have clear action labels and visible focus states.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Buttons have clear action labels and visible focus states. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-238 — Loading, empty, error and success states are visible.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Loading, empty, error and success states are visible. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-239 — The interface avoids displaying secrets in profile cards or error traces.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: The interface avoids displaying secrets in profile cards or error traces. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-240 — Screen-reader and keyboard navigation tests pass before release.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** portal UI (cross-cutting), all module workspaces · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable test environment, execute this scenario: Screen-reader and keyboard navigation tests pass before release. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## API, application security and secure coding

### UH-241 — Unknown API routes return safe errors without stack traces.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Unknown API routes return safe errors without stack traces. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-242 — Input lengths, content types, enum values and dates are validated server-side.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Input lengths, content types, enum values and dates are validated server-side. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-243 — Parameterised database calls are used for user-controlled values.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Parameterised database calls are used for user-controlled values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-244 — Security headers and a restrictive content security policy are enabled.
- **Priority:** P1 · **Source status:** Implemented baseline — live test required · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Security headers and a restrictive content security policy are enabled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-245 — Private uploads never resolve through a static public route.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Private uploads never resolve through a static public route. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-246 — Downloads use attachment disposition and nosniff protection.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Downloads use attachment disposition and nosniff protection. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-247 — Rate limits cover login and sensitive high-cost operations.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Rate limits cover login and sensitive high-cost operations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-248 — CSRF/origin protections match the selected session-cookie deployment.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: CSRF/origin protections match the selected session-cookie deployment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-249 — Record IDs cannot bypass module access checks (IDOR test).
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Record IDs cannot bypass module access checks (IDOR test). Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-250 — Logs redact secrets and avoid storing submitted passwords.
- **Priority:** P1 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Logs redact secrets and avoid storing submitted passwords. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-251 — Dependencies are reviewed for known vulnerabilities before production.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Dependencies are reviewed for known vulnerabilities before production. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-252 — Production secrets are injected through a secret manager or protected environment.
- **Priority:** P1 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** auth API, RBAC, private_files, audit logs (cross-cutting), all API routes · **Suggested owner:** Developer / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Production secrets are injected through a secret manager or protected environment. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Testing, quality gates and release readiness

### UH-253 — Unit tests cover module definitions, required fields and allowed statuses.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Unit tests cover module definitions, required fields and allowed statuses. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-254 — API tests cover happy path and invalid input for every module.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: API tests cover happy path and invalid input for every module. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-255 — Role tests verify allowed and denied access for every role/module pair.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Role tests verify allowed and denied access for every role/module pair. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-256 — IDOR tests attempt to access another member’s record by changing record ID.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: IDOR tests attempt to access another member’s record by changing record ID. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-257 — Session tests verify login rotation, logout and suspension.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Session tests verify login rotation, logout and suspension. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-258 — File tests cover size limits, signature mismatch and access denial.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: File tests cover size limits, signature mismatch and access denial. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-259 — Backup/restore tests verify encryption failure and integrity failure paths.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Backup/restore tests verify encryption failure and integrity failure paths. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-260 — Approval tests verify self-approval and same-person second approval are rejected.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Approval tests verify self-approval and same-person second approval are rejected. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-261 — Database migrations run on a clean install and an older database snapshot.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Database migrations run on a clean install and an older database snapshot. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-262 — Build has a reproducible lockfile and CI checks on each change.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Build has a reproducible lockfile and CI checks on each change. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-263 — Critical/high security findings are resolved before launch.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Critical/high security findings are resolved before launch. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-264 — End-to-end test report records test date, version, result and tester.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, all module workflows · **Suggested owner:** Developer / QA / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: End-to-end test report records test date, version, result and tester. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Production deployment, monitoring and support

### UH-265 — Production runs behind HTTPS with secure cookies enabled.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Production runs behind HTTPS with secure cookies enabled. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-266 — Database and uploads use protected persistent storage with least-privilege OS access.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Database and uploads use protected persistent storage with least-privilege OS access. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-267 — Database WAL/SHM and backup handling are included in operational procedures.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Database WAL/SHM and backup handling are included in operational procedures. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-268 — Health endpoint reports status without exposing secrets or sensitive configuration.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Health endpoint reports status without exposing secrets or sensitive configuration. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-269 — Uptime, latency, error rate and disk capacity are monitored.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Uptime, latency, error rate and disk capacity are monitored. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-270 — Logs have retention, access control, redaction and alerting.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Logs have retention, access control, redaction and alerting. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-271 — Container runs as a non-root user with a reviewed image.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Container runs as a non-root user with a reviewed image. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-272 — Deployment supports environment-specific configuration and secret rotation.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Deployment supports environment-specific configuration and secret rotation. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-273 — Rollback procedure is tested with a recent backup.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Rollback procedure is tested with a recent backup. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-274 — Incident-response contacts and escalation rota are documented.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident-response contacts and escalation rota are documented. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-275 — Public deployment waits until unresolved security gates are signed off.
- **Priority:** P0 · **Source status:** Baseline code — live test required · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Public deployment waits until unresolved security gates are signed off. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-276 — Production readiness owner signs off every blocker with attached evidence.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** releases, continuity, integrations, vendors, operational jobs · **Suggested owner:** Technical Owner / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Production readiness owner signs off every blocker with attached evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Company governance, fairness and continuous improvement

### UH-277 — Every module has an accountable owner and an explicit intended use.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Every module has an accountable owner and an explicit intended use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-278 — Role matrix is version-controlled and reviewed after team changes.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Role matrix is version-controlled and reviewed after team changes. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-279 — No shared Founder or Super Admin accounts are used.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: No shared Founder or Super Admin accounts are used. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-280 — Access grants are time-bound where practical and removed when expired.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Access grants are time-bound where practical and removed when expired. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-281 — Self-approval and conflict-of-interest rules are applied consistently.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Self-approval and conflict-of-interest rules are applied consistently. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-282 — Employee-facing explanations describe work-status and KPI calculations.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Employee-facing explanations describe work-status and KPI calculations. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-283 — Employees have a way to provide context and appeal decisions.
- **Priority:** P0 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Employees have a way to provide context and appeal decisions. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-284 — Sensitive HR and grievance content is restricted to need-to-know roles.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive HR and grievance content is restricted to need-to-know roles. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-285 — Policy changes retain version, effective date and acknowledgement state.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Policy changes retain version, effective date and acknowledgement state. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-286 — Release feedback is captured with prioritisation and owner.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: Release feedback is captured with prioritisation and owner. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-287 — A quarterly review updates checklist status and evidence links.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: A quarterly review updates checklist status and evidence links. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-288 — No feature is marked complete until behaviour, permission tests and operational ownership are evidenced.
- **Priority:** P0 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** goals, performance_reviews, compliance, decisions, grievances · **Suggested owner:** Founder / HR / Security Reviewer
- **Acceptance check:** In a disposable test environment, execute this scenario: No feature is marked complete until behaviour, permission tests and operational ownership are evidenced. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Analytics, incident drills and security operations

### UH-289 — Security events can be triaged by severity, owner and due date.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Security events can be triaged by severity, owner and due date. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-290 — Incident response exercises test detection, escalation, containment and recovery.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Incident response exercises test detection, escalation, containment and recovery. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-291 — Sensitive exports and unusually high record access generate reviewable events.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Sensitive exports and unusually high record access generate reviewable events. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-292 — Authentication logs exclude password contents, session IDs and OTP values.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Authentication logs exclude password contents, session IDs and OTP values. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-293 — Privileged account recovery has a documented break-glass process.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Privileged account recovery has a documented break-glass process. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-294 — Break-glass use alerts the Founder and is reviewed after use.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Break-glass use alerts the Founder and is reviewed after use. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-295 — Backups and restore credentials are tested independently from day-to-day logins.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Backups and restore credentials are tested independently from day-to-day logins. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-296 — Operational job runtimes and failures are measurable over time.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Operational job runtimes and failures are measurable over time. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-297 — Security controls have named owners, review dates and exception records.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Security controls have named owners, review dates and exception records. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-298 — Post-incident corrective actions have owners and closure evidence.
- **Priority:** P2 · **Source status:** External setup / production gate · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Post-incident corrective actions have owners and closure evidence. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-299 — Data retention and access reviews are recorded on a calendar.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Data retention and access reviews are recorded on a calendar. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

### UH-300 — Security dashboards disclose only data appropriate to the viewer role.
- **Priority:** P2 · **Source status:** Partial workflow / specialist implementation · **Validation:** Not run
- **Related modules:** incidents, compliance, backup_jobs, sessions_devices, permissions_access · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable test environment, execute this scenario: Security dashboards disclose only data appropriate to the viewer role. Verify the result in the UI and server/API response, reload and confirm it persists, then attach timestamped evidence. For permission/security controls, also attempt the same action as an unauthorised role and record the expected denial.
- **Evidence:** 

## Department structures & cost centres

### UH-301 — Department identifiers must be unique and linked to a valid parent department, when applicable.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Department identifiers must be unique and linked to a valid parent department, when applicable. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-302 — Department-head changes must capture prior owner, new owner, reason, approver and effective date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Department-head changes must capture prior owner, new owner, reason, approver and effective date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-303 — Cost-centre references must be checked against the controlled finance register before approval.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Cost-centre references must be checked against the controlled finance register before approval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-304 — Headcount targets and actual staffing must use the same time period and status definition.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Headcount targets and actual staffing must use the same time period and status definition. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-305 — Closed departments must block new assignments while preserving historical reports.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Closed departments must block new assignments while preserving historical reports. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-306 — Org-chart views must show only department details permitted to the viewer role.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Org-chart views must show only department details permitted to the viewer role. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-307 — Circular parent-department relationships must be rejected before saving.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Circular parent-department relationships must be rejected before saving. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-308 — A department restructure must produce a reviewable impact list of members, projects, budgets and service owners.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** departments, org_directory, budget_planning · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A department restructure must produce a reviewable impact list of members, projects, budgets and service owners. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Capacity forecasting & workload balance

### UH-309 — Capacity plans must define a period, team, available hours and the source of availability data.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Capacity plans must define a period, team, available hours and the source of availability data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-310 — Planned load above the configured threshold must create an at-risk signal for the accountable lead.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Planned load above the configured threshold must create an at-risk signal for the accountable lead. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-311 — Approved leave and non-working days must be excluded from available capacity calculations.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approved leave and non-working days must be excluded from available capacity calculations. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-312 — Forecasts must distinguish planned hours, recorded hours and completed outcomes rather than equating time with productivity.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Forecasts must distinguish planned hours, recorded hours and completed outcomes rather than equating time with productivity. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-313 — Workload reallocations must record the old assignment, new assignment, rationale and approver.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Workload reallocations must record the old assignment, new assignment, rationale and approver. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-314 — Individual workload data must not be visible outside the user’s authorised team and reporting chain.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Individual workload data must not be visible outside the user’s authorised team and reporting chain. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-315 — Capacity summaries must indicate missing worklogs or stale data instead of treating blanks as zero.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Capacity summaries must indicate missing worklogs or stale data instead of treating blanks as zero. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-316 — The model must be tested against overloaded, underloaded, part-time and on-leave scenarios.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** capacity_planning, tasks, time_tracking, leave, projects · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The model must be tested against overloaded, underloaded, part-time and on-leave scenarios. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Shift coverage & handover

### UH-317 — Every shift must have a valid date, start/end time, coverage role and accountable owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every shift must have a valid date, start/end time, coverage role and accountable owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-318 — Shift end times crossing midnight must be calculated consistently in the configured company timezone.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Shift end times crossing midnight must be calculated consistently in the configured company timezone. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-319 — Overlapping shifts for the same member must be detected before a roster is approved.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Overlapping shifts for the same member must be detected before a roster is approved. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-320 — Shift swaps must require approval from a different authorised user and preserve both roster versions.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Shift swaps must require approval from a different authorised user and preserve both roster versions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-321 — Coverage gaps for critical roles must trigger an alert to the schedule owner before the shift starts.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Coverage gaps for critical roles must trigger an alert to the schedule owner before the shift starts. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-322 — Handover notes must link to the next responsible member without exposing unrelated HR information.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Handover notes must link to the next responsible member without exposing unrelated HR information. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-323 — Approved leave and public holidays must be considered by roster validation.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approved leave and public holidays must be considered by roster validation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-324 — Roster changes must retain who changed them, what changed, when and why.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** shift_planning, attendance, leave, org_directory · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Roster changes must retain who changed them, what changed, when and why. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## OKRs & quarterly cycles

### UH-325 — Each objective must link to one accountable owner, a cycle, a baseline and a measurable outcome.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each objective must link to one accountable owner, a cycle, a baseline and a measurable outcome. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-326 — Key results must store target, actual, direction and measurement date with an explicit calculation method.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Key results must store target, actual, direction and measurement date with an explicit calculation method. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-327 — Confidence check-ins must be timestamped and trendable without silently overwriting previous check-ins.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Confidence check-ins must be timestamped and trendable without silently overwriting previous check-ins. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-328 — A changed objective or target must retain the previous value, reason and approver.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A changed objective or target must retain the previous value, reason and approver. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-329 — Quarterly progress must roll up only from valid child results and disclose missing measurements.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Quarterly progress must roll up only from valid child results and disclose missing measurements. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-330 — OKR visibility must follow department/project access rules and protect confidential individual review notes.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: OKR visibility must follow department/project access rules and protect confidential individual review notes. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-331 — Cycle close must preserve the final snapshot and any uncompleted follow-up actions.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Cycle close must preserve the final snapshot and any uncompleted follow-up actions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-332 — Tests must include improving, declining, missing and out-of-range key-result values.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** okr_cycles, goals, kpis, decisions · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Tests must include improving, declining, missing and out-of-range key-result values. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Anonymous team surveys & pulse

### UH-333 — Survey configuration must define purpose, audience, open/close dates and data classification before publishing.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Survey configuration must define purpose, audience, open/close dates and data classification before publishing. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-334 — Minimum group-size rules must suppress results that could identify an individual in a small team.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Minimum group-size rules must suppress results that could identify an individual in a small team. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-335 — Raw survey responses must be separated from aggregate views and restricted to specifically authorised reviewers.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Raw survey responses must be separated from aggregate views and restricted to specifically authorised reviewers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-336 — Survey exports must remove direct identifiers when the published promise is anonymity.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Survey exports must remove direct identifiers when the published promise is anonymity. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-337 — A response-rate figure must distinguish invited, submitted and excluded responses.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A response-rate figure must distinguish invited, submitted and excluded responses. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-338 — Follow-up themes must be aggregated and must not quote identifying free text without review.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Follow-up themes must be aggregated and must not quote identifying free text without review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-339 — Survey participation must not automatically change employee status, KPI or disciplinary decisions.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Survey participation must not automatically change employee status, KPI or disciplinary decisions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-340 — Retention and deletion schedules must cover raw responses, aggregated results and follow-up action records.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** surveys, grievances, policies, data_requests · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Retention and deletion schedules must cover raw responses, aggregated results and follow-up action records. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Recognition & contribution evidence

### UH-341 — Recognition entries must describe an observable contribution or outcome and link optional supporting evidence.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Recognition entries must describe an observable contribution or outcome and link optional supporting evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-342 — Recognition visibility must support private, team and company audiences with server-side access checks.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Recognition visibility must support private, team and company audiences with server-side access checks. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-343 — The recipient must not approve a recognition entry they created for themselves.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The recipient must not approve a recognition entry they created for themselves. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-344 — Public recognition must avoid publishing sensitive member data, client data or confidential project details.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Public recognition must avoid publishing sensitive member data, client data or confidential project details. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-345 — Duplicate recognition submissions for the same event must be detectable without blocking legitimate multiple contributions.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate recognition submissions for the same event must be detectable without blocking legitimate multiple contributions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-346 — Recognition history must remain separate from formal KPI calculations unless a documented policy explicitly links them.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Recognition history must remain separate from formal KPI calculations unless a documented policy explicitly links them. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-347 — Corrections must append a correction record rather than erase the original attribution.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Corrections must append a correction record rather than erase the original attribution. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-348 — Members must be able to flag inaccurate or inappropriate recognition for review.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** recognition, tasks, task_submissions, performance_reviews · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Members must be able to flag inaccurate or inappropriate recognition for review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Communications & brand templates

### UH-349 — Each template must have a version, owner, approved audience and last-review date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each template must have a version, owner, approved audience and last-review date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-350 — Only approved templates may be selected for official or policy-critical announcements.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Only approved templates may be selected for official or policy-critical announcements. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-351 — Retired templates must remain read-only for audit but cannot be used for new sends.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Retired templates must remain read-only for audit but cannot be used for new sends. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-352 — Template placeholders must be validated so missing fields do not produce misleading communications.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Template placeholders must be validated so missing fields do not produce misleading communications. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-353 — Content changes must record before/after versions and approval decisions.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Content changes must record before/after versions and approval decisions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-354 — Sensitive announcements must use role-based recipients and a documented publication window.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive announcements must use role-based recipients and a documented publication window. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-355 — Rendered previews must be checked on desktop and narrow mobile widths before release.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Rendered previews must be checked on desktop and narrow mobile widths before release. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-356 — Delivery status must distinguish drafted, scheduled, sent, partially delivered and failed.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** communication_templates, announcements, policies · **Suggested owner:** Admin / Communications Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Delivery status must distinguish drafted, scheduled, sent, partially delivered and failed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Internal service catalogue & ownership

### UH-357 — Each service must have a named accountable owner, supported audience and intake route.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each service must have a named accountable owner, supported audience and intake route. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-358 — Service dependencies and data classification must be recorded before the service is marked active.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Service dependencies and data classification must be recorded before the service is marked active. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-359 — A service without a current owner must be flagged for reassignment rather than silently considered healthy.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A service without a current owner must be flagged for reassignment rather than silently considered healthy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-360 — Service catalogue links must route to an authorised intake path, not a public or unprotected record.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Service catalogue links must route to an authorised intake path, not a public or unprotected record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-361 — Service changes must preserve previous owner and support-policy version.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Service changes must preserve previous owner and support-policy version. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-362 — Services marked critical must have a documented escalation contact and recovery reference.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Services marked critical must have a documented escalation contact and recovery reference. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-363 — Periodic service reviews must capture availability, open risks and follow-up actions.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Periodic service reviews must capture availability, open risks and follow-up actions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-364 — Access to client-facing or restricted service metadata must be limited to need-to-know roles.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** service_catalog, helpdesk, sla_policies, vendors · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Access to client-facing or restricted service metadata must be limited to need-to-know roles. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## SLA & escalation matrix

### UH-365 — SLA policies must define response and resolution targets, working calendar and priority mapping.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: SLA policies must define response and resolution targets, working calendar and priority mapping. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-366 — Paused SLA time must use an explicit policy reason and be audited.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Paused SLA time must use an explicit policy reason and be audited. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-367 — Escalation timers must deduplicate notifications and avoid repeating alerts indefinitely.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Escalation timers must deduplicate notifications and avoid repeating alerts indefinitely. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-368 — Severity upgrades must recalculate relevant deadlines and alert the current accountable owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Severity upgrades must recalculate relevant deadlines and alert the current accountable owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-369 — Escalation routing must include a fallback when the primary owner is exited, suspended or unavailable.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Escalation routing must include a fallback when the primary owner is exited, suspended or unavailable. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-370 — SLA reports must separate first response, resolution time and reopened-ticket time.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: SLA reports must separate first response, resolution time and reopened-ticket time. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-371 — Policy changes must apply prospectively unless a controlled migration explicitly says otherwise.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Policy changes must apply prospectively unless a controlled migration explicitly says otherwise. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-372 — Tests must cover weekends, holidays, daylight/timezone differences and overdue edge cases.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sla_policies, helpdesk, notification_rules, incidents · **Suggested owner:** Operations / Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Tests must cover weekends, holidays, daylight/timezone differences and overdue edge cases. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Purchase-order governance

### UH-373 — Purchase requests must reference an active vendor, cost centre, amount and business justification.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Purchase requests must reference an active vendor, cost centre, amount and business justification. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-374 — Approval thresholds must be enforced on the server and cannot be bypassed by hiding UI controls.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approval thresholds must be enforced on the server and cannot be bypassed by hiding UI controls. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-375 — Requesters cannot approve their own purchase orders or act as both required approvers.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Requesters cannot approve their own purchase orders or act as both required approvers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-376 — Issued purchase orders must retain the approved amount and vendor snapshot used at approval time.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Issued purchase orders must retain the approved amount and vendor snapshot used at approval time. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-377 — Changes to amount, currency, vendor or delivery date after approval must trigger a new review.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Changes to amount, currency, vendor or delivery date after approval must trigger a new review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-378 — Receiving must reconcile ordered, received, damaged and outstanding quantities.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Receiving must reconcile ordered, received, damaged and outstanding quantities. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-379 — Duplicate vendor invoice or purchase-order references must be flagged for finance review.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate vendor invoice or purchase-order references must be flagged for finance review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-380 — Exports and attachments must be access-checked and audited with the reason for retrieval.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** purchase_orders, vendors, finance, budget_planning · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exports and attachments must be access-checked and audited with the reason for retrieval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Expense claims & reimbursement

### UH-381 — Claims must validate claimant, expense date, category, amount and required receipt reference.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Claims must validate claimant, expense date, category, amount and required receipt reference. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-382 — Policy exceptions must require a named approver and rationale separate from the claimant.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Policy exceptions must require a named approver and rationale separate from the claimant. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-383 — A claimant must not approve their own reimbursement or provide the second approval.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A claimant must not approve their own reimbursement or provide the second approval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-384 — Approved amount, submitted amount and reimbursed amount must be separately recorded.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approved amount, submitted amount and reimbursed amount must be separately recorded. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-385 — Rejected claims must include a reason and a route for correction or appeal.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Rejected claims must include a reason and a route for correction or appeal. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-386 — Receipt files must be held privately and downloaded only by authorised claim reviewers.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Receipt files must be held privately and downloaded only by authorised claim reviewers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-387 — Duplicate claims must be flagged using configurable date, amount and receipt-reference checks.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate claims must be flagged using configurable date, amount and receipt-reference checks. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-388 — Reimbursement exports must exclude unrelated personal data and must log the requesting actor.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** expense_claims, document_vault, finance, approvals · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reimbursement exports must exclude unrelated personal data and must log the requesting actor. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Budget & forecasting

### UH-389 — Every budget must specify department, period, currency, owner and approval state.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every budget must specify department, period, currency, owner and approval state. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-390 — Forecast-to-actual variance must be calculated from persisted values with the formula version displayed.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Forecast-to-actual variance must be calculated from persisted values with the formula version displayed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-391 — A locked budget must not be overwritten; an amendment must create a new version and approval record.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A locked budget must not be overwritten; an amendment must create a new version and approval record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-392 — Cross-department reallocations must capture both sending and receiving cost centres.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Cross-department reallocations must capture both sending and receiving cost centres. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-393 — Budgets must not be visible to roles without finance permission even if a record ID is guessed.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Budgets must not be visible to roles without finance permission even if a record ID is guessed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-394 — An unapproved forecast must never be labelled as approved company spend.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: An unapproved forecast must never be labelled as approved company spend. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-395 — Forecast exports must include report timestamp, period and completeness warnings.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Forecast exports must include report timestamp, period and completeness warnings. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-396 — Quarter-end review must preserve the signed-off snapshot and unresolved variances.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** budget_planning, finance, kpis, departments · **Suggested owner:** Founder / Finance Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Quarter-end review must preserve the signed-off snapshot and unresolved variances. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Client & partner data boundaries

### UH-397 — Every account must have a business owner, relationship state and approved data scope.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every account must have a business owner, relationship state and approved data scope. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-398 — Client contact details must be visible only to roles with a business need.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Client contact details must be visible only to roles with a business need. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-399 — Documents attached to an account must inherit the client and document classification rules.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Documents attached to an account must inherit the client and document classification rules. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-400 — Account transfer or closure must identify open contracts, active integrations, tasks and data-retention obligations.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Account transfer or closure must identify open contracts, active integrations, tasks and data-retention obligations. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-401 — Exports containing client data must require a reason and produce an audit event.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exports containing client data must require a reason and produce an audit event. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-402 — Client status changes must retain the previous status, reason, approver and date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Client status changes must retain the previous status, reason, approver and date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-403 — Test users must not access another client’s records by changing a URL, module key or record ID.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Test users must not access another client’s records by changing a URL, module key or record ID. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-404 — Closure reports must identify which data is retained, returned, anonymised or queued for legal review.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** client_accounts, contracts, document_vault, data_requests · **Suggested owner:** Founder / Account Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Closure reports must identify which data is retained, returned, anonymised or queued for legal review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Customer feedback triage

### UH-405 — Feedback must capture its source, product area, impact, response owner and review due date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Feedback must capture its source, product area, impact, response owner and review due date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-406 — Duplicate feedback must be linkable to a canonical item without erasing original submission history.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate feedback must be linkable to a canonical item without erasing original submission history. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-407 — Feedback marked critical must notify the assigned owner and an appropriate escalation role.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Feedback marked critical must notify the assigned owner and an appropriate escalation role. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-408 — Personal data must be removed or restricted before feedback is shared broadly with product teams.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Personal data must be removed or restricted before feedback is shared broadly with product teams. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-409 — Response status must separate received, triaged, planned, in progress and resolved.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Response status must separate received, triaged, planned, in progress and resolved. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-410 — A feedback-to-roadmap link must reference an existing visible project or task record.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A feedback-to-roadmap link must reference an existing visible project or task record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-411 — A resolution must capture the action taken or why no action was selected.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A resolution must capture the action taken or why no action was selected. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-412 — Trend reports must state sample period and must not imply representativeness from an incomplete sample.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** customer_feedback, helpdesk, projects, goals · **Suggested owner:** Product Lead / Support Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Trend reports must state sample period and must not imply representativeness from an incomplete sample. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Sprint planning & capacity

### UH-413 — Sprint records must link to a live project and define start/end date and sprint goal.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sprint records must link to a live project and define start/end date and sprint goal. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-414 — Sprint capacity must account for approved leave, available time and support rotation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sprint capacity must account for approved leave, available time and support rotation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-415 — Only eligible project tasks may be committed to a sprint.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Only eligible project tasks may be committed to a sprint. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-416 — Committed points/hours must be snapshot at sprint start so later edits are traceable.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Committed points/hours must be snapshot at sprint start so later edits are traceable. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-417 — Carryover tasks must retain their original sprint history and link to the next sprint.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Carryover tasks must retain their original sprint history and link to the next sprint. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-418 — Sprint closure must calculate completed, carried and removed scope separately.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sprint closure must calculate completed, carried and removed scope separately. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-419 — Retrospective actions must have an owner, due date and status.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Retrospective actions must have an owner, due date and status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-420 — Sprint dashboards must restrict tasks and estimates to the requester’s assigned project.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sprint_planning, tasks, capacity_planning, projects · **Suggested owner:** Project Lead / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sprint dashboards must restrict tasks and estimates to the requester’s assigned project. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## QA test-case management

### UH-421 — Each test case must include preconditions, steps, expected outcome and a stable identifier.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each test case must include preconditions, steps, expected outcome and a stable identifier. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-422 — Test executions must record tester, environment, run timestamp, actual outcome and evidence reference.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Test executions must record tester, environment, run timestamp, actual outcome and evidence reference. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-423 — Production test data must be synthetic or approved and must not expose real member secrets.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Production test data must be synthetic or approved and must not expose real member secrets. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-424 — A failed critical test must block release approval unless a documented exception is approved.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A failed critical test must block release approval unless a documented exception is approved. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-425 — Test-case version changes must preserve the prior expected result for historical runs.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Test-case version changes must preserve the prior expected result for historical runs. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-426 — Regression suites must be linkable to resolved defects and the release that included the fix.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Regression suites must be linkable to resolved defects and the release that included the fix. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-427 — Test reports must distinguish not-run, blocked, passed, failed and approved waiver results.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Test reports must distinguish not-run, blocked, passed, failed and approved waiver results. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-428 — Test evidence downloads must be restricted to the project/release roles allowed to see them.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** qa_test_cases, releases, bug_tracker, code_reviews · **Suggested owner:** QA / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Test evidence downloads must be restricted to the project/release roles allowed to see them. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Defect triage & regression

### UH-429 — Every defect must have severity, reproducible steps, expected/actual result and an owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every defect must have severity, reproducible steps, expected/actual result and an owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-430 — Severity changes must include a rationale and notification to the current owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Severity changes must include a rationale and notification to the current owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-431 — A defect cannot be marked verified without a linked retest or approved exception.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A defect cannot be marked verified without a linked retest or approved exception. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-432 — Reopened defects must retain the prior resolution and failed regression evidence.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reopened defects must retain the prior resolution and failed regression evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-433 — Blocker/critical defects must be considered in release gating and risk reports.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Blocker/critical defects must be considered in release gating and risk reports. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-434 — Duplicate defects must link to a canonical record and preserve the original reporter’s context.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate defects must link to a canonical record and preserve the original reporter’s context. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-435 — Root-cause and prevention actions must be tracked for recurring high-impact defects.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Root-cause and prevention actions must be tracked for recurring high-impact defects. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-436 — Defect dashboards must count each canonical issue once and disclose filters and time period.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** bug_tracker, qa_test_cases, releases, projects · **Suggested owner:** Engineering Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Defect dashboards must count each canonical issue once and disclose filters and time period. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Code review & change approval

### UH-437 — Code-review records must include change reference, author, reviewer and automated check status.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Code-review records must include change reference, author, reviewer and automated check status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-438 — Authors cannot provide their own approval for protected changes.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Authors cannot provide their own approval for protected changes. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-439 — Security-sensitive changes must require a reviewer with the required security permission.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Security-sensitive changes must require a reviewer with the required security permission. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-440 — A failed required check must prevent approval unless an explicit audited exception is granted.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A failed required check must prevent approval unless an explicit audited exception is granted. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-441 — Review decisions and requested changes must remain visible in the change history.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Review decisions and requested changes must remain visible in the change history. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-442 — Merge references must point to a valid repository/change identifier without storing access tokens.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Merge references must point to a valid repository/change identifier without storing access tokens. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-443 — Production configuration or permission changes must be linked to a release/change request.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Production configuration or permission changes must be linked to a release/change request. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-444 — Review completion must be verified by integration or test evidence, not status labels alone.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** code_reviews, releases, api_registry, incidents · **Suggested owner:** Engineering / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Review completion must be verified by integration or test evidence, not status labels alone. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Release calendar & freeze windows

### UH-445 — Releases must define a version, owner, change window, readiness gate and rollback state.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Releases must define a version, owner, change window, readiness gate and rollback state. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-446 — Overlapping critical change windows must be flagged for coordination.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Overlapping critical change windows must be flagged for coordination. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-447 — A release cannot be labelled ready if mandatory tests or approvals are missing.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A release cannot be labelled ready if mandatory tests or approvals are missing. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-448 — Freeze windows must identify the approving role and the exception process.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Freeze windows must identify the approving role and the exception process. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-449 — Stakeholder announcements must reference the actual release record and scheduled time.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Stakeholder announcements must reference the actual release record and scheduled time. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-450 — Release rescheduling must notify affected owners and retain original and revised dates.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Release rescheduling must notify affected owners and retain original and revised dates. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-451 — Rollback drills must capture test environment, result, duration and evidence.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Rollback drills must capture test environment, result, duration and evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-452 — Post-release review must record incidents, metrics and unresolved follow-up actions.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** release_calendar, releases, announcements, continuity · **Suggested owner:** Release Manager
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Post-release review must record incidents, metrics and unresolved follow-up actions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## API inventory & endpoint ownership

### UH-453 — Every endpoint family must have an accountable service owner and authentication classification.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every endpoint family must have an accountable service owner and authentication classification. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-454 — API data classification must specify whether responses may contain personal or restricted records.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: API data classification must specify whether responses may contain personal or restricted records. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-455 — New sensitive endpoints must link to a reviewed authorization and input-validation test.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: New sensitive endpoints must link to a reviewed authorization and input-validation test. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-456 — Deprecated endpoints must have a removal deadline and documented consumers.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Deprecated endpoints must have a removal deadline and documented consumers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-457 — Registry changes must record who added or changed endpoint metadata and why.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Registry changes must record who added or changed endpoint metadata and why. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-458 — Public endpoints must have an explicit justification and rate-limit/abuse assessment.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Public endpoints must have an explicit justification and rate-limit/abuse assessment. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-459 — Service tokens must be referenced by vault path only; token values must never be entered in this register.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Service tokens must be referenced by vault path only; token values must never be entered in this register. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-460 — Periodic endpoint review must reconcile the inventory against the actual route catalogue.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** api_registry, permissions_access, releases, compliance · **Suggested owner:** Security Reviewer / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Periodic endpoint review must reconcile the inventory against the actual route catalogue. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Secret rotation metadata & ownership

### UH-461 — The register must store only a non-secret vault reference and metadata, never the credential or private key value.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The register must store only a non-secret vault reference and metadata, never the credential or private key value. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-462 — Each secret reference must identify an accountable owner, dependent system and next rotation date.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each secret reference must identify an accountable owner, dependent system and next rotation date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-463 — Overdue rotations must create deduplicated alerts without revealing secret material in notification text.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Overdue rotations must create deduplicated alerts without revealing secret material in notification text. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-464 — Credential replacement must be followed by a controlled verification and old credential revocation record.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Credential replacement must be followed by a controlled verification and old credential revocation record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-465 — Access to vault paths must be governed by the external vault’s ACL, not by this metadata table alone.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Access to vault paths must be governed by the external vault’s ACL, not by this metadata table alone. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-466 — Exports and audit logs must redact credential values and sensitive provider responses.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exports and audit logs must redact credential values and sensitive provider responses. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-467 — Emergency rotation must record trigger, approvals, service impact and post-rotation verification.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Emergency rotation must record trigger, approvals, service impact and post-rotation verification. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-468 — Key loss/recovery procedures must be documented separately and tested without storing recovery keys beside backups.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** secret_rotation_register, integrations, permissions_access · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Key loss/recovery procedures must be documented separately and tested without storing recovery keys beside backups. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Data retention schedule & disposal

### UH-469 — Every data class must specify purpose, lawful basis review, retention trigger and owner.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every data class must specify purpose, lawful basis review, retention trigger and owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-470 — Retention countdown must distinguish record creation, relationship end and legal-hold release events.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Retention countdown must distinguish record creation, relationship end and legal-hold release events. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-471 — A disposal batch must preview counts and sample references before execution.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A disposal batch must preview counts and sample references before execution. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-472 — Legal holds must block disposal for covered records and associated backup-retention workflows as policy requires.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Legal holds must block disposal for covered records and associated backup-retention workflows as policy requires. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-473 — Disposal must record method, scope, operator, timestamp, verification and exceptions.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Disposal must record method, scope, operator, timestamp, verification and exceptions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-474 — Records needed for audit or legal obligations must not be silently destroyed through ordinary UI routes.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Records needed for audit or legal obligations must not be silently destroyed through ordinary UI routes. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-475 — Backup expiry must be coordinated with approved retention rules and restore requirements.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Backup expiry must be coordinated with approved retention rules and restore requirements. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-476 — Periodic review must confirm the schedule still matches the company’s actual data use and applicable law.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** data_retention, data_requests, legal_holds, compliance · **Suggested owner:** Privacy Owner / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Periodic review must confirm the schedule still matches the company’s actual data use and applicable law. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Legal hold register & custodians

### UH-477 — A hold must include an approved matter reference, scope, issuing authority and accountable owner.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A hold must include an approved matter reference, scope, issuing authority and accountable owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-478 — Custodian lists must use stable member IDs and change history.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Custodian lists must use stable member IDs and change history. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-479 — Activating a hold must generate a preservation checklist for records, attachments and relevant exports.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Activating a hold must generate a preservation checklist for records, attachments and relevant exports. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-480 — Release requires documented authority and a second reviewer where company policy mandates it.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Release requires documented authority and a second reviewer where company policy mandates it. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-481 — Access to hold scope and matter details must be restricted to authorised legal/leadership roles.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Access to hold scope and matter details must be restricted to authorised legal/leadership roles. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-482 — Conflicting retention jobs must identify held records before disposal.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Conflicting retention jobs must identify held records before disposal. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-483 — Hold reviews must be scheduled and overdue reviews escalated to the matter owner.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Hold reviews must be scheduled and overdue reviews escalated to the matter owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-484 — Evidence of hold issue, acknowledgement, scope change and release must be retained.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** legal_holds, contracts, document_vault, data_retention · **Suggested owner:** Founder / Legal Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Evidence of hold issue, acknowledgement, scope change and release must be retained. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Notification routing, deduplication & quiet hours

### UH-485 — Each rule must name trigger, severity, recipient logic, dedupe window and accountable owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each rule must name trigger, severity, recipient logic, dedupe window and accountable owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-486 — Critical security alerts must bypass optional quiet hours when the policy requires immediate routing.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Critical security alerts must bypass optional quiet hours when the policy requires immediate routing. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-487 — Repeated identical alerts must be grouped or deduplicated without hiding a severity escalation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Repeated identical alerts must be grouped or deduplicated without hiding a severity escalation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-488 — Inactive recipients must be replaced with a documented fallback owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Inactive recipients must be replaced with a documented fallback owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-489 — Rule changes must be tested against representative events before activation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Rule changes must be tested against representative events before activation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-490 — Notification content must not contain passwords, OTPs, session cookies or secret values.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Notification content must not contain passwords, OTPs, session cookies or secret values. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-491 — Delivery failure must record provider state and retry outcome without infinite loops.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Delivery failure must record provider state and retry outcome without infinite loops. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-492 — Periodic review must detect orphaned rules, empty recipients and overlapping trigger conditions.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** notification_rules, notifications, incidents, tasks · **Suggested owner:** Operations / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Periodic review must detect orphaned rules, empty recipients and overlapping trigger conditions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Scheduled reports & export governance

### UH-493 — Each report schedule must specify audience, scope, owner, cadence, retention and approval state.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each report schedule must specify audience, scope, owner, cadence, retention and approval state. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-494 — Scheduled exports must execute under a scoped service identity, not a shared super-admin session.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Scheduled exports must execute under a scoped service identity, not a shared super-admin session. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-495 — Sensitive report recipients must be checked at send time in case their role or employment status changed.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive report recipients must be checked at send time in case their role or employment status changed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-496 — Export failure must be recorded and must not silently send a partial report as complete.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Export failure must be recorded and must not silently send a partial report as complete. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-497 — Large or sensitive exports must require a recorded business reason and authorisation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Large or sensitive exports must require a recorded business reason and authorisation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-498 — CSV output must escape spreadsheet formulas and prevent script-like cell execution on open.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: CSV output must escape spreadsheet formulas and prevent script-like cell execution on open. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-499 — Generated report files must expire according to their approved retention window.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Generated report files must expire according to their approved retention window. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-500 — Report history must include data freshness, applied filters, result count and delivery evidence.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** report_schedules, finance, data_requests, audit logs · **Suggested owner:** Founder / Data Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Report history must include data freshness, applied filters, result count and delivery evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Company events, calendar & RSVP

### UH-501 — Events must have start/end times, timezone, organiser and intended audience.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Events must have start/end times, timezone, organiser and intended audience. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-502 — End time must be after start time and overlapping venue/resource bookings must be flagged.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: End time must be after start time and overlapping venue/resource bookings must be flagged. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-503 — RSVP status must be linked to a member identity and allow only permitted audience members to respond.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: RSVP status must be linked to a member identity and allow only permitted audience members to respond. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-504 — Private calendar items must not expose confidential leave, grievance or personal reasons.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Private calendar items must not expose confidential leave, grievance or personal reasons. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-505 — Event updates and cancellations must notify registered participants with delivery status.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Event updates and cancellations must notify registered participants with delivery status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-506 — Recurring events must handle skipped dates, holidays and timezone transitions.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Recurring events must handle skipped dates, holidays and timezone transitions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-507 — Event attendance data must follow a documented purpose and retention policy.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Event attendance data must follow a documented purpose and retention policy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-508 — The UI must offer usable list and calendar-style views on mobile and desktop.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** event_calendar, announcements, leave, meetings · **Suggested owner:** HR / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The UI must offer usable list and calendar-style views on mobile and desktop. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Digital member IDs, QR references & revocation

### UH-509 — Each digital ID must reference a unique member identifier and minimal approved display fields.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each digital ID must reference a unique member identifier and minimal approved display fields. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-510 — The QR payload must contain no password, OTP, session token or other authentication secret.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The QR payload must contain no password, OTP, session token or other authentication secret. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-511 — QR references must be revocable and must resolve only to allowed public/minimal member data.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: QR references must be revocable and must resolve only to allowed public/minimal member data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-512 — ID issue, renewal and revocation must be auditable with actor, reason and timestamp.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: ID issue, renewal and revocation must be auditable with actor, reason and timestamp. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-513 — Exited or suspended members must not retain an active verification status in the ID registry.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exited or suspended members must not retain an active verification status in the ID registry. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-514 — Member photo references must point to private files and use access checks before retrieval.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Member photo references must point to private files and use access checks before retrieval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-515 — Public verification must not reveal private email, phone, address, HR status or internal project access.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Public verification must not reveal private email, phone, address, HR status or internal project access. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-516 — Lost-device and QR-sharing risks must be documented and tested before IDs are treated as access credentials.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Lost-device and QR-sharing risks must be documented and tested before IDs are treated as access credentials. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Team workload and daily check-ins

### UH-517 — Daily check-ins must capture planned work, actual progress, blockers and next action without requesting unnecessary personal data.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Daily check-ins must capture planned work, actual progress, blockers and next action without requesting unnecessary personal data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-518 — Worklog hours must be separate from task completion and quality outcome metrics.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Worklog hours must be separate from task completion and quality outcome metrics. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-519 — An absent check-in must create a reminder or review signal, not an automatic disciplinary result.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: An absent check-in must create a reminder or review signal, not an automatic disciplinary result. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-520 — Team leads must see only their assigned scope and may not access restricted HR case details.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Team leads must see only their assigned scope and may not access restricted HR case details. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-521 — Check-in edit history must preserve original content for the defined retention period.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Check-in edit history must preserve original content for the defined retention period. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-522 — Workload dashboards must account for leave, holidays, role changes and partial schedules.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Workload dashboards must account for leave, holidays, role changes and partial schedules. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-523 — Employees must be able to add context and appeal incorrect blocker or activity classifications.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Employees must be able to add context and appeal incorrect blocker or activity classifications. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-524 — Team rollups must use approved/recorded values and disclose missing or stale updates.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, time_tracking, capacity_planning, employee_status · **Suggested owner:** Project Lead / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Team rollups must use approved/recorded values and disclose missing or stale updates. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Blocker escalation & clarification

### UH-525 — Blockers must include category, impact, owner, start time and requested assistance.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Blockers must include category, impact, owner, start time and requested assistance. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-526 — Critical blockers must notify the assigned lead and designated escalation route.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Critical blockers must notify the assigned lead and designated escalation route. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-527 — Escalation timers must pause only for documented states defined by policy.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Escalation timers must pause only for documented states defined by policy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-528 — A resolved blocker must record resolution details and the resulting task/project status.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A resolved blocker must record resolution details and the resulting task/project status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-529 — Repeated blockers with the same cause must be linkable to a root-cause action.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Repeated blockers with the same cause must be linkable to a root-cause action. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-530 — Blocker detail visibility must follow project and confidentiality rules.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Blocker detail visibility must follow project and confidentiality rules. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-531 — Employee clarification responses must remain attached to the history and must not be silently removed.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Employee clarification responses must remain attached to the history and must not be silently removed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-532 — Escalation reports must distinguish blocked work from ordinary overdue tasks.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, helpdesk, incidents, notifications · **Suggested owner:** Project Lead / Operations
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Escalation reports must distinguish blocked work from ordinary overdue tasks. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Task dependencies and milestone risk

### UH-533 — Dependency links must reference existing tasks/milestones and must remain within allowed project boundaries.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Dependency links must reference existing tasks/milestones and must remain within allowed project boundaries. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-534 — Circular dependencies must be rejected before the schedule is saved.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Circular dependencies must be rejected before the schedule is saved. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-535 — A predecessor delay must recalculate downstream risk using a documented rule.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A predecessor delay must recalculate downstream risk using a documented rule. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-536 — Milestone readiness must check acceptance criteria, required evidence and dependent work.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Milestone readiness must check acceptance criteria, required evidence and dependent work. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-537 — Dependency changes must capture who changed the relationship, the reason and the previous chain.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Dependency changes must capture who changed the relationship, the reason and the previous chain. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-538 — Project risk flags must distinguish computed warnings from an approved human risk assessment.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project risk flags must distinguish computed warnings from an approved human risk assessment. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-539 — Blocked downstream tasks must link to the dependency responsible for the block.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Blocked downstream tasks must link to the dependency responsible for the block. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-540 — Schedule summaries must show assumptions and must not present estimates as guarantees.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** tasks, milestones, projects, risks · **Suggested owner:** Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Schedule summaries must show assumptions and must not present estimates as guarantees. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Submission evidence & reviewer quality

### UH-541 — Every submission must reference an existing assigned task and identify the submitter server-side.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every submission must reference an existing assigned task and identify the submitter server-side. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-542 — Evidence files must be private, size-limited, content-checked and scanned before being trusted in production.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Evidence files must be private, size-limited, content-checked and scanned before being trusted in production. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-543 — Review decisions must be made by an authorised reviewer other than the submitter.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Review decisions must be made by an authorised reviewer other than the submitter. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-544 — Revision requests must include actionable feedback and preserve each prior submission version.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Revision requests must include actionable feedback and preserve each prior submission version. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-545 — Reviewer response time must be measured from the actual submission timestamp.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reviewer response time must be measured from the actual submission timestamp. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-546 — Accepted submissions must record reviewer identity, decision time and acceptance rationale.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Accepted submissions must record reviewer identity, decision time and acceptance rationale. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-547 — Sensitive evidence downloads must be audited and blocked for unrelated projects.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive evidence downloads must be audited and blocked for unrelated projects. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-548 — Sampling review must assess consistency and appeal outcomes, not only throughput.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** task_submissions, document_vault, tasks, performance_reviews · **Suggested owner:** Project Lead / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sampling review must assess consistency and appeal outcomes, not only throughput. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Project portfolio management

### UH-549 — Portfolio views must show ownership, health, next milestone, major dependency and last-updated date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Portfolio views must show ownership, health, next milestone, major dependency and last-updated date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-550 — Portfolio KPIs must be calculated from visible source records and explain their underlying logic.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Portfolio KPIs must be calculated from visible source records and explain their underlying logic. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-551 — Cross-project risks must identify an accountable owner and mitigation action.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Cross-project risks must identify an accountable owner and mitigation action. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-552 — Projects without an active owner must be flagged before appearing healthy.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Projects without an active owner must be flagged before appearing healthy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-553 — Portfolio exports must aggregate data only from records accessible to the requester.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Portfolio exports must aggregate data only from records accessible to the requester. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-554 — Project closure must reconcile open tasks, assets, private files, approvals and retained evidence.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project closure must reconcile open tasks, assets, private files, approvals and retained evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-555 — Project scope or budget changes must be versioned with reason and approval.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project scope or budget changes must be versioned with reason and approval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-556 — Monthly portfolio review must preserve a dated snapshot and outstanding decision register.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, goals, capacity_planning, risks, finance · **Suggested owner:** Founder / PMO
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Monthly portfolio review must preserve a dated snapshot and outstanding decision register. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Project health score transparency

### UH-557 — Every health score must disclose the indicators, weights, thresholds and refresh timestamp used.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every health score must disclose the indicators, weights, thresholds and refresh timestamp used. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-558 — Missing or stale inputs must be identified rather than silently treated as zero risk.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Missing or stale inputs must be identified rather than silently treated as zero risk. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-559 — A human owner must be able to annotate or challenge a calculated risk score.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A human owner must be able to annotate or challenge a calculated risk score. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-560 — Health-score changes must retain the previous value, trigger, calculation version and reviewer.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Health-score changes must retain the previous value, trigger, calculation version and reviewer. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-561 — No health score may alone trigger member punishment, suspension or termination.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: No health score may alone trigger member punishment, suspension or termination. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-562 — Project health must separate schedule, scope, quality, dependency and resourcing risks.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project health must separate schedule, scope, quality, dependency and resourcing risks. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-563 — Threshold changes must be versioned and reviewed before being applied to active reports.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Threshold changes must be versioned and reviewed before being applied to active reports. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-564 — Tests must cover edge cases, conflicting inputs and incomplete project records.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** projects, milestones, tasks, risks, kpis · **Suggested owner:** Founder / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Tests must cover edge cases, conflicting inputs and incomplete project records. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Worklog approvals & hour anomalies

### UH-565 — Worklogs must identify the member, date, linked task, quantity and submission status.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Worklogs must identify the member, date, linked task, quantity and submission status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-566 — Worklog approval must be performed by an authorised reviewer who is not the submitter.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Worklog approval must be performed by an authorised reviewer who is not the submitter. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-567 — Negative, non-finite or unreasonable hour entries must be rejected or flagged per company policy.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Negative, non-finite or unreasonable hour entries must be rejected or flagged per company policy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-568 — Duplicate daily task entries must be detectable and must preserve legitimate split shifts.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Duplicate daily task entries must be detectable and must preserve legitimate split shifts. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-569 — Anomalies must create a review task rather than an automatic accusation of misconduct.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Anomalies must create a review task rather than an automatic accusation of misconduct. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-570 — Changes after approval must trigger re-approval and retain the original approved version.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Changes after approval must trigger re-approval and retain the original approved version. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-571 — Billable and non-billable totals must use clearly defined rounding and timezone rules.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Billable and non-billable totals must use clearly defined rounding and timezone rules. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-572 — Reports must show unsubmitted, rejected and approved hours separately.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** time_tracking, tasks, capacity_planning, finance · **Suggested owner:** Project Lead / Finance
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reports must show unsubmitted, rejected and approved hours separately. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Leave-aware planning and coverage

### UH-573 — Leave requests must prevent invalid date ranges and expose only necessary details to managers.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Leave requests must prevent invalid date ranges and expose only necessary details to managers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-574 — Approved leave must update availability and workload forecasts from the effective date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approved leave must update availability and workload forecasts from the effective date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-575 — Leave overlaps with scheduled critical coverage must request a replacement or explicit exception.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Leave overlaps with scheduled critical coverage must request a replacement or explicit exception. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-576 — Leave balances must use a ledger of grants, usage and adjustments rather than a hidden editable total.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Leave balances must use a ledger of grants, usage and adjustments rather than a hidden editable total. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-577 — A denied request must include a reason and appeal path.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A denied request must include a reason and appeal path. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-578 — Work-inactivity alerts must be suppressed or contextualised for approved leave and company holidays.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Work-inactivity alerts must be suppressed or contextualised for approved leave and company holidays. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-579 — Calendar views must hide sensitive leave type/reason from unauthorised colleagues.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Calendar views must hide sensitive leave type/reason from unauthorised colleagues. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-580 — Balance corrections must require a reason, reviewer and before/after audit record.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** leave, shift_planning, attendance, capacity_planning · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Balance corrections must require a reason, reviewer and before/after audit record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Fair inactivity detection and appeal

### UH-581 — Inactivity thresholds must be configurable and use work activity evidence, not login alone.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Inactivity thresholds must be configurable and use work activity evidence, not login alone. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-582 — Approved leave, suspension, holidays and role-transition periods must be considered before alerting.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Approved leave, suspension, holidays and role-transition periods must be considered before alerting. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-583 — Initial inactivity alerts must prompt a human review and never automatically change employment status.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Initial inactivity alerts must prompt a human review and never automatically change employment status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-584 — The affected member must be able to provide clarification through an authorised channel.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The affected member must be able to provide clarification through an authorised channel. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-585 — Status classification changes must record evidence, reviewer, reason and review date.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Status classification changes must record evidence, reviewer, reason and review date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-586 — Managers must not see raw unrelated personal or grievance data while reviewing inactivity.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Managers must not see raw unrelated personal or grievance data while reviewing inactivity. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-587 — Rules must be tested with contractors, part-time schedules, recently joined members and system outages.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Rules must be tested with contractors, part-time schedules, recently joined members and system outages. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-588 — A review dashboard must expose false-positive and appeal outcomes so thresholds can be improved.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** employee_status, attendance, leave, task_submissions · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A review dashboard must expose false-positive and appeal outcomes so thresholds can be improved. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Configurable department KPI formulas

### UH-589 — Each KPI must define metric, formula, direction, target, unit, period and accountable owner.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each KPI must define metric, formula, direction, target, unit, period and accountable owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-590 — KPI formula changes must create a version and retain the target/actual context of past periods.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: KPI formula changes must create a version and retain the target/actual context of past periods. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-591 — Quality and timeliness indicators must be visible separately from quantity measures.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Quality and timeliness indicators must be visible separately from quantity measures. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-592 — Null inputs must be marked missing and must not silently contribute a zero score.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Null inputs must be marked missing and must not silently contribute a zero score. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-593 — Department filters must restrict the underlying member-level records to authorised viewers.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Department filters must restrict the underlying member-level records to authorised viewers. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-594 — Exceptional conditions and approved target changes must be annotated with reason and approver.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exceptional conditions and approved target changes must be annotated with reason and approver. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-595 — Attainment calculations must be reproducible from stored input snapshots.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Attainment calculations must be reproducible from stored input snapshots. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-596 — A score alone must never automatically decide salary, discipline, suspension or termination.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** kpis, departments, performance_reviews, goals · **Suggested owner:** Founder / HR
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A score alone must never automatically decide salary, discipline, suspension or termination. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Performance review approval and appeals

### UH-597 — Reviews must define period, reviewer, evidence scope and review status before submission.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reviews must define period, reviewer, evidence scope and review status before submission. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-598 — Reviewer conflict-of-interest checks must be available for reassignment.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reviewer conflict-of-interest checks must be available for reassignment. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-599 — Employee acknowledgement must be distinct from agreement with the review.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Employee acknowledgement must be distinct from agreement with the review. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-600 — An appeal must retain the original review and assign a separate authorised reviewer.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: An appeal must retain the original review and assign a separate authorised reviewer. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-601 — Review text must be immutable to the reviewer after submission unless a revision is explicitly reopened.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Review text must be immutable to the reviewer after submission unless a revision is explicitly reopened. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-602 — Sensitive review notes must not appear in broad project-member cards or exports.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive review notes must not appear in broad project-member cards or exports. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-603 — Decision outcomes must record support actions, owner and follow-up date where relevant.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Decision outcomes must record support actions, owner and follow-up date where relevant. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-604 — Tests must cover employee disagreement, late review, manager exit and reviewer conflict.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** performance_reviews, kpis, employee_status, hr_cases · **Suggested owner:** HR / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Tests must cover employee disagreement, late review, manager exit and reviewer conflict. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Quarterly company planning & OKR rollups

### UH-605 — Quarterly plans must record strategic objective, accountable owner, timeframe and success measures.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Quarterly plans must record strategic objective, accountable owner, timeframe and success measures. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-606 — Department and project goals must link to parent company goals with valid references.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Department and project goals must link to parent company goals with valid references. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-607 — Progress rollups must show both the formula and timestamp of the underlying source records.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Progress rollups must show both the formula and timestamp of the underlying source records. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-608 — Dependencies and staffing assumptions must be explicit before approving a goal.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Dependencies and staffing assumptions must be explicit before approving a goal. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-609 — Goal edits after sign-off must require versioned change reasons and approval.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Goal edits after sign-off must require versioned change reasons and approval. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-610 — At quarter-end the platform must preserve final values, incomplete key results and carryover items.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: At quarter-end the platform must preserve final values, incomplete key results and carryover items. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-611 — Leadership dashboards must not reveal restricted HR, grievance, client or finance details to broader audiences.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Leadership dashboards must not reveal restricted HR, grievance, client or finance details to broader audiences. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-612 — Post-cycle review must record actual outcomes, lessons, owners and the next review date.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** goals, okr_cycles, kpis, decisions · **Suggested owner:** Founder / Leadership
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Post-cycle review must record actual outcomes, lessons, owners and the next review date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Incident postmortems and corrective actions

### UH-613 — High-severity incidents must have a timeline, owner, containment summary and impact assessment.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: High-severity incidents must have a timeline, owner, containment summary and impact assessment. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-614 — A postmortem must identify root cause, contributing factors and verified corrective actions.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A postmortem must identify root cause, contributing factors and verified corrective actions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-615 — Corrective actions must have an owner, priority, due date and closure evidence.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Corrective actions must have an owner, priority, due date and closure evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-616 — Sensitive exploit details must be restricted to the incident response roles that need them.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive exploit details must be restricted to the incident response roles that need them. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-617 — Incident changes must preserve chronology and avoid editing timestamps to hide delays.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Incident changes must preserve chronology and avoid editing timestamps to hide delays. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-618 — Lessons learned must link to policy, test or system changes where relevant.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Lessons learned must link to policy, test or system changes where relevant. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-619 — Repeated incidents must be grouped for trend analysis while preserving individual evidence.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Repeated incidents must be grouped for trend analysis while preserving individual evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-620 — Closure must require the designated reviewer and a post-incident review status.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, risks, releases, tasks · **Suggested owner:** Security Reviewer / Engineering
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Closure must require the designated reviewer and a post-incident review status. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Business continuity exercise tracking

### UH-621 — Continuity plans must name critical services, recovery owner, dependencies and contact route.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Continuity plans must name critical services, recovery owner, dependencies and contact route. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-622 — Each critical service must have approved recovery time and recovery point objectives.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each critical service must have approved recovery time and recovery point objectives. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-623 — Exercises must document scenario, participants, start/end time, outcome and evidence.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exercises must document scenario, participants, start/end time, outcome and evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-624 — Unmet recovery objectives must create corrective actions with accountable owners.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Unmet recovery objectives must create corrective actions with accountable owners. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-625 — Vendor and integration dependencies must be included in the continuity scope.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Vendor and integration dependencies must be included in the continuity scope. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-626 — Exercise records must distinguish tabletop discussion from a real technical restore/recovery test.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exercise records must distinguish tabletop discussion from a real technical restore/recovery test. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-627 — Continuity plans must be versioned and accessible during an outage using an approved alternate route.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Continuity plans must be versioned and accessible during an outage using an approved alternate route. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-628 — Leadership must review unresolved continuity risks by a documented cadence.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** continuity, backup_jobs, releases, vendors · **Suggested owner:** Founder / Technical Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Leadership must review unresolved continuity risks by a documented cadence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Backup recovery and restore assurance

### UH-629 — Backup inventory must state dataset scope, encryption mode, timestamp, storage destination and retention.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Backup inventory must state dataset scope, encryption mode, timestamp, storage destination and retention. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-630 — Backup keys must be held separately from backup archives and have a tested recovery procedure.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Backup keys must be held separately from backup archives and have a tested recovery procedure. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-631 — Authenticated encryption failure or checksum mismatch must cause restore to stop without loading the data.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Authenticated encryption failure or checksum mismatch must cause restore to stop without loading the data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-632 — Restore must occur in a clean target environment and must never silently overwrite a live database.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Restore must occur in a clean target environment and must never silently overwrite a live database. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-633 — Database integrity, attachment inventory and referenced file hashes must be reconciled after restore.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Database integrity, attachment inventory and referenced file hashes must be reconciled after restore. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-634 — Restore drills must record achieved recovery time and data-loss window against approved objectives.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Restore drills must record achieved recovery time and data-loss window against approved objectives. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-635 — At least one backup copy must reside in separately protected storage before production sign-off.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: At least one backup copy must reside in separately protected storage before production sign-off. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-636 — Backup failures, age breaches and missing off-site copies must alert the designated owner.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** backup_jobs, continuity, audit logs, private_files · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Backup failures, age breaches and missing off-site copies must alert the designated owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Database integrity and schema migrations

### UH-637 — Every schema change must be versioned, repeatable and recorded in a migration ledger.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every schema change must be versioned, repeatable and recorded in a migration ledger. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-638 — Migrations must be tested from a clean install and a copy of the previous supported schema.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Migrations must be tested from a clean install and a copy of the previous supported schema. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-639 — Failed migrations must stop deployment and provide an approved rollback or forward-fix procedure.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Failed migrations must stop deployment and provide an approved rollback or forward-fix procedure. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-640 — Foreign-key and unique-key constraints must be checked as part of migration validation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Foreign-key and unique-key constraints must be checked as part of migration validation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-641 — Sensitive historical fields must be preserved or transformed only under an approved migration plan.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive historical fields must be preserved or transformed only under an approved migration plan. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-642 — Database backup must complete before any migration with data-loss risk.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Database backup must complete before any migration with data-loss risk. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-643 — Migration logs must exclude credentials and member content not needed for diagnosis.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Migration logs must exclude credentials and member content not needed for diagnosis. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-644 — Release acceptance must attach migration test output and post-migration integrity results.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** releases, continuity, compliance · **Suggested owner:** Technical Owner / Developer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Release acceptance must attach migration test output and post-migration integrity results. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Environment configuration and secret management

### UH-645 — Production secrets must be injected through protected environment/secret management, never hard-coded.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Production secrets must be injected through protected environment/secret management, never hard-coded. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-646 — Startup validation must reject weak or missing session secrets and unsafe production origin settings.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Startup validation must reject weak or missing session secrets and unsafe production origin settings. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-647 — Secrets must not be printed to logs, health endpoints, error responses or client-side configuration.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Secrets must not be printed to logs, health endpoints, error responses or client-side configuration. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-648 — Key rotation must include dependent service verification and old-key revocation.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Key rotation must include dependent service verification and old-key revocation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-649 — Development, staging and production must use separate credentials and storage locations.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Development, staging and production must use separate credentials and storage locations. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-650 — Build artifacts and source-control ignore rules must exclude environment files, databases, private uploads and backups.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Build artifacts and source-control ignore rules must exclude environment files, databases, private uploads and backups. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-651 — Privileged recovery materials must have named custodians and a tested access procedure.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Privileged recovery materials must have named custodians and a tested access procedure. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-652 — Secret-leak response must include rotation, audit review and assessment of previously accessible data.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** integrations, api_registry, secret_rotation_register · **Suggested owner:** Technical Owner / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Secret-leak response must include rotation, audit review and assessment of previously accessible data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Data classification and document lifecycle

### UH-653 — Each document must carry a classification, owner, version, review date and retention category.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Each document must carry a classification, owner, version, review date and retention category. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-654 — Classification changes must re-evaluate viewer roles, attachment access and previously issued links.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Classification changes must re-evaluate viewer roles, attachment access and previously issued links. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-655 — Private documents must be stored outside the public web root and retrieved through authenticated access checks.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Private documents must be stored outside the public web root and retrieved through authenticated access checks. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-656 — Production file acceptance must include malware scanning and quarantine before a document is trusted.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Production file acceptance must include malware scanning and quarantine before a document is trusted. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-657 — Downloads must be audited and use attachment disposition, safe filenames and content-sniffing protections.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Downloads must be audited and use attachment disposition, safe filenames and content-sniffing protections. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-658 — Version replacement must preserve prior versions and identify the approving editor.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Version replacement must preserve prior versions and identify the approving editor. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-659 — Legal hold must suspend disposal for covered documents and related evidence.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Legal hold must suspend disposal for covered documents and related evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-660 — Document review reminders must identify stale and ownerless content without exposing document contents.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, knowledge, policies, data_retention · **Suggested owner:** Security Reviewer / Document Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Document review reminders must identify stale and ownerless content without exposing document contents. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Private file scanning and download controls

### UH-661 — Uploads must have size limits, allow-listed type, file-signature verification and storage names not derived from the upload path.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Uploads must have size limits, allow-listed type, file-signature verification and storage names not derived from the upload path. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-662 — Content scanning must run before release from quarantine when production malware scanning is configured.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Content scanning must run before release from quarantine when production malware scanning is configured. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-663 — File download must re-check both record permission and file classification for every request.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: File download must re-check both record permission and file classification for every request. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-664 — Restricted files must not become more accessible merely because they are attached to an internal record.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Restricted files must not become more accessible merely because they are attached to an internal record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-665 — File metadata must include uploader, checksum, classification, timestamp and linked record.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: File metadata must include uploader, checksum, classification, timestamp and linked record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-666 — Malformed, oversized and signature-mismatched files must be rejected and logged without storing them as trusted attachments.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Malformed, oversized and signature-mismatched files must be rejected and logged without storing them as trusted attachments. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-667 — Backups must contain private files and a manifest that can be reconciled after restoration.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Backups must contain private files and a manifest that can be reconciled after restoration. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-668 — Expired, quarantined and legally held files must follow distinct retention workflows.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** document_vault, private_files, grievances, contracts · **Suggested owner:** Security Reviewer / Owner
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Expired, quarantined and legally held files must follow distinct retention workflows. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Member photo and digital ID privacy

### UH-669 — Member photos must be treated as personal data and stored privately with access-controlled references.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Member photos must be treated as personal data and stored privately with access-controlled references. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-670 — A digital ID must show only approved fields such as name, member ID, designation and company mark.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A digital ID must show only approved fields such as name, member ID, designation and company mark. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-671 — The QR reference must be random and non-authorising; it must not function as a session credential.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: The QR reference must be random and non-authorising; it must not function as a session credential. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-672 — Photo change, ID issue, expiry and revocation must create history records.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Photo change, ID issue, expiry and revocation must create history records. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-673 — Exited members must be marked inactive/revoked on the card and directory according to policy.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exited members must be marked inactive/revoked on the card and directory according to policy. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-674 — Public QR validation must not reveal email, phone, home address, salary, HR status or project details.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Public QR validation must not reveal email, phone, home address, salary, HR status or project details. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-675 — ID card rendering must work at small-screen print dimensions and remain legible without exposing hidden fields.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: ID card rendering must work at small-screen print dimensions and remain legible without exposing hidden fields. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-676 — Member photo removal/correction requests must be handled under the approved privacy and retention process.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** digital_id_cards, org_directory, onboarding, offboarding · **Suggested owner:** HR / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Member photo removal/correction requests must be handled under the approved privacy and retention process. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Remote access and device-risk review

### UH-677 — Privileged access must use enforced multi-factor authentication before production release.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Privileged access must use enforced multi-factor authentication before production release. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-678 — Session/device inventory must show last-seen time, revocation state and a user-safe device label.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Session/device inventory must show last-seen time, revocation state and a user-safe device label. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-679 — Suspicious login patterns must create an alert with evidence, not disclose session secrets.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Suspicious login patterns must create an alert with evidence, not disclose session secrets. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-680 — Suspended or exited accounts must lose authenticated access on the next request and all active sessions must be revoked.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Suspended or exited accounts must lose authenticated access on the next request and all active sessions must be revoked. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-681 — Remote access exceptions must have a named approver, defined scope and expiry date.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Remote access exceptions must have a named approver, defined scope and expiry date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-682 — Session IDs and OTPs must never be stored in general member records or event descriptions.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Session IDs and OTPs must never be stored in general member records or event descriptions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-683 — Users must be able to revoke their own sessions, while privileged global revocation remains audited.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Users must be able to revoke their own sessions, while privileged global revocation remains audited. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-684 — Security reviewers must test session fixation, cross-site requests, reuse after logout and revoked-session behaviour.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** sessions_devices, permissions_access, incidents · **Suggested owner:** Security Reviewer / Founder
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Security reviewers must test session fixation, cross-site requests, reuse after logout and revoked-session behaviour. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Audit tamper evidence and retention

### UH-685 — Sensitive events must record actor, timestamp, action, target, outcome and reason, without storing secrets.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Sensitive events must record actor, timestamp, action, target, outcome and reason, without storing secrets. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-686 — Application roles must not be able to hard-delete ordinary audit rows through any API route.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Application roles must not be able to hard-delete ordinary audit rows through any API route. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-687 — High-assurance deployments must forward critical audit events to separately protected append-only storage.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: High-assurance deployments must forward critical audit events to separately protected append-only storage. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-688 — Audit records must be integrity checked and have a documented retention schedule.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Audit records must be integrity checked and have a documented retention schedule. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-689 — Permission changes must record before/after role and scope values.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Permission changes must record before/after role and scope values. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-690 — Security reviewers must see only authorised event categories and must not receive unrelated grievance or finance details.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Security reviewers must see only authorised event categories and must not receive unrelated grievance or finance details. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-691 — Audit export must be reasoned, scoped and logged as another sensitive action.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Audit export must be reasoned, scoped and logged as another sensitive action. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-692 — Tamper-detection alerts must be routed to a separate administrative path and tested during recovery exercises.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** audit logs, incidents, permissions_access, compliance · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Tamper-detection alerts must be routed to a separate administrative path and tested during recovery exercises. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Security incident communications and breach assessment

### UH-693 — Incident severity must include criteria for potential personal-data exposure and business impact.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Incident severity must include criteria for potential personal-data exposure and business impact. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-694 — Breach assessment must record known scope, affected systems/data classes and uncertainty.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Breach assessment must record known scope, affected systems/data classes and uncertainty. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-695 — External notification obligations must be assessed by an authorised owner with qualified legal review where needed.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: External notification obligations must be assessed by an authorised owner with qualified legal review where needed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-696 — Internal updates must target roles that need the information and avoid circulating exploit details widely.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Internal updates must target roles that need the information and avoid circulating exploit details widely. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-697 — Incident communications must be versioned and tied to the incident record.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Incident communications must be versioned and tied to the incident record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-698 — Containment/recovery updates must distinguish verified facts from hypotheses.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Containment/recovery updates must distinguish verified facts from hypotheses. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-699 — Notification decisions and reasons must be auditable even when the decision is not to notify.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Notification decisions and reasons must be auditable even when the decision is not to notify. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-700 — Post-incident follow-up must link corrective actions, policy changes, affected-member support and closure sign-off.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** incidents, data_requests, announcements, legal_holds · **Suggested owner:** Founder / Security Reviewer
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Post-incident follow-up must link corrective actions, policy changes, affected-member support and closure sign-off. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Role lifecycle approvals and periodic review

### UH-701 — Every privileged role assignment must require a reason, scope, approver and review date.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Every privileged role assignment must require a reason, scope, approver and review date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-702 — Only the Founder may grant roles defined by the company as Founder/Super Admin privileged, under a guarded workflow.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Only the Founder may grant roles defined by the company as Founder/Super Admin privileged, under a guarded workflow. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-703 — Self-approval and same-person second approval must be rejected server-side.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Self-approval and same-person second approval must be rejected server-side. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-704 — Role transfers must preserve prior permissions and produce a before/after audit record.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Role transfers must preserve prior permissions and produce a before/after audit record. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-705 — Project Lead assignment must reference a live project record and have a clear expiry/review point.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project Lead assignment must reference a live project record and have a clear expiry/review point. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-706 — Periodic access review must identify stale, excessive, orphaned and expired permissions.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Periodic access review must identify stale, excessive, orphaned and expired permissions. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-707 — Exiting or suspended members must have all sessions, project memberships and integration grants revoked.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exiting or suspended members must have all sessions, project memberships and integration grants revoked. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-708 — A failed access review must lead to an accountable remediation record with due date.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** permissions_access, org_directory, onboarding, offboarding · **Suggested owner:** Founder / Super Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: A failed access review must lead to an accountable remediation record with due date. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Onboarding training and policy acknowledgement

### UH-709 — New accounts must remain pending until the required verification and authorised approval steps complete.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: New accounts must remain pending until the required verification and authorised approval steps complete. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-710 — Required policy acknowledgements must record policy version, member identity and timestamp.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Required policy acknowledgements must record policy version, member identity and timestamp. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-711 — Training assignments must define due date, completion evidence and renewal requirements.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Training assignments must define due date, completion evidence and renewal requirements. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-712 — Privileged onboarding must include security training and MFA verification before elevated access.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Privileged onboarding must include security training and MFA verification before elevated access. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-713 — First-login credential rotation must be enforced when temporary credentials are issued.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: First-login credential rotation must be enforced when temporary credentials are issued. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-714 — Onboarding blockers must have an owner, reason and next action.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Onboarding blockers must have an owner, reason and next action. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-715 — Member profile photo and digital ID issue must be optional until collection is justified and consent/notice is handled.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Member profile photo and digital ID issue must be optional until collection is justified and consent/notice is handled. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-716 — Onboarding completion must generate an auditable handoff from HR to the member’s project owner.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** onboarding, policies, training, digital_id_cards · **Suggested owner:** HR / Member Admin
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Onboarding completion must generate an auditable handoff from HR to the member’s project owner. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Offboarding ownership and reconciliation

### UH-717 — Exit approval must create a task checklist for account access, session revocation, assets and data ownership.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exit approval must create a task checklist for account access, session revocation, assets and data ownership. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-718 — Project ownership must transfer to an active approved member before a Project Lead exit is completed.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Project ownership must transfer to an active approved member before a Project Lead exit is completed. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-719 — Open tasks and approvals must be reassigned with before/after ownership history.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Open tasks and approvals must be reassigned with before/after ownership history. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-720 — Assets, licences and issued devices must be returned, transferred or assigned an approved exception.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Assets, licences and issued devices must be returned, transferred or assigned an approved exception. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-721 — Integration tokens and service credentials used by the exiting member must be rotated or revoked.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Integration tokens and service credentials used by the exiting member must be rotated or revoked. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-722 — Legal-hold review must run before any covered records are disposed of or transferred.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Legal-hold review must run before any covered records are disposed of or transferred. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-723 — Account suspension/exit must not erase required member history or audit evidence.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Account suspension/exit must not erase required member history or audit evidence. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-724 — Exit completion must include accountable review, unresolved exceptions and a timestamped completion report.
- **Priority:** P0 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** offboarding, tasks, assets, projects, sessions_devices · **Suggested owner:** HR / Project Lead
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Exit completion must include accountable review, unresolved exceptions and a timestamped completion report. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Mobile accessibility and responsive QA

### UH-725 — All major workspaces must remain usable at narrow phone widths without horizontal page overflow.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: All major workspaces must remain usable at narrow phone widths without horizontal page overflow. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-726 — Navigation and dialogs must support touch targets, visible focus states and keyboard navigation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Navigation and dialogs must support touch targets, visible focus states and keyboard navigation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-727 — Status must be conveyed with text and not colour alone.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Status must be conveyed with text and not colour alone. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-728 — Loading, error, empty and success states must be clear for every important operation.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Loading, error, empty and success states must be clear for every important operation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-729 — Charts and tracker summaries must have textual labels or accessible equivalent data.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Charts and tracker summaries must have textual labels or accessible equivalent data. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-730 — Forms must associate labels and validation messages with their inputs.
- **Priority:** P1 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Forms must associate labels and validation messages with their inputs. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-731 — Reduced-motion preferences must be respected by transitions and nonessential animation.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Reduced-motion preferences must be respected by transitions and nonessential animation. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

### UH-732 — Release screenshots and responsive test results must be retained for each supported viewport.
- **Priority:** P2 · **Source status:** Proposed / implementation and verification required · **Validation:** Not run
- **Related modules:** UI, all module workspaces, qa_test_cases · **Suggested owner:** Product Owner / QA
- **Acceptance check:** In a disposable environment, test this requirement end-to-end: Release screenshots and responsive test results must be retained for each supported viewport. For controls affecting access, run the same test as an unauthorised role and record the expected denial. Attach test output, build identifier, tester and date.
- **Evidence:** Add owner, tester, environment, dated evidence link and any approved exception.

## Release rule
Do not deploy with confidential member data based on checklist counts alone. Each control must pass the appropriate workflow and negative-permission tests and be signed off by an accountable owner. Review `RELEASE_READINESS.md` for production gates.
