
# AWS Shared Responsibility Matrix

**Document ID:** SSRM-001  
**Version:** 1.0  
**Service Provider:** Amazon Web Services (AWS)  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Document Owner:** IT Manager  
**Review Date:** 2026-11-27  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Confidential  

## 1. Purpose

This document defines the division of information security responsibilities between CloudLedger Technologies (Pvt) Ltd and Amazon Web Services (AWS).

The objective is to identify security responsibilities associated with CloudLedger's use of AWS cloud infrastructure and prevent security gaps caused by unclear ownership.

## 2. Shared Responsibility Model

AWS operates under a shared responsibility model.

- **Security of the cloud:** AWS is responsible for protecting the underlying cloud infrastructure, including physical facilities, hardware and foundational infrastructure.
- **Security in the cloud:** CloudLedger is responsible for securing the workloads, data, identities, applications and configurations it deploys or manages within AWS.

The exact division depends on the AWS service and deployment model.

## 3. Responsibility Matrix

| Security Area | AWS Responsibility | CloudLedger Responsibility |
|---|---|---|
| Physical Data Centres | Protect physical facilities and infrastructure | Review relevant supplier assurance information |
| Physical Server Hardware | Maintain and protect underlying hardware | Understand service dependencies |
| Hypervisor and Virtualisation | Manage underlying infrastructure components according to service model | Secure deployed workloads and configurations within customer control |
| Cloud Identity Management | Provide identity and access management capabilities | Configure users, roles, permissions and MFA |
| Customer Data | Protect underlying infrastructure and provide service capabilities | Classify, protect, retain and manage customer information |
| Network Security | Protect underlying network infrastructure | Configure cloud networks, security groups, routing and network access controls |
| Application Security | Secure AWS services and underlying service components | Develop, test and maintain secure applications |
| Vulnerability Management | Manage vulnerabilities in AWS-managed infrastructure | Identify and remediate vulnerabilities in customer-managed workloads |
| Logging and Monitoring | Provide relevant logging and monitoring services | Enable, configure, retain, review and investigate relevant logs |
| Encryption | Provide supported encryption capabilities and services | Configure encryption, manage customer-controlled keys and protect data |
| Backup and Recovery | Provide backup and recovery features where applicable | Configure backup policies, monitor backups and test restoration |
| Incident Management | Respond to incidents affecting AWS infrastructure and services | Detect and respond to incidents involving CloudLedger systems and data |
| Business Continuity | Maintain AWS infrastructure resilience and service continuity arrangements | Develop business continuity and disaster recovery arrangements for CloudLedger |
| Access Reviews | Manage AWS personnel access to AWS systems | Review CloudLedger employee and supplier access |
| Configuration Management | Maintain AWS service infrastructure | Securely configure and monitor customer-managed cloud resources |

## 4. CloudLedger Security Responsibilities

CloudLedger must establish and maintain the following activities:

1. Maintain an inventory of AWS resources.
2. Apply least-privilege access controls.
3. Enforce MFA for privileged access.
4. Protect customer information using appropriate safeguards.
5. Enable and monitor relevant security logs.
6. Perform vulnerability assessments on customer-managed workloads.
7. Maintain secure application development practices.
8. Configure and monitor backups.
9. Test recovery procedures.
10. Maintain incident response procedures for cloud-related security events.
11. Review AWS security notifications and relevant assurance information.
12. Monitor cloud configuration changes.

## 5. AWS Supplier Assurance Requirements

CloudLedger should obtain and review relevant AWS assurance information, including:

- AWS security and compliance documentation.
- Relevant independent assurance reports.
- Service-specific security documentation.
- Data protection and privacy information.
- Service availability and continuity information.
- Relevant security incident and notification terms.

The scope and reporting period of any assurance report must be checked before relying on it.

## 6. Responsibility Validation

The IT Manager should periodically verify that:

- AWS services used by CloudLedger are identified.
- Customer-managed security configurations are assigned to responsible personnel.
- AWS responsibilities are understood.
- CloudLedger responsibilities have owners.
- Security gaps are recorded in the risk register.
- Relevant controls have supporting implementation evidence.

## 7. Review and Approval

This matrix must be reviewed annually and whenever CloudLedger adopts new AWS services or materially changes its cloud architecture.

| Role | Name | Approval Status |
|---|---|---|
| IT Manager | Pending | Not Approved |
| Information Security Manager | Pending | Not Approved |
| Managing Director | Pending | Not Approved |

## 8. Related Documents

- Third-Party and Supplier Security Policy.
- Supplier Register.
- Supplier Security Assessment Questionnaire.
- Supplier Security Assessment Report.
- Third-Party Risk Assessment Register.
- Information Security Risk Register.
- Access Control Policy.

## 9. Disclaimer

This is a fictional simulated portfolio document. It illustrates typical AWS shared responsibility concepts and is not a verified responsibility assessment for a specific deployed AWS architecture. Actual responsibilities must be validated against the AWS services used by the organisation.
