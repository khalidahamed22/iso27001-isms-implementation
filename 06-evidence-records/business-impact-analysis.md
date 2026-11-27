# Business Impact Analysis (BIA)

**Document ID:** BIA-001  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Confidential  
**Assessment Date:** 2026-11-27  
**Review Frequency:** Annually or following significant business changes

## 1. Purpose

The purpose of this Business Impact Analysis is to identify critical business processes, assess the potential consequences of disruption, and establish proposed recovery priorities.

The analysis supports business continuity and disaster recovery planning for CloudLedger's SaaS financial management platform.

## 2. Scope

This assessment covers the following business functions:

- SaaS application operations
- Customer financial data processing
- Cloud infrastructure and database services
- Customer support
- Identity and access management
- Software development and maintenance
- Security monitoring and incident response

## 3. Business Impact Assessment Methodology

Business disruption is assessed using the following impact categories:

| Impact Category | Assessment Considerations |
|---|---|
| Financial | Revenue loss, operational costs and compensation |
| Operational | Inability to deliver business services |
| Legal and Regulatory | Contractual, regulatory and legal consequences |
| Reputational | Customer trust and organisational reputation |
| Information Security | Confidentiality, integrity and availability of information |

Impact ratings:

| Rating | Description |
|---|---|
| Critical | Severe disruption with major business consequences |
| High | Significant disruption requiring urgent recovery |
| Medium | Manageable disruption with operational consequences |
| Low | Limited disruption with minimal business consequences |

## 4. Critical Business Process Assessment

| Process ID | Business Process | Process Owner | Supporting Systems | Business Impact | Criticality |
|---|---|---|---|---|---|
| BCP-001 | SaaS Application Operations | Head of Engineering | AWS, application servers | Customers cannot access the financial management platform | Critical |
| BCP-002 | Financial Data Processing | Head of Finance | Production database, application | Financial transactions may be delayed or unavailable | Critical |
| BCP-003 | Cloud Infrastructure Management | Cloud Administrator | AWS infrastructure | Infrastructure failure may affect multiple services | Critical |
| BCP-004 | Identity and Access Management | IT Manager | Identity platform, IAM | Users may be unable to authenticate or access authorised services | High |
| BCP-005 | Customer Support | Customer Support Manager | Support platform, email | Customer enquiries and incident communication may be delayed | High |
| BCP-006 | Security Monitoring | Information Security Manager | Logging, monitoring platform | Security events may go undetected or response may be delayed | High |
| BCP-007 | Software Development and Maintenance | Head of Engineering | Source code repository, development environment | Development and maintenance activities may be delayed | Medium |

## 5. Maximum Tolerable Period of Disruption

The Maximum Tolerable Period of Disruption (MTPD) represents the proposed maximum period a business process can remain disrupted before the consequences become unacceptable.

| Process ID | Business Process | Proposed MTPD |
|---|---|---|
| BCP-001 | SaaS Application Operations | 8 hours |
| BCP-002 | Financial Data Processing | 8 hours |
| BCP-003 | Cloud Infrastructure Management | 8 hours |
| BCP-004 | Identity and Access Management | 12 hours |
| BCP-005 | Customer Support | 24 hours |
| BCP-006 | Security Monitoring | 8 hours |
| BCP-007 | Software Development and Maintenance | 72 hours |

These are proposed planning assumptions requiring validation by process owners and management.

## 6. Proposed Recovery Objectives

**Recovery Time Objective (RTO):** The target time within which a business process or service should be restored following disruption.

**Recovery Point Objective (RPO):** The maximum targeted period of data loss measured in time.

| Process ID | Business Process | Proposed RTO | Proposed RPO |
|---|---|---|---|
| BCP-001 | SaaS Application Operations | 4 hours | 1 hour |
| BCP-002 | Financial Data Processing | 4 hours | 15 minutes |
| BCP-003 | Cloud Infrastructure Management | 4 hours | 1 hour |
| BCP-004 | Identity and Access Management | 8 hours | 4 hours |
| BCP-005 | Customer Support | 12 hours | 8 hours |
| BCP-006 | Security Monitoring | 4 hours | 1 hour |
| BCP-007 | Software Development and Maintenance | 24 hours | 24 hours |

These are proposed targets, not demonstrated recovery capabilities. They must be assessed against technical feasibility, costs, dependencies and business requirements.

## 7. Critical Dependencies

| Dependency | Related Processes | Potential Impact |
|---|---|---|
| AWS Cloud Infrastructure | BCP-001, BCP-002, BCP-003 | Application and infrastructure unavailability |
| Production Database | BCP-001, BCP-002 | Loss of access to customer financial records |
| Identity Platform | BCP-001, BCP-004 | Authentication and access disruption |
| Network Connectivity | BCP-001, BCP-003, BCP-005 | Service and communication disruption |
| Backup Services | BCP-001, BCP-002, BCP-003 | Inability to recover data and systems |
| Logging and Monitoring | BCP-006 | Reduced security visibility |
| Source Code Repository | BCP-007 | Development and maintenance disruption |

## 8. Recovery Priorities

Based on the preliminary assessment, recovery should generally follow this sequence:

1. Restore essential cloud infrastructure and connectivity.
2. Restore identity and access services required for secure administration.
3. Restore production databases and critical application services.
4. Validate financial data integrity and application functionality.
5. Restore security monitoring and logging capabilities.
6. Restore customer support operations and communication channels.
7. Resume normal software development and maintenance activities.

Actual recovery order must account for technical dependencies and the approved disaster recovery strategy.

## 9. Assessment Limitations

- Impact ratings are preliminary simulated assessments.
- RTO and RPO values have not been approved by process owners.
- No business continuity exercise has been conducted.
- No disaster recovery capability has been technically tested.
- Third-party recovery commitments have not been independently verified.
- Resource availability and recovery costs require further assessment.

## 10. Review and Approval

| Role | Responsibility | Approval Status |
|---|---|---|
| Head of Engineering | Validate technology recovery requirements | Pending |
| Head of Finance | Validate financial process impact | Pending |
| Information Security Manager | Review information security impacts | Pending |
| Senior Management | Approve business recovery priorities | Pending |

## 11. Conclusion

This Business Impact Analysis establishes a preliminary understanding of CloudLedger's critical business processes, disruption impacts and proposed recovery objectives.

The results will support the development of the Business Continuity Plan and Disaster Recovery Plan.

All recovery targets remain proposed until validated and approved by the relevant business owners and management.

## 12. Portfolio Disclaimer

This document is a fictional Business Impact Analysis prepared for a simulated ISO/IEC 27001:2022 implementation portfolio. No real business impact assessment or management approval has occurred.
