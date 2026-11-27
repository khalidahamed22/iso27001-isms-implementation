# Change Management Procedure

**Document ID:** PROC-010  
**Version:** 1.0  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Related Control:** ISO/IEC 27001:2022 Annex A 8.32

## 1. Purpose

This procedure establishes requirements for requesting, assessing, approving, implementing and reviewing changes to organisational information systems and technology environments.

Its purpose is to minimise security risks, service disruptions, unauthorised modifications and unintended impacts resulting from changes.

## 2. Scope

This procedure applies to changes involving:

- Production and development applications.
- AWS cloud infrastructure and configurations.
- Network devices and security appliances.
- Databases and data storage systems.
- Identity and access management systems.
- Operating systems and endpoint configurations.
- Security tools and monitoring systems.
- Software libraries and application dependencies.

Emergency changes are also covered by this procedure.

## 3. Change Categories

| Change Category | Description | Example |
|---|---|---|
| Standard Change | Low-risk, repetitive change with an approved documented process | Routine approved software updates |
| Normal Change | Change requiring risk assessment and formal approval | Production application upgrade |
| Emergency Change | Urgent change required to address a critical security issue or service disruption | Blocking an actively exploited vulnerability |

Standard changes must be documented and pre-authorised. They must still be monitored and reviewed periodically.

## 4. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Change Requester | Submit change requests with sufficient information |
| Change Owner | Coordinate the change and ensure required documentation is maintained |
| IT Team | Assess technical impact and implement approved changes |
| Information Security Manager | Evaluate security risks and required security safeguards |
| System Owner | Assess business impact and approve changes affecting owned systems |
| Change Approver | Authorise changes according to delegated authority |
| Change Advisory Group | Review significant or high-risk changes where required |

The requester should not approve their own high-risk change without independent review.

## 5. Change Request Process

All normal changes must be recorded using an approved change request.

Each request should include:

- Unique change reference number.
- Requester and responsible owner.
- Description and business justification.
- Affected systems and assets.
- Proposed implementation date.
- Security and operational impact.
- Risk assessment.
- Testing and validation requirements.
- Rollback or recovery plan.
- Required approvals.

Incomplete requests must be returned for clarification before approval.

## 6. Security and Risk Assessment

Before approval, the change owner and relevant technical personnel must evaluate:

- Confidentiality, integrity and availability impacts.
- Potential vulnerabilities introduced by the change.
- Access control and privilege implications.
- Data protection and encryption requirements.
- Network exposure and configuration changes.
- Logging and monitoring requirements.
- Supplier or third-party dependencies.
- Backup and recovery requirements.
- Compliance and contractual obligations.

High-risk changes must receive additional security review before implementation.

## 7. Approval Requirements

Changes must be approved by authorised personnel before implementation.

| Change Type | Required Approval |
|---|---|
| Standard | Pre-authorised change owner or designated approver |
| Normal – Low/Medium Risk | System Owner and relevant Change Approver |
| Normal – High Risk | System Owner, IT Manager and Information Security Manager |
| Emergency | Authorised emergency approver, with retrospective review |

Approval requirements must reflect the organisation's delegated authority.

## 8. Testing Requirements

Where technically applicable, changes must be tested before production deployment.

Testing may include:

- Functional testing.
- Security testing.
- Vulnerability assessment.
- Compatibility testing.
- Access control validation.
- Performance testing.
- Backup and recovery validation.

Production changes must not be deployed solely on the basis of successful development testing where additional production validation is necessary.

## 9. Implementation

The authorised implementation team must:

1. Verify that approval has been obtained.
2. Confirm the implementation schedule.
3. Ensure required backups or recovery arrangements are available.
4. Follow the approved implementation plan.
5. Record implementation activities.
6. Monitor the affected environment.
7. Report unexpected outcomes.

Unauthorised changes are prohibited and must be investigated.

## 10. Rollback and Recovery

Each normal change must have an appropriate rollback or recovery plan where technically feasible.

The plan should define:

- Conditions requiring rollback.
- Responsible personnel.
- Recovery steps.
- Backup or restoration requirements.
- Validation activities.
- Stakeholder communication requirements.

If a change causes unacceptable service or security impact, the change owner must coordinate rollback or another approved recovery action.

## 11. Emergency Changes

Emergency changes may be implemented without the full normal approval sequence only where delay would create unacceptable security or business risk.

Emergency changes must:

- Be authorised by an appropriate emergency approver.
- Have the reason and risk documented.
- Be implemented by authorised personnel.
- Be recorded as soon as practicable.
- Receive retrospective review and approval.
- Be assessed for lessons learned.

Emergency classification must not be used to bypass normal change controls for convenience.

## 12. Post-Implementation Review

After implementation, the change owner must evaluate:

- Whether the change achieved its intended outcome.
- Whether security requirements were satisfied.
- Whether unexpected issues occurred.
- Whether rollback was required.
- Whether documentation requires updating.
- Whether additional corrective actions are needed.

The change must only be closed after the required review and evidence are recorded.

## 13. Change Records

The organisation must retain:

- Change requests.
- Risk assessments.
- Approval records.
- Test results.
- Implementation records.
- Rollback records, where applicable.
- Post-implementation reviews.
- Emergency change justifications.
- Related incident or problem references.

## 14. Monitoring and Review

The Information Security Manager and IT Manager should periodically review change management performance.

Suggested indicators include:

- Number of changes implemented.
- Percentage of changes approved before implementation.
- Number of unauthorised changes.
- Change failure rate.
- Emergency change frequency.
- Number of changes requiring rollback.
- Outstanding post-implementation reviews.

## 15. Review and Approval

| Approval Role | Name | Status |
|---|---|---|
| Prepared By | IT Manager | Draft |
| Reviewed By | Information Security Manager | Pending |
| Approved By | CTO | Pending |

**Portfolio Disclaimer:** This procedure is a fictional implementation artefact created for simulated ISO/IEC 27001:2022 portfolio demonstration. It does not establish that change management controls have been implemented in a real organisation.
