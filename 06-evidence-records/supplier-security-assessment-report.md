
# Supplier Security Assessment Report

**Report ID:** SSAR-001  
**Supplier:** Amazon Web Services (AWS)  
**Supplier ID:** SUP-001  
**Service Assessed:** Cloud Infrastructure and Hosting  
**Assessment Date:** 2026-11-27  
**Assessment Owner:** Information Security Manager  
**Supplier Risk Level:** Critical  
**Assessment Status:** Simulated – Evidence Not Verified  
**Classification:** Confidential  

## 1. Executive Summary

CloudLedger Technologies (Pvt) Ltd relies on AWS cloud infrastructure to host its production SaaS platform and customer information.

Due to the criticality of this service and the sensitivity of the information processed, AWS has been classified as a Critical supplier in the supplier register.

A supplier security assessment questionnaire was prepared to identify the security requirements and supporting evidence that should be reviewed.

However, no actual supplier documentation, independent assurance reports, contractual records or technical evidence were obtained or examined for this portfolio exercise.

Therefore, the assessment cannot conclude that AWS security controls are effective or ineffective.

## 2. Assessment Objectives

The objectives are to:

- Identify security risks associated with the cloud service.
- Evaluate the supplier assurance evidence required.
- Understand relevant shared responsibility arrangements.
- Identify potential gaps requiring further investigation.
- Recommend supplier risk treatment activities.
- Support management decisions concerning supplier risk.

## 3. Assessment Scope

The assessment considers the following areas:

| Assessment Area | Review Focus |
|---|---|
| Security Governance | Security policies and responsibilities |
| Identity and Access Management | Authentication, authorisation and privileged access |
| Data Protection | Encryption, data handling and deletion |
| Infrastructure Security | Vulnerability management, patching and network security |
| Logging and Monitoring | Security event collection and monitoring |
| Incident Management | Incident response and customer notification |
| Business Continuity | Backup, recovery and service availability |
| Supplier Management | Subcontractors and supply chain security |
| Compliance Assurance | Independent assurance and contractual obligations |

## 4. Evidence Reviewed

| Evidence Reference | Evidence Description | Review Status |
|---|---|---|
| SSAQ-001 | Supplier Security Assessment Questionnaire | Prepared – No supplier responses received |
| SUP-001 | Supplier Register Entry | Reviewed as a simulated portfolio record |
| TPR-001 | Third-Party Risk Assessment Register | Reviewed as a simulated risk record |

No external AWS evidence was reviewed.

## 5. Assessment Findings

### Finding 1 – Cloud Security Assurance Not Verified

**Finding ID:** SSAR-F01  
**Risk:** Cloud infrastructure compromise or misconfiguration.

**Observation:**

CloudLedger depends on AWS infrastructure for its production environment. The assessment has not examined supplier assurance documentation or CloudLedger's actual cloud configuration.

**Potential Impact:**

Unauthorised access, data exposure, service disruption or compromise of production resources.

**Recommendation:**

Obtain relevant AWS assurance documentation and assess CloudLedger's own cloud configuration against its security responsibilities.

**Related Risk:** TPR-001

**Status:** Pending Evidence Collection

### Finding 2 – Shared Responsibility Requires Validation

**Finding ID:** SSAR-F02  
**Risk:** Security responsibilities may be misunderstood or inadequately implemented.

**Observation:**

Cloud security responsibilities are divided between the cloud provider and customer according to the services used. The applicable responsibility allocation has not been documented or validated in this simulated assessment.

**Potential Impact:**

Security gaps involving identity management, data protection, configuration, logging or incident response.

**Recommendation:**

Develop a shared responsibility matrix identifying AWS responsibilities and CloudLedger responsibilities for each relevant cloud service.

**Related Risk:** TPR-001

**Status:** Pending Validation

### Finding 3 – Incident Notification Arrangements Not Verified

**Finding ID:** SSAR-F03  
**Risk:** Delayed awareness of a supplier incident affecting CloudLedger.

**Observation:**

No contractual incident notification terms or relevant incident communication arrangements were examined.

**Potential Impact:**

Delayed incident response, increased exposure and possible failure to meet applicable notification obligations.

**Recommendation:**

Review contractual notification provisions and define CloudLedger's internal escalation and communication process.

**Related Risk:** TPR-001

**Status:** Pending Evidence Collection

### Finding 4 – Business Continuity Assurance Not Verified

**Finding ID:** SSAR-F04  
**Risk:** Inability to maintain or recover production services following a cloud service disruption.

**Observation:**

No relevant continuity assurance documentation, recovery objectives or recovery test evidence was examined.

**Potential Impact:**

Extended service interruption, customer impact and financial loss.

**Recommendation:**

Review applicable service availability commitments, recovery arrangements, backup responsibilities and recovery testing evidence.

**Related Risk:** TPR-001

**Status:** Pending Evidence Collection

## 6. Shared Responsibility Considerations

CloudLedger must understand that using AWS does not transfer all information security responsibilities to AWS.

| Security Area | Typical AWS Responsibility | CloudLedger Responsibility |
|---|---|---|
| Physical Data Centres | Physical facilities and environmental protection | Understand relevant assurance and service dependencies |
| Cloud Infrastructure | Underlying infrastructure security | Secure configuration of deployed cloud resources |
| Identity and Access | Security features provided by cloud services | Configure identities, permissions and MFA appropriately |
| Customer Data | Provides infrastructure and service capabilities | Classify, protect and manage customer information |
| Application Security | Security of underlying cloud services | Secure application development and deployment |
| Logging | Provides logging capabilities | Enable, protect, monitor and review relevant logs |
| Backup and Recovery | Provides relevant backup services and features | Configure, monitor and test backups and recovery |

**Note:** The exact responsibility allocation depends on the AWS service and deployment model. This table is illustrative and must be validated against the services CloudLedger actually uses.

## 7. Recommended Action Plan

| Action ID | Action | Responsible Role | Priority | Status |
|---|---|---|---|---|
| SSAR-A01 | Obtain and review relevant AWS assurance documentation | Information Security Manager | High | Planned |
| SSAR-A02 | Develop an AWS shared responsibility matrix | IT Manager | High | Planned |
| SSAR-A03 | Review cloud incident notification arrangements | Information Security Manager | High | Planned |
| SSAR-A04 | Review backup and disaster recovery responsibilities | IT Manager | High | Planned |
| SSAR-A05 | Validate cloud configuration and access controls | Cloud Administrator | High | Planned |

## 8. Overall Assessment Conclusion

AWS is identified as a Critical supplier because of its role in supporting CloudLedger's production services and processing sensitive information.

The assessment identified areas requiring further evidence collection and validation.

The supplier's actual security effectiveness has not been determined. Supplier approval and residual risk acceptance remain subject to appropriate evidence review and management decisions.

## 9. Approval

| Role | Name | Status |
|---|---|---|
| Assessment Owner | Information Security Manager | Simulated |
| Technical Reviewer | IT Manager | Pending |
| Risk Acceptance Authority | Managing Director | Pending |

## 10. Disclaimer

This report is a fictional simulated GRC portfolio assessment. AWS has not been contacted, audited or assessed through this exercise. No real supplier assurance evidence or technical configurations were examined.
