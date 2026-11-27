# Cloud Security Configuration Standard

**Document ID:** STD-001  
**Document Owner:** IT Manager  
**Approved By:** Head of Technology  
**Version:** 1.0  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Review Frequency:** Annually or following significant infrastructure changes

## 1. Purpose

This standard defines the minimum security configuration requirements for cloud infrastructure operated by CloudLedger Technologies (Pvt) Ltd.

Its objective is to reduce the risk of unauthorised access, data exposure, insecure configurations and service disruption within the AWS environment.

## 2. Scope

This standard applies to:

- AWS production and development environments.
- Cloud networking and security configurations.
- Compute instances and container workloads.
- Cloud storage services.
- Cloud databases.
- Identity and access management.
- Logging and monitoring services.
- Backup and recovery configurations.

## 3. Cloud Account Security

The following requirements must be followed:

1. Use dedicated AWS accounts or appropriate account separation for production and non-production environments.
2. Enable multi-factor authentication (MFA) for privileged users.
3. Avoid using the AWS root user for routine administration.
4. Protect root account credentials and maintain appropriate recovery arrangements.
5. Apply least-privilege access permissions.
6. Review privileged access periodically.
7. Enable appropriate logging of account and administrative activities.
8. Restrict access to cloud management interfaces.

## 4. Identity and Access Management

Cloud access must be managed through approved identity and access management mechanisms.

Requirements:

- Assign access according to job responsibilities.
- Use role-based access control where appropriate.
- Prohibit shared user accounts unless formally justified and controlled.
- Require MFA for privileged and remote administrative access.
- Avoid long-lived access keys where temporary credentials are practical.
- Rotate or revoke credentials when compromise is suspected.
- Remove access promptly when employees leave.
- Review privileged permissions regularly.

## 5. Network Security

Cloud network configurations must restrict unnecessary exposure.

Requirements:

1. Separate public-facing services from internal application and database components.
2. Restrict inbound and outbound traffic to approved requirements.
3. Avoid exposing database services directly to the public internet.
4. Use security groups and network access controls appropriately.
5. Restrict administrative access to approved access paths.
6. Review firewall and network rules periodically.
7. Document significant network configuration changes.

## 6. Data Protection and Storage Security

CloudLedger information must be protected according to its classification.

Requirements:

- Enable encryption at rest for Restricted and Confidential information, subject to approved technical architecture.
- Use encryption in transit for sensitive data transfers.
- Restrict access to storage services.
- Block public access to private storage resources unless explicitly approved.
- Apply appropriate data retention and deletion requirements.
- Protect encryption keys and secrets.
- Review storage permissions and access policies periodically.

Any exception to encryption requirements must undergo documented risk assessment and formal approval. Alternative controls must not automatically be treated as equivalent to encryption.

## 7. Logging and Monitoring

Cloud environments must generate and retain appropriate security logs.

The organisation should monitor:

- Authentication attempts.
- Privileged account activities.
- IAM policy changes.
- Security group and network changes.
- Storage access and permission changes.
- Cloud service configuration changes.
- Security alerts and suspicious activities.

Logging must be protected against unauthorised modification and deletion.

Log retention periods must be defined according to legal, regulatory, contractual and operational requirements.

## 8. Vulnerability and Patch Management

CloudLedger must maintain a process for identifying and addressing vulnerabilities.

Requirements:

1. Maintain an inventory of cloud workloads and relevant software components.
2. Perform vulnerability assessments at defined intervals.
3. Prioritise vulnerabilities according to severity and business risk.
4. Apply security patches within approved remediation timelines.
5. Validate remediation where practical.
6. Document exceptions and overdue vulnerabilities.

## 9. Backup and Recovery

Critical cloud data and services must be covered by approved backup and recovery arrangements.

Requirements:

- Define backup frequency based on business requirements.
- Restrict access to backup repositories.
- Protect backups against unauthorised modification or deletion.
- Encrypt backups containing sensitive information.
- Define recovery objectives for critical services.
- Perform periodic restoration tests.
- Document backup failures and recovery test results.

## 10. Configuration and Change Management

Cloud infrastructure changes must follow an approved change management process.

Each significant change should include:

- Change description and business justification.
- Requesting individual.
- Risk and security impact assessment.
- Approval before implementation.
- Testing where appropriate.
- Implementation record.
- Rollback or recovery plan where appropriate.

Emergency changes must be documented and reviewed after implementation.

## 11. Cloud Security Responsibility

CloudLedger must understand and document the security responsibilities shared with AWS.

AWS is generally responsible for security of the underlying cloud infrastructure, while CloudLedger remains responsible for its own data, identities, applications and service configurations, depending on the AWS services used.

The IT Manager must review the applicable service-specific responsibilities before deploying or significantly changing cloud services.

## 12. Compliance and Verification

Compliance with this standard should be verified through:

- Periodic configuration reviews.
- IAM permission reviews.
- Vulnerability assessment reports.
- Cloud security monitoring records.
- Backup restoration test records.
- Change management records.
- Relevant cloud security assurance reports.

Identified deviations must be documented, risk assessed and tracked until resolution or formally accepted.

## 13. Related ISO/IEC 27001:2022 Controls

- A.5.15 – Access control.
- A.5.23 – Information security for use of cloud services.
- A.8.2 – Privileged access rights.
- A.8.5 – Secure authentication.
- A.8.8 – Management of technical vulnerabilities.
- A.8.9 – Configuration management.
- A.8.13 – Information backup.
- A.8.15 – Logging.
- A.8.16 – Monitoring activities.
- A.8.20 – Networks security.
- A.8.24 – Use of cryptography.

## 14. Review and Approval

| Approval Role | Name | Status |
|---|---|---|
| IT Manager | Simulated role | Pending |
| Head of Technology | Simulated role | Pending |

---

**Portfolio Disclaimer:** This is a simulated cloud security configuration standard for the fictional organisation CloudLedger Technologies (Pvt) Ltd. It defines proposed security requirements and does not demonstrate that AWS configurations have actually been deployed or verified.
