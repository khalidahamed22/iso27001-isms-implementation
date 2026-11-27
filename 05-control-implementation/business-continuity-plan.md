# Business Continuity Plan (BCP)

**Document ID:** BCP-001  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Confidential  
**Plan Owner:** IT Manager  
**Approval Authority:** Senior Management  
**Review Frequency:** Annually or following a significant disruption or organisational change

## 1. Purpose

This Business Continuity Plan defines the actions and responsibilities required to maintain or restore critical business operations during disruptive events.

The plan supports the organisation's ability to continue delivering essential SaaS financial management services while protecting customer information and meeting relevant business obligations.

## 2. Scope

This plan covers:

- SaaS application operations.
- Customer financial data processing.
- AWS cloud infrastructure.
- Identity and access management.
- Customer support operations.
- Security monitoring and incident response.
- Critical employees and third-party service providers.

## 3. Plan Activation Criteria

The plan may be activated when a disruption significantly affects or threatens critical business operations.

Examples include:

| Scenario | Potential Business Impact | Activation Consideration |
|---|---|---|
| AWS infrastructure outage | Application and database unavailability | Critical services cannot be restored through normal operational procedures |
| Ransomware or major cyberattack | Systems and information may become unavailable or compromised | Security incident requires coordinated business continuity response |
| Production database failure | Customer financial data processing disrupted | Database recovery exceeds normal operational capability |
| Network connectivity failure | Employees or customers cannot access services | Alternative connectivity or recovery arrangements are required |
| Critical supplier outage | Essential third-party service unavailable | Business operations are materially affected |
| Office or facility disruption | Staff cannot access normal working facilities | Remote-working arrangements are required |

Activation shall be based on the severity, duration and business impact of the disruption.

## 4. Activation and Escalation

The following process shall be followed:

1. Identify and report the disruption.
2. Perform an initial impact and severity assessment.
3. Notify the IT Manager and Information Security Manager.
4. Determine whether normal incident handling is sufficient.
5. Escalate to Senior Management when continuity activation is necessary.
6. Formally activate the relevant continuity arrangements.
7. Notify affected stakeholders.
8. Coordinate recovery and business operations.

**Activation Authority:** Senior Management or an authorised delegate.

**Operational Coordinator:** IT Manager.

## 5. Business Continuity Roles

| Role | Responsibilities |
|---|---|
| Senior Management | Authorise plan activation and provide strategic direction |
| IT Manager | Coordinate continuity activities and technical recovery |
| Information Security Manager | Assess security implications and coordinate incident response |
| Cloud Administrator | Support cloud infrastructure recovery |
| Head of Engineering | Coordinate application recovery and technical validation |
| Head of Finance | Assess financial process disruption and validate restored financial operations |
| Customer Support Manager | Coordinate customer communication and support continuity |
| Employees | Follow continuity instructions and report operational issues |

## 6. Business Continuity Strategies

### 6.1 Cloud Infrastructure Disruption

- Identify the affected AWS services.
- Assess whether the disruption is provider-related or caused by CloudLedger configuration.
- Contact the relevant cloud provider through approved support channels.
- Evaluate available recovery options.
- Restore critical infrastructure according to the approved recovery strategy.
- Validate application availability and security before resuming normal operations.

### 6.2 Cybersecurity Incident

- Activate the Information Security Incident Management Procedure.
- Contain affected systems where necessary.
- Preserve relevant evidence.
- Assess whether customer information or critical services are affected.
- Coordinate secure recovery with technical teams.
- Obtain appropriate security validation before restoring affected services.

### 6.3 Database Disruption

- Assess the database failure and its impact.
- Identify the latest suitable backup or recovery point.
- Obtain recovery authorisation.
- Restore the database using approved procedures.
- Validate financial data integrity.
- Obtain business owner acceptance before resuming affected operations.

### 6.4 Office or Facility Disruption

- Notify affected employees.
- Activate approved remote-working arrangements.
- Confirm access to required systems and communication channels.
- Apply existing access control and remote access security requirements.
- Coordinate employee availability and essential business activities.

### 6.5 Third-Party Service Disruption

- Contact the affected provider.
- Assess the impact on dependent business processes.
- Review contractual support and recovery commitments.
- Identify available alternative arrangements.
- Escalate prolonged disruptions to management.

## 7. Communication and Notification

Communication shall be coordinated through approved channels.

| Stakeholder | Communication Responsibility | Information |
|---|---|---|
| Senior Management | IT Manager | Disruption, impact and recovery status |
| Employees | Department Managers | Operational instructions and working arrangements |
| Customers | Customer Support Manager | Service availability and relevant updates |
| Cloud Providers | Cloud Administrator | Technical incident and support requirements |
| Business Partners | Relevant Process Owner | Impact on dependent services |
| Regulators or Authorities | Authorised Management Representative | Notifications where legally or contractually required |

Communications must be accurate, authorised and consistent with applicable confidentiality and notification requirements.

## 8. Recovery Priorities

The proposed recovery sequence is based on BIA-001 and must account for technical dependencies.

| Priority | Business Service | Proposed RTO | Proposed RPO |
|---|---|---|---|
| 1 | SaaS Application Operations | 4 hours | 1 hour |
| 2 | Financial Data Processing | 4 hours | 15 minutes |
| 3 | Cloud Infrastructure Management | 4 hours | 1 hour |
| 4 | Security Monitoring | 4 hours | 1 hour |
| 5 | Identity and Access Management | 8 hours | 4 hours |
| 6 | Customer Support | 12 hours | 8 hours |
| 7 | Software Development and Maintenance | 24 hours | 24 hours |

These targets are proposed planning objectives, not verified recovery capabilities.

## 9. Continuity Resource Requirements

The organisation should identify and maintain access to:

- Critical technical personnel.
- Approved administrative access.
- Cloud provider support arrangements.
- Protected backup copies.
- Secure communication channels.
- Recovery documentation.
- Alternative working arrangements.
- Relevant supplier contacts.
- Required hardware and software resources.

## 10. Return to Normal Operations

Before normal operations resume:

1. Confirm critical services are operational.
2. Validate restored information and data integrity.
3. Confirm security controls are functioning.
4. Verify access permissions.
5. Obtain relevant business owner acceptance.
6. Notify affected stakeholders.
7. Record recovery activities and outstanding issues.
8. Conduct a post-disruption review.

## 11. Testing and Maintenance

The plan shall be reviewed and tested periodically.

Testing may include:

- Tabletop continuity exercises.
- Communication and escalation exercises.
- Remote-working readiness checks.
- Cloud recovery exercises.
- Backup restoration validation.

Identified weaknesses shall be recorded and tracked through corrective action processes.

## 12. Related Documents

- Business Continuity Policy (POL-005)
- Business Impact Analysis (BIA-001)
- Disaster Recovery Plan
- Backup and Recovery Procedure (PROC-007)
- Information Security Incident Management Procedure (PROC-008)
- Incident Escalation Matrix (MAT-001)
- Backup Schedule Register
- Backup Restoration Test Report

## 13. Approval

| Role | Approval Status |
|---|---|
| IT Manager | Pending |
| Information Security Manager | Pending |
| Senior Management | Pending |

**Plan Activation Status:** Not Activated

## 14. Portfolio Disclaimer

This is a fictional Business Continuity Plan prepared for a simulated ISO/IEC 27001:2022 implementation portfolio. It has not been approved, activated or tested by a real organisation. All recovery targets are proposed planning assumptions.
