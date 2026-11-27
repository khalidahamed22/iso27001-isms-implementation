# Security Incident Escalation Matrix

**Document ID:** MAT-001  
**Version:** 1.0  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Related Procedure:** PROC-008 – Information Security Incident Management Procedure

## 1. Purpose

This matrix establishes escalation requirements for information security incidents to ensure timely notification, appropriate decision-making and coordinated response.

## 2. Incident Severity Levels

| Severity | Description | Example |
|---|---|---|
| Critical | Confirmed or strongly suspected major compromise, significant data exposure or major business disruption | Production database breach or ransomware affecting critical services |
| High | Significant security incident with potential customer, financial or operational impact | Privileged account compromise |
| Medium | Limited incident requiring investigation and security team response | Phishing email with no confirmed execution |
| Low | Minor security event with limited or no confirmed impact | Blocked suspicious login attempt |

Severity must be reassessed as investigation evidence becomes available.

## 3. Escalation Matrix

| Severity | Initial Notification | Escalation To | Target Notification Time | Management Involvement |
|---|---|---|---|---|
| Critical | Immediately notify Information Security Manager | CTO and Executive Management | Immediately; target within 15 minutes of identification | Immediate |
| High | Notify Information Security Manager | IT Manager and relevant system owner | Target within 30 minutes | As required by impact |
| Medium | Notify Security Analyst / Security Manager | Relevant IT or department manager | Target within 4 hours | If escalation criteria are met |
| Low | Notify Security Team | Assigned operational owner | Target within 1 business day | Normally not required |

**Note:** These notification targets are proposed internal service targets for the fictional organisation. They are not ISO 27001-mandated timeframes or legal reporting deadlines.

## 4. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Employee / Reporter | Report suspected incidents promptly and preserve available information |
| Security Analyst | Record, triage, investigate and escalate incidents |
| Information Security Manager | Coordinate response, determine severity and manage escalation |
| IT Manager | Coordinate technical containment and recovery |
| System Owner | Assess impact on affected systems and business processes |
| CTO | Make senior technical and business decisions |
| Executive Management | Approve major business decisions and resource allocation |
| Legal / Data Protection Contact | Assess legal, regulatory and contractual notification obligations |

## 5. Mandatory Escalation Triggers

Escalation must occur when one or more of the following conditions apply:

- Suspected or confirmed unauthorised access to restricted information.
- Potential exposure of customer personal or financial information.
- Compromise of privileged accounts or production systems.
- Ransomware, destructive malware or widespread endpoint compromise.
- Significant interruption to customer-facing services.
- Suspected compromise involving a critical third-party provider.
- Potential legal, regulatory or contractual notification obligations.
- Incident impact exceeds the authority of the assigned response team.

## 6. External Notification

The Information Security Manager, with Legal and the relevant business owner, must assess whether customers, regulators, law enforcement, insurers or suppliers need to be notified.

External notifications must:

- Be based on verified facts.
- Follow applicable legal and contractual requirements.
- Be approved by authorised personnel.
- Be documented, including the decision not to notify where appropriate.

## 7. Escalation Records

The following information must be retained:

- Incident ID and severity.
- Date and time of detection.
- Date and time of each escalation.
- Person or team notified.
- Communication method.
- Decision or instruction received.
- Reason for escalation or non-escalation.
- Approval and notification records.

## 8. Review and Approval

This matrix must be reviewed annually or when organisational roles, incident response arrangements, legal requirements or business operations materially change.

| Approval Role | Name | Status |
|---|---|---|
| Information Security Manager | Pending | Pending |
| CTO | Pending | Pending |

**Portfolio Disclaimer:** This is a fictional escalation matrix created for simulated ISO 27001 implementation and portfolio demonstration. Notification targets and organisational roles are illustrative and require validation before real-world adoption.
