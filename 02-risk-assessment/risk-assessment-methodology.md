
# Information Security Risk Assessment Methodology

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Document ID:** CL-ISMS-RA-001  
**Version:** 1.0  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Document Owner:** Information Security Manager  
**Applicable Standard:** ISO/IEC 27001:2022  
**Review Frequency:** Annually or following significant changes

---

## 1. Purpose

This methodology establishes a consistent approach for identifying, analysing and evaluating information security risks affecting CloudLedger Technologies.

It supports the organisation's Information Security Management System (ISMS) and addresses the requirements of ISO/IEC 27001:2022 Clause 6.1.2.

## 2. Scope

This methodology applies to:

- Information assets within the ISMS scope.
- Cloud infrastructure and hosted applications.
- Employee and customer information.
- Business processes and supporting technologies.
- Third-party services and supplier relationships.
- Physical and logical information processing environments.

## 3. Risk Assessment Responsibilities

| Role | Responsibility |
|---|---|
| Executive Management | Approves risk acceptance criteria and significant risk decisions |
| Information Security Manager | Coordinates risk assessments and maintains the risk register |
| Risk Owner | Owns identified risks and approves treatment decisions within delegated authority |
| IT Manager | Provides technical information and implements assigned treatments |
| Process Owners | Identify business risks and assess operational impacts |
| Employees | Report security weaknesses and potential incidents |

## 4. Risk Assessment Process

CloudLedger uses the following assessment stages:

1. Identify information assets and business processes.
2. Identify threats that could affect those assets.
3. Identify vulnerabilities or weaknesses that threats could exploit.
4. Identify potential information security consequences.
5. Estimate likelihood and impact.
6. Calculate and evaluate risk levels.
7. Assign risk owners.
8. Record assessment results in the risk register.

## 5. Risk Identification

Risk identification considers threats affecting the confidentiality, integrity and availability of information.

Examples include:

| Threat | Potential Vulnerability | Possible Consequence |
|---|---|---|
| Ransomware | Inadequate endpoint protection or recovery controls | Business disruption and data unavailability |
| Phishing | Insufficient awareness or weak authentication | Account compromise |
| Cloud misconfiguration | Incorrect storage permissions | Unauthorised disclosure of customer information |
| Insider threat | Excessive privileges or inadequate monitoring | Unauthorised data access |
| Hardware failure | Inadequate redundancy | Service interruption |
| Supplier compromise | Insufficient supplier security oversight | Exposure of organisational information |

## 6. Risk Analysis Method

Each identified risk is evaluated using two factors:

- Likelihood: The estimated probability of the risk scenario occurring within the assessment period.
- Impact: The estimated severity of the consequences if the scenario occurs.

### 6.1 Likelihood Scale

| Score | Rating | Description |
|---|---|---|
| 1 | Rare | Exceptional circumstances; highly unlikely |
| 2 | Unlikely | Could occur, but not expected |
| 3 | Possible | May occur under certain conditions |
| 4 | Likely | Expected to occur in many circumstances |
| 5 | Almost Certain | Expected to occur frequently or imminently |

### 6.2 Impact Scale

Impact is assessed against confidentiality, integrity, availability, financial loss, legal or contractual obligations, and reputational consequences.

Use the highest applicable impact rating rather than averaging the different dimensions.

| Score | Rating | Description |
|---|---|---|
| 1 | Insignificant | Minimal operational effect; no meaningful information exposure |
| 2 | Minor | Limited disruption or low-level information security impact |
| 3 | Moderate | Noticeable business disruption or limited sensitive information exposure |
| 4 | Major | Significant service disruption, substantial data exposure or serious compliance consequences |
| 5 | Severe | Critical business disruption, extensive sensitive data exposure or potentially severe legal and financial consequences |

## 7. Risk Scoring

The organisation calculates the risk score using:

**Risk Score = Likelihood × Impact**

The possible score ranges from 1 to 25.

### 7.1 Risk Evaluation Matrix

| Likelihood / Impact | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| 5 – Almost Certain | 5 | 10 | 15 | 20 | 25 |
| 4 – Likely | 4 | 8 | 12 | 16 | 20 |
| 3 – Possible | 3 | 6 | 9 | 12 | 15 |
| 2 – Unlikely | 2 | 4 | 6 | 8 | 10 |
| 1 – Rare | 1 | 2 | 3 | 4 | 5 |

## 8. Risk Acceptance Criteria

CloudLedger adopts the following initial risk classification thresholds.

| Risk Score | Risk Level | Required Action |
|---|---|---|
| 1–4 | Low | May be accepted by the authorised risk owner |
| 5–9 | Moderate | Document and monitor; acceptance requires risk owner approval |
| 10–16 | High | Risk treatment plan required; formal management oversight |
| 17–25 | Critical | Immediate escalation and priority treatment decision |

These thresholds are proposed organisational criteria for this simulated case study, not thresholds prescribed by ISO 27001.

Risk acceptance must consider legal obligations, contractual requirements, business impact and management risk appetite. A legal or contractual obligation cannot be disregarded merely because a numerical risk score is low.

## 9. Risk Ownership and Approval

Every risk recorded in the risk register must have:

- Unique risk identification number.
- Description of the risk scenario.
- Associated information asset or business process.
- Identified threat and vulnerability.
- Likelihood and impact scores.
- Calculated risk score and classification.
- Assigned risk owner.
- Risk treatment decision.
- Approval or acceptance record, where applicable.

Risk owners must be authorised to make decisions within the organisation's defined risk acceptance authority.

## 10. Risk Assessment Review

Risk assessments must be reviewed:

- At least annually.
- Following significant changes to systems or business operations.
- Following major security incidents.
- When new threats or vulnerabilities are identified.
- When legal, regulatory or contractual requirements change.
- When supplier or cloud service arrangements change.

## 11. Risk Assessment Records

The following records will be maintained:

- Information asset register.
- Information security risk register.
- Risk assessment and evaluation records.
- Risk owner assignments.
- Risk acceptance approvals.
- Risk assessment review history.

## 12. Methodology Review and Approval

The Information Security Manager is responsible for reviewing this methodology.

Executive Management is responsible for approving the organisational risk acceptance criteria.

| Role | Responsibility | Status |
|---|---|---|
| Information Security Manager | Prepared by | Simulated |
| Executive Management | Approval authority | Pending |

---

**Portfolio Disclaimer:** This methodology is designed for a fictional organisation as an educational implementation exercise. Risk scores, thresholds and assessment results are simulated.
