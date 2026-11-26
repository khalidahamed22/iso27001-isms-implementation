
# Information Security Risk Treatment Plan

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Document ID:** CL-ISMS-RT-001  
**Version:** 1.0  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Document Owner:** Information Security Manager  
**Applicable Standard:** ISO/IEC 27001:2022  
**Review Frequency:** Quarterly and following significant risk changes

---

## 1. Purpose

This document defines the proposed treatment actions for information security risks identified in the CloudLedger risk register.

The objective is to reduce information security risks to levels acceptable to the organisation while meeting applicable legal, regulatory and contractual obligations.

## 2. Risk Treatment Options

CloudLedger considers the following treatment options:

1. Risk modification: Implement controls to reduce likelihood or impact.
2. Risk avoidance: Discontinue activities that create unacceptable risks.
3. Risk sharing: Share selected consequences or responsibilities through contractual arrangements or insurance.
4. Risk retention: Formally accept the risk based on the organisation's acceptance criteria.

## 3. Risk Treatment Register

| Risk ID | Initial Score | Treatment Option | Proposed Treatment Actions | Relevant Annex A Controls | Responsible Owner |
|---|---:|---|---|---|---|
| RISK-001 | 20 | Modify | Apply least privilege, database access restrictions, encryption and periodic access reviews | 5.15, 5.18, 8.3, 8.24 | Head of Finance |
| RISK-002 | 15 | Modify | Implement application access restrictions, secure authentication and monitoring | 5.15, 8.3, 8.5, 8.16 | Data Protection Contact |
| RISK-003 | 12 | Modify | Restrict repository permissions, require code reviews and protect development environments | 8.4, 8.25, 8.28, 8.32 | Development Manager |
| RISK-004 | 20 | Modify | Establish secure cloud configurations, privileged access restrictions, configuration monitoring and cloud security reviews | 5.23, 8.2, 8.9, 8.16 | IT Manager |
| RISK-005 | 12 | Modify | Restrict HR system access, conduct access reviews and protect employee records | 5.15, 5.18, 8.3, 8.24 | HR Manager |
| RISK-006 | 20 | Modify | Enforce MFA, strengthen authentication, conduct awareness training and monitor suspicious login activity | 6.3, 8.5, 8.16 | IT Manager |
| RISK-007 | 12 | Modify | Protect security logs, restrict administrative access and establish log retention and monitoring | 8.15, 8.16, 8.17 | Security Manager |
| RISK-008 | 15 | Modify | Implement protected backups, backup monitoring and periodic restoration testing | 8.13, 5.30 | IT Manager |
| RISK-009 | 16 | Modify | Deploy endpoint protection, implement vulnerability management and apply security patches | 8.1, 8.7, 8.8 | IT Manager |
| RISK-010 | 15 | Modify | Store integration secrets securely, restrict access and rotate exposed credentials | 5.17, 8.3, 8.24 | Development Manager |
| RISK-011 | 12 | Modify | Apply role-based access, restrict sensitive ticket visibility and review permissions | 5.15, 5.18, 8.3 | Customer Support Manager |
| RISK-012 | 9 | Modify | Establish document version control, approval and periodic policy reviews | 5.1, 5.37, 7.5 | Information Security Manager |
| RISK-013 | 20 | Modify | Enforce MFA, protect authentication information and monitor account compromise indicators | 5.17, 8.5, 8.16 | IT Manager |
| RISK-014 | 15 | Modify | Introduce formal configuration change approval, privileged access restrictions and configuration monitoring | 8.2, 8.9, 8.32 | IT Manager |
| RISK-015 | 12 | Modify | Conduct supplier security assessments, review agreements and monitor supplier security performance | 5.19, 5.20, 5.21, 5.22 | Procurement Manager |

## 4. Risk Treatment Priorities

The initial treatment priorities are:

### Priority 1 – Critical Risks

- RISK-001: Customer financial database exposure.
- RISK-004: AWS production environment compromise.
- RISK-006: Employee credential compromise.
- RISK-013: Authentication credential compromise.

These risks require priority treatment decisions and management oversight.

### Priority 2 – High Risks

- RISK-002: Customer personal information exposure.
- RISK-003: Application source code modification.
- RISK-005: Employee information disclosure.
- RISK-007: Security log tampering.
- RISK-008: Backup unavailability.
- RISK-009: Endpoint malware infection.
- RISK-010: Payment integration credential exposure.
- RISK-011: Customer support information exposure.
- RISK-014: Unauthorised cloud configuration changes.
- RISK-015: Third-party supplier compromise.

### Priority 3 – Moderate Risks

- RISK-012: Outdated information security procedures.

This risk will be addressed through document control and communication improvements.

## 5. Treatment Implementation Requirements

Each treatment action must have:

- An assigned responsible owner.
- A defined implementation deadline.
- Required resources.
- Evidence of implementation.
- A method for assessing effectiveness.
- A reassessment of residual risk.

Implementation progress must be tracked by the Information Security Manager.

## 6. Residual Risk Assessment

Following implementation, each risk must be reassessed using the approved risk assessment methodology.

Residual risk is the risk remaining after the implemented controls and their effectiveness have been considered.

Residual risk scores must not be assumed or automatically reduced simply because a control has been selected.

The risk owner must review the remaining exposure and formally accept the residual risk where authorised.

## 7. Risk Acceptance and Approval

Risk owners are responsible for reviewing proposed treatment actions and remaining risks.

Executive Management must approve risk acceptance decisions that exceed delegated authority or fall outside the organisation's risk appetite.

No treatment action or residual risk acceptance is considered completed until appropriate evidence and approval records are available.

## 8. Monitoring and Review

The Information Security Manager will:

- Review treatment progress quarterly.
- Follow up overdue treatment actions.
- Escalate critical risks.
- Verify implementation evidence.
- Coordinate residual risk reassessments.
- Update the risk register when treatment changes risk exposure.

## 9. Approval

| Role | Responsibility | Status |
|---|---|---|
| Information Security Manager | Prepared by | Simulated |
| Risk Owners | Review treatment actions | Pending |
| Executive Management | Approval authority | Pending |

---

**Portfolio Disclaimer:** This is a simulated risk treatment plan for a fictional organisation. No real security controls have been implemented or independently verified.
