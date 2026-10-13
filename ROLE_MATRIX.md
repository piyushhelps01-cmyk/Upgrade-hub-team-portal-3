# Role and Permission Matrix — v4.0 Baseline

The backend maps are in `src/server.js`. This document is a human-readable starting point, not a replacement for endpoint-level tests. Unknown roles and modules should default to denied. Privileged actions must use individual accounts, not shared logins.

| Capability / data | Founder | Super Admin | Admin | HR / Member Admin | Project Lead | Employee | Security Reviewer |
|---|---|---|---|---|---|---|---|
| All modules and company settings | Full | Platform-wide baseline | No | No | No | No | No |
| Member directory | Full | Full | Authorised | Authorised | No by default | Limited basic directory | No by default |
| Create pending employee/project lead | Yes | Yes | Yes | Yes, scoped | No | No | No |
| Create privileged roles | Yes, with reason/audit | No | No | No | No | No | No |
| Approve new member | Yes | Yes | Yes | No | No | No | No |
| Change member role | Founder-only route | No | No | No | No | No | No |
| Suspend / exit access | Yes | Yes, except Founder target | Selected non-privileged members | Limited by route | No | No | No |
| Company announcements/policies | All | All | Permitted operational view | HR scope | Shared view as configured | Published/shared view | Security/policy scope |
| Project/task records | All | All | Operational modules | HR-relevant modules | Assigned project and own records | Own/assigned records | Security-related only |
| Sensitive HR/grievance records | Full | Full | No by default | Case/assignment-scoped | No | Own submission/response | No by default |
| Contracts/finance/data exports | Full and audited | Policy-scoped baseline | No by default | No by default | No | No | No |
| Audit and security records | Full | Full | No by default | No | No | Own activity only | Relevant security scope |
| Create encrypted backup / download | Yes, reason required | Yes, reason required | No | No | No | No | No |
| Restore backup | Yes, offline host procedure | Yes, offline host procedure | No | No | No | No | No |
| Permanently delete member/history | No ordinary route | No ordinary route | No | No | No | No | No |

## Sensitive action rules

- Founder is the sole route for creating another Super Admin or changing an existing member role in this baseline. A second Founder cannot be created from the UI.
- Project Lead access is scoped to the assigned project identifier and own records; verify that every project reference is valid and visible to the caller.
- Employee submissions use server-side field allowlists so fields such as reviewer decisions, status classifications and approval fields are not self-authored through the common form.
- HR case records use assigned/created ownership logic; unassigned grievance cases are visible to authorised HR for triage, and should be assigned/recused before case details are broadly circulated.
- Security Reviewer can review relevant security/access/system records and update incident/risk/compliance records, but does not receive general finance/legal authoring.
- High-risk approvals require a different second approver where configured. Founder/Super Admin-only approval types are enforced at the decision endpoint.
- Backup creation and download require an explicit reason and are audited. Restoration is a separate offline host operation, not an in-app button.
- Hide/soft archive is not permanent deletion. Hidden comments and archived records retain history.

## Required production review

Run a negative test against each role for every restricted module and record. Review the role maps each time a module, role or endpoint changes. Ensure that no sensitive field, private file, session secret, password hash or OTP leaks through error responses, exports, UI metadata or logs.


## New restricted module families

- Founder/Super Admin only: purchase orders, expense claims, budget planning, finance/legal retention control and designated recovery/permission administration paths.
- HR: approved member lifecycle, department, shift, survey, recognition and digital-ID metadata modules based on current server maps.
- Project Leads: assigned-project delivery work, capacity, sprint, QA and related non-finance workspaces only.
- Security Reviewer: relevant incident/risk/compliance and approved security metadata workspaces. This role does not automatically receive access to HR grievances, employee reviews or finance data.
- Employee: own/assigned work, helpdesk/grievance submission, published/shared content and basic member ID/recognition features as permitted.

Re-test these mappings whenever the module catalogue or role map changes; a new field schema must not bypass server-side authorisation.
