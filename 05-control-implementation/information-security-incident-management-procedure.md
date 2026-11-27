# Information Security Incident Management Procedure

**Document ID:** PROC-008  
**Document Owner:** Information Security Manager  
**Approved By:** Head of Technology  
**Version:** 1.0  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Review Frequency:** Annually or following a significant security incident

## 1. Purpose

This procedure establishes how CloudLedger Technologies (Pvt) Ltd identifies, reports, assesses, responds to and learns from information security events and incidents.

Its objective is to minimise the impact of security incidents on organisational information, systems, customers and business operations.

## 2. Scope

This procedure applies to information security events and incidents affecting:

- Cloud infrastructure and production systems.
- Customer information and financial records.
- Employee endpoints and corporate devices.
- Application source code and development environments.
- Identity and access management systems.
- Network infrastructure.
- Third-party services and integrations.
- Confidential and Restricted information.

It applies to all employees, contractors and authorised third parties who identify or handle security incidents involving CloudLedger.

## 3. Definitions

**Security Event:** An observed occurrence that may indicate a security issue or control failure.

**Security Incident:** An event, or series of events, that compromises or threatens information security and requires a coordinated response.

**Incident Response:** Activities performed to detect, assess, contain, eradicate and recover from a security incident.

**Near Miss:** An event that could have caused harm but did not result in an actual security incident.

## 4. Responsibilities

| Role | Responsibility |
|---|---|
| All Employees | Report suspected security events promptly. |
| Security Analyst | Monitor alerts, perform initial triage and document findings. |
| Information Security Manager | Coordinate incident response and assess severity. |
| IT Manager | Coordinate infrastructure containment and recovery. |
| Development Manager | Investigate application and software-related incidents. |
| Data Protection Contact | Assess potential personal data breaches and applicable notification obligations. |
| Management | Provide resources and approve major response decisions. |
| Supplier Owner | Coordinate incidents involving third-party services. |

## 5. Incident Identification and Reporting

Security events may be identified through:

- Security monitoring alerts.
- Endpoint detection systems.
- Firewall and network logs.
- Suspicious authentication activity.
- Employee reports.
- Vulnerability assessments.
- Customer complaints.
- Supplier notifications.
- Unusual application behaviour.

Employees must report suspected incidents through the approved internal reporting channel.

Reports should include:

- Date and time identified.
- Reporting individual.
- Affected system or asset.
- Description of the event.
- Available evidence.
- Potential business impact.

Employees must avoid deleting evidence or independently investigating beyond their authority.

## 6. Initial Triage and Assessment

The Security Analyst performs initial triage to determine whether the reported event requires escalation.

The assessment should consider:

1. Whether the activity is suspicious.
2. Whether a security control may have failed.
3. Which assets and information may be affected.
4. Whether unauthorised access is suspected.
5. Whether confidentiality, integrity or availability is affected.
6. Whether the incident is ongoing.
7. Whether immediate containment is necessary.

Events confirmed as incidents must be recorded in the Incident Register.

Events determined to be false positives or non-incidents must still be documented where appropriate, including the rationale for closure.

## 7. Incident Classification

CloudLedger proposes the following severity levels:

| Severity | Description | Examples |
|---|---|---|
| Critical | Major compromise or significant disruption affecting critical services or highly sensitive information | Confirmed production compromise or widespread customer data breach |
| High | Significant security incident affecting important systems or sensitive information | Privileged account compromise or malware affecting business systems |
| Medium | Limited incident requiring investigation and corrective action | Unauthorised access attempt with limited impact |
| Low | Minor security event with limited or no demonstrated impact | Suspicious activity blocked by an existing control |

Severity must be determined using actual impact, scope, urgency and business risk. An alert alone does not automatically establish an incident.

## 8. Incident Response Process

### 8.1 Preparation

The organisation must maintain:

- Incident response responsibilities.
- Reporting channels.
- Escalation contacts.
- Relevant technical tools.
- Evidence handling arrangements.
- Communication procedures.
- Recovery arrangements.

### 8.2 Detection and Analysis

The Security Analyst must:

1. Review the available alert or report.
2. Identify affected assets and accounts.
3. Correlate relevant security logs.
4. Determine whether the event is a confirmed incident.
5. Assign an initial severity.
6. Escalate according to the incident's potential impact.

### 8.3 Containment

The response team must take appropriate action to limit the impact.

Examples include:

- Disabling compromised accounts.
- Revoking compromised credentials or tokens.
- Isolating affected endpoints.
- Blocking malicious network indicators.
- Restricting access to affected services.
- Temporarily disabling affected integrations.

Containment decisions must consider evidence preservation and business impact.

### 8.4 Eradication

The response team must identify and remove the cause of the incident.

Activities may include:

- Removing malware.
- Closing exploited vulnerabilities.
- Removing unauthorised accounts.
- Resetting compromised credentials.
- Correcting insecure configurations.
- Removing unauthorised access mechanisms.

### 8.5 Recovery

Systems may be restored after the response team confirms that appropriate security checks have been completed.

Recovery activities should include:

- Restoring affected services.
- Verifying system integrity.
- Monitoring for recurring suspicious activity.
- Confirming that security controls are functioning.
- Obtaining appropriate business owner approval.

### 8.6 Post-Incident Review

Following significant incidents, the Information Security Manager must coordinate a review.

The review should document:

- Incident timeline.
- Root cause.
- Business impact.
- Response effectiveness.
- Lessons learned.
- Control weaknesses.
- Corrective actions.
- Risk register updates where required.

## 9. Evidence Handling

Incident evidence must be protected against unauthorised modification, loss or disclosure.

Evidence may include:

- Authentication logs.
- Firewall and network logs.
- Endpoint security alerts.
- System snapshots.
- Relevant application logs.
- Email headers and suspicious attachments.
- Investigation notes.
- Screenshots and configuration exports.

Evidence collection must be documented, including the collector, collection date, source and handling details.

Where forensic investigation or legal proceedings may be involved, appropriate evidence preservation and chain-of-custody arrangements must be followed.

## 10. Communication and Escalation

Incidents must be escalated to appropriate management and relevant stakeholders according to severity.

Where an incident may involve personal data, the Data Protection Contact must assess applicable legal and contractual notification requirements.

External communications must be authorised by management and coordinated with relevant legal or compliance personnel.

Third-party incidents must be coordinated through the supplier management process.

## 11. Incident Records and Reporting

The organisation must maintain:

- Incident Register.
- Incident Reports.
- Investigation Records.
- Evidence Collection Records.
- Incident Communication Records.
- Corrective Action Records.
- Post-Incident Review Reports.

Incident records must be access-controlled and retained according to applicable requirements.

## 12. Related ISO/IEC 27001:2022 Controls

- A.5.24 – Information security incident management planning and preparation.
- A.5.25 – Assessment and decision on information security events.
- A.5.26 – Response to information security incidents.
- A.5.27 – Learning from information security incidents.
- A.5.28 – Collection of evidence.
- A.6.8 – Information security event reporting.
- A.8.15 – Logging.
- A.8.16 – Monitoring activities.

## 13. Review and Approval

| Approval Role | Name | Status |
|---|---|---|
| Information Security Manager | Simulated role | Pending |
| Head of Technology | Simulated role | Pending |

---

**Portfolio Disclaimer:** This is a simulated incident management procedure for the fictional organisation CloudLedger Technologies (Pvt) Ltd. It defines a proposed incident response process and does not represent an actual security incident or operational response exercise.
