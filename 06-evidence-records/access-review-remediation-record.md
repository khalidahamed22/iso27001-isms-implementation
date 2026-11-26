# Access Review Remediation Record

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Record ID:** REM-001  
**Related Review:** UAR-001  
**Record Status:** Simulated – Portfolio Evidence  
**Classification:** Internal

---

## 1. Remediation Summary

During the simulated user access review dated 25 November 2026, two access control weaknesses were identified.

| Finding ID | Employee | System | Identified Weakness | Priority |
|---|---|---|---|---|
| REM-001-A | Tharushi Silva | Customer Financial Records | Read/Write access exceeds job requirements | High |
| REM-001-B | Amal Jayasinghe | Privileged AWS Account | Permanent administrator access instead of time-limited privileged access | High |

## 2. Finding REM-001-A – Excessive Data Access

**Employee:** Tharushi Silva  
**Employee ID:** CL-EMP-032  
**System:** Customer Financial Records  
**Responsible Owner:** Data Owner

### Identified Issue

The employee's current permissions allow reading and modifying customer financial records. However, the Finance Manager's documented business requirement only requires read-only access.

### Risk

Unnecessary modification permissions could result in accidental or unauthorised changes to customer financial records.

### Required Corrective Action

1. Review the employee's business requirements.
2. Obtain approval from the Data Owner.
3. Remove unnecessary modification permissions.
4. Retain read-only access.
5. Verify the updated permissions.

**Target Completion Date:** 2026-11-30

### Simulated Remediation Result

| Field | Result |
|---|---|
| Action Taken | Modification permissions removed |
| Remaining Access | Read Only |
| Implemented By | IT Administrator |
| Completion Date | 2026-11-28 |
| Verification | Pass – Simulated |
| Verified By | Data Owner |
| Status | Closed – Simulated |

## 3. Finding REM-001-B – Excessive Privileged Access

**Employee:** Amal Jayasinghe  
**Employee ID:** CL-EMP-018  
**System:** Privileged AWS Account  
**Responsible Owner:** Information Security Manager

### Identified Issue

The employee has permanent administrator permissions. The organisation's proposed access model requires privileged access to be granted only for approved administrative tasks and limited periods.

### Risk

Permanent privileged permissions increase the potential impact of compromised credentials, accidental misconfiguration and unauthorised administrative activities.

### Required Corrective Action

1. Review the employee's administrative responsibilities.
2. Identify the privileged tasks that require elevated permissions.
3. Approve an appropriate time-limited access model.
4. Remove unnecessary permanent administrator permissions.
5. Configure and test the approved privileged access workflow.
6. Retain access logs and approval records.

**Target Completion Date:** 2026-12-05

### Simulated Remediation Result

| Field | Result |
|---|---|
| Action Taken | Permanent administrator access removed |
| New Access Model | Time-limited privileged access |
| Implemented By | Cloud Administrator |
| Completion Date | 2026-12-03 |
| Verification | Pass – Simulated |
| Verified By | Information Security Manager |
| Status | Closed – Simulated |

## 4. Remediation Summary

| Finding ID | Original Issue | Remediation Status |
|---|---|---|
| REM-001-A | Excessive customer data permissions | Closed – Simulated |
| REM-001-B | Permanent privileged access | Closed – Simulated |

## 5. GRC Verification

The reviewer should confirm:

- The corrective actions address the original weaknesses.
- Updated access permissions match approved business requirements.
- Supporting technical evidence exists.
- Remediation was verified by an appropriate reviewer.
- The original review register reflects the final remediation status.

## 6. ISO/IEC 27001:2022 Alignment

- Annex A 5.18 – Access Rights
- Annex A 8.2 – Privileged Access Rights
- Annex A 8.3 – Information Access Restriction
- Clause 10.1 – Continual Improvement
- Clause 10.2 – Nonconformity and Corrective Action

**Portfolio Disclaimer:** All employee information, findings, remediation activities, dates and verification results are fictional. They demonstrate a simulated GRC remediation workflow and are not evidence of actual organisational implementation.
