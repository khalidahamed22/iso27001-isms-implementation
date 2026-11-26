# Joiner–Mover–Leaver (JML) Access Management Procedure

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Document ID:** CL-PROC-001  
**Version:** 1.0  
**Document Status:** Draft – Simulated Portfolio Document  
**Process Owner:** IT Manager  
**Supporting Functions:** Human Resources, Department Managers, System Owners, Information Security  
**Approval Authority:** Executive Management  
**Review Frequency:** Annually or following significant changes

---

## 1. Purpose

This procedure defines how CloudLedger Technologies manages user access when employees and contractors join the organisation, change roles or leave the organisation.

It ensures that access rights are authorised, appropriate, documented and removed when no longer required.

## 2. Scope

This procedure applies to employees, contractors and other authorised users who require access to:

- Corporate email and collaboration platforms.
- Cloud infrastructure and AWS environments.
- Financial management applications.
- Databases and production systems.
- Source code repositories.
- Corporate networks and endpoints.
- Security monitoring and administrative tools.

## 3. Responsibilities

| Role | Responsibility |
|---|---|
| Human Resources | Notify IT about joining, role changes and departures |
| Department Manager | Request and justify access |
| System Owner | Approve access to assigned systems |
| IT Administrator | Provision, modify and revoke access |
| Information Security Manager | Monitor compliance and review exceptions |
| Employee | Protect credentials and report access issues |

## 4. Joiner Process

When a new employee or contractor joins CloudLedger:

1. HR sends a joining notification to IT.
2. The department manager identifies required systems and access permissions.
3. The manager submits an access request.
4. Relevant system owners approve access.
5. IT creates the required accounts.
6. IT assigns permissions based on the employee's job role.
7. MFA and other required authentication controls are configured.
8. The employee receives security instructions.
9. IT records the completed provisioning activities.

**Required records:**
- HR joining notification.
- Approved access request.
- Account provisioning record.
- User acknowledgement of security responsibilities.

## 5. Mover Process

When an employee changes department, job role or responsibilities:

1. HR or the department manager notifies IT.
2. The manager identifies new access requirements.
3. Relevant system owners approve additional permissions.
4. IT removes permissions no longer required.
5. IT grants approved new permissions.
6. IT checks for conflicting access rights.
7. The changes are documented.

Existing access must not automatically remain when it is no longer required.

**Required records:**
- Role change notification.
- Updated access request.
- Approval records.
- Access modification record.

## 6. Leaver Process

When an employee or contractor leaves CloudLedger:

1. HR notifies IT of the departure and effective time.
2. IT identifies all accounts associated with the individual.
3. Access is disabled or revoked according to the departure timing and approved offboarding requirements.
4. Active sessions, tokens and remote access permissions are revoked where applicable.
5. Privileged credentials and shared secrets are rotated where necessary.
6. Company devices and other assets are returned.
7. The manager confirms handover of relevant business responsibilities.
8. IT records access revocation.
9. The completed offboarding process is reviewed.

For urgent or involuntary departures, access revocation must be coordinated with HR and management to take effect at the required departure time.

**Required records:**
- HR departure notification.
- Account revocation record.
- Asset return record.
- Offboarding checklist.
- Completion confirmation.

## 7. Emergency Access Changes

Where an immediate security risk exists, IT may disable or restrict access before completing the normal workflow, provided the action is authorised in accordance with the emergency process where practicable.

The action must be documented and reviewed afterwards.

## 8. Monitoring and Verification

The IT Manager shall periodically verify that:

- Joiner accounts have valid approvals.
- Mover access changes reflect current job responsibilities.
- Leaver accounts have been disabled or removed.
- Privileged permissions are justified.
- Required records are retained.

Exceptions shall be recorded and assigned for remediation.

## 9. Records Retention

JML records shall be retained according to the organisation's approved records retention requirements, legal obligations and contractual commitments.

Access to these records shall be restricted to authorised personnel.

## 10. Procedure Review

This procedure shall be reviewed annually or when significant changes occur to employment processes, systems, access management arrangements or security requirements.

## 11. Approval

**Process Owner:** IT Manager  
**Reviewed by:** Information Security Manager  
**Approved by:** Executive Management  
**Approval Status:** Pending – Simulated Portfolio Scenario

---

## ISO/IEC 27001:2022 Alignment

- Annex A 5.16 – Identity Management
- Annex A 5.18 – Access Rights
- Annex A 6.5 – Responsibilities After Termination or Change of Employment
- Annex A 8.2 – Privileged Access Rights
- Annex A 8.3 – Information Access Restriction

**Portfolio Disclaimer:** This is a fictional procedure developed for an educational portfolio scenario. It does not represent an approved or implemented procedure at a real organisation.
