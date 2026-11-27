# Supplier Security Review Procedure

**Document ID:** PROC-005  
**Document Owner:** Information Security Manager  
**Approved By:** Head of Technology  
**Version:** 1.0  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Review Frequency:** Annually or following significant supplier changes

---

## 1. Purpose

This procedure establishes how CloudLedger Technologies (Pvt) Ltd identifies, assesses, monitors and reviews information security risks associated with third-party suppliers.

It ensures that supplier services do not introduce unacceptable risks to the confidentiality, integrity and availability of CloudLedger information and systems.

## 2. Scope

This procedure applies to all third-party suppliers that provide services, technology, infrastructure or support to CloudLedger.

Examples include:

- Cloud infrastructure providers (AWS).
- Payment gateway providers.
- Software-as-a-Service (SaaS) providers.
- Identity and authentication providers.
- Source code repository providers.
- Backup and security service providers.
- External IT support providers.

## 3. Responsibilities

| Role | Responsibility |
|---|---|
| Procurement Manager | Maintains the supplier register and coordinates supplier reviews. |
| Information Security Manager | Oversees supplier security assessments and evaluates security risks. |
| IT Manager | Reviews technical dependencies, cloud configurations and supplier access. |
| Legal / Compliance Representative | Reviews contractual, regulatory and data protection requirements. |
| Supplier Owner | Monitors supplier performance and reports significant changes or incidents. |
| Risk Owner | Reviews supplier-related risks and approves treatment or residual risk acceptance. |

## 4. Supplier Security Review Process

### 4.1 Supplier Identification and Registration

Before a supplier is engaged, the responsible department must:

1. Identify the business purpose of the supplier service.
2. Determine what information and systems the supplier may access or support.
3. Identify whether customer, employee or financial information is involved.
4. Record the supplier in the Supplier Register.
5. Assign a supplier owner.
6. Determine the supplier's initial risk classification.

The supplier register must contain, at minimum:

- Supplier ID and name.
- Service provided.
- Business owner.
- Information or systems involved.
- Risk classification.
- Assessment date.
- Next review date.

### 4.2 Initial Security Assessment

The Information Security Manager coordinates a security assessment before onboarding high-risk suppliers.

The assessment may include:

- Information security policies and certifications.
- Independent assurance reports, where available.
- Access control and authentication practices.
- Encryption and data protection arrangements.
- Vulnerability and patch management.
- Security incident notification procedures.
- Backup and disaster recovery arrangements.
- Business continuity capabilities.
- Subcontractor and fourth-party dependencies.
- Data location, retention and deletion arrangements.

The Supplier Security Assessment Questionnaire may be used to collect information.

Supplier responses must be supported by appropriate evidence where necessary. Unsupported statements must not automatically be treated as verified security controls.

### 4.3 Supplier Risk Evaluation

The Information Security Manager evaluates the information collected and identifies potential risks.

The assessment considers:

- Confidentiality, integrity and availability impacts.
- Supplier access to CloudLedger information.
- Criticality of the supplied service.
- Regulatory and contractual obligations.
- Supplier security assurance.
- Service availability and recovery capabilities.
- Dependencies on subcontractors or other providers.

Identified risks must be recorded in the Third-Party Risk Assessment Register.

Risk owners must review and validate the assessment.

### 4.4 Contractual Security Requirements

Before a supplier is approved, relevant security requirements must be considered in the agreement.

Depending on the service, requirements may include:

- Confidentiality obligations.
- Data protection responsibilities.
- Access control requirements.
- Security incident notification timelines.
- Cooperation during security investigations.
- Availability and recovery commitments.
- Right to request relevant security assurance.
- Subcontractor security requirements.
- Data return and secure deletion upon termination.

Legal and compliance representatives must review relevant contractual requirements.

### 4.5 Ongoing Supplier Monitoring

Supplier security must be monitored throughout the relationship.

Monitoring activities may include:

1. Reviewing updated security certifications and assurance reports.
2. Checking relevant supplier security notifications.
3. Reviewing changes to supplier services and security responsibilities.
4. Monitoring supplier incidents and service disruptions.
5. Reviewing contractual and regulatory changes.
6. Following up on outstanding security findings.
7. Reassessing supplier risks when significant changes occur.

For cloud services, the IT Manager must also review CloudLedger's responsibilities under the applicable cloud service model.

### 4.6 Periodic Supplier Reviews

Supplier reviews must be performed according to risk classification.

| Supplier Risk Level | Minimum Review Frequency |
|---|---|
| Critical | Quarterly |
| High | Every six months |
| Medium | Annually |
| Low | Every two years |

These are proposed internal review intervals for the fictional organisation, not ISO 27001-mandated frequencies.

Reviews must consider whether the supplier's service, access, risks and security assurance remain acceptable.

### 4.7 Findings and Corrective Actions

Where a supplier assessment identifies security weaknesses:

1. Record the finding.
2. Assess its potential impact on CloudLedger.
3. Assign a responsible risk owner.
4. Determine appropriate treatment actions.
5. Agree a target completion date.
6. Track progress until closure.
7. Reassess residual risk after treatment.

If a supplier cannot provide requested evidence, record the information as **Not Verified** or **Not Received**, as appropriate.

Do not mark a supplier control as implemented or effective without sufficient supporting evidence.

### 4.8 Supplier Changes and Termination

Supplier reviews must also be triggered by:

- Significant changes to services.
- Changes in data processing arrangements.
- Security incidents.
- Changes in subcontractors.
- Changes in hosting or data locations.
- Contract renewal or termination.

When a supplier relationship ends, CloudLedger must consider:

- Revocation of supplier access.
- Return or secure deletion of CloudLedger information.
- Recovery or transfer of business data.
- Termination of credentials and integrations.
- Retention of relevant contractual and security records.

## 5. Required Records and Evidence

The following records must be maintained:

| Record | Reference |
|---|---|
| Supplier Register | `06-evidence-records/supplier-register.csv` |
| Supplier Security Assessment Questionnaire | `06-evidence-records/supplier-security-assessment-questionnaire.md` |
| Third-Party Risk Assessment Register | `06-evidence-records/third-party-risk-assessment-register.csv` |
| Supplier Security Assessment Report | `06-evidence-records/supplier-security-assessment-report.md` |
| AWS Shared Responsibility Matrix | `05-control-implementation/aws-shared-responsibility-matrix.md` |
| Supplier Review Records | To be maintained in the evidence records directory |
| Supplier Contracts and Agreements | To be maintained in the approved document repository |

## 6. Exceptions

Any exception to this procedure must be documented, justified, assessed for risk and approved by the appropriate management authority.

High or critical supplier risks must be escalated to senior management where necessary.

## 7. Related ISO/IEC 27001:2022 Controls

- **A.5.19** – Information security in supplier relationships.
- **A.5.20** – Addressing information security within supplier agreements.
- **A.5.21** – Managing information security in the ICT supply chain.
- **A.5.22** – Monitoring, review and change management of supplier services.
- **A.5.23** – Information security for use of cloud services.

## 8. Review and Approval

This procedure must be reviewed annually or when significant changes occur in supplier relationships, technology or applicable requirements.

| Approval Role | Name | Status |
|---|---|---|
| Information Security Manager | Simulated role | Pending |
| Head of Technology | Simulated role | Pending |

---

**Portfolio Disclaimer:** This is a simulated supplier security procedure developed for the fictional organisation CloudLedger Technologies (Pvt) Ltd. It demonstrates a proposed ISO/IEC 27001:2022 implementation approach and does not represent an actual supplier assessment or operational implementation.
