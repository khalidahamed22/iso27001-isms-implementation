# User Access Revocation Record – AR-002

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Record ID:** AR-002  
**Classification:** Internal  
**Record Status:** Simulated – Portfolio Evidence

---

## 1. Employee Details

| Field | Information |
|---|---|
| Employee Name | Kasun Fernando |
| Employee ID | CL-EMP-011 |
| Department | Finance |
| Job Title | Finance Executive |
| Line Manager | Finance Manager |
| Employment Type | Permanent Employee |
| Departure Type | Resignation |
| Last Working Date | 2026-11-20 |

## 2. Departure Notification

| Field | Information |
|---|---|
| Notification Received From | Human Resources |
| Notification Date | 2026-11-18 |
| Effective Departure Time | 2026-11-20, 5:00 PM |
| Notification Reference | SIM-HR-002 |
| IT Notification Received | 2026-11-18 |

## 3. Access Revocation Checklist

| System / Resource | Required Action | Completion Status |
|---|---|---|
| Corporate Email | Disable account | Completed – Simulated |
| AWS Environment | Revoke user access | Not Applicable – No direct access |
| Financial Management Application | Disable account | Completed – Simulated |
| Database Environment | Revoke access | Not Applicable – No direct access |
| Source Code Repository | Disable account | Not Applicable – No access |
| VPN / Remote Access | Revoke access | Completed – Simulated |
| MFA Sessions / Active Tokens | Revoke active sessions and tokens where applicable | Completed – Simulated |
| Shared Credentials | Review and rotate if necessary | Completed – Simulated |

## 4. Asset Return

| Asset | Asset ID | Return Status |
|---|---|---|
| Company Laptop | CL-LAP-011 | Returned – Simulated |
| Company ID Card | CL-ID-011 | Returned – Simulated |
| Security Token | CL-TOK-011 | Not Issued |

**Asset Return Verified By:** HR Representative  
**Verification Date:** 2026-11-20

## 5. IT Revocation Record

| Field | Information |
|---|---|
| Access Revocation Performed By | IT Administrator |
| Revocation Date | 2026-11-20 |
| Revocation Time | 5:00 PM |
| Account Status | Disabled – Simulated |
| Active Sessions | Revoked – Simulated |
| Verification Performed | Yes – Simulated |
| Supporting Evidence Reference | SIM-IT-002 |

## 6. Verification

| Verification Item | Result |
|---|---|
| HR departure notification received | Pass – Simulated |
| Required accounts identified | Pass – Simulated |
| Applicable access revoked | Pass – Simulated |
| Active sessions addressed | Pass – Simulated |
| Company assets returned | Pass – Simulated |
| Revocation documented | Pass – Simulated |

**Verified By:** IT Manager  
**Verification Date:** 2026-11-20

## 7. Closure

**Record Status:** Closed – Simulated  
**Closure Date:** 2026-11-20  
**Closed By:** IT Manager

## 8. GRC Review Notes

A GRC implementer or internal auditor should verify:

1. HR notifications are received promptly.
2. Access is revoked at the required departure time.
3. All relevant systems and accounts are covered.
4. Privileged access and active sessions are addressed.
5. Company assets are returned.
6. Evidence supports the recorded revocation activities.

**Potential Risk:** If an employee's account remains active after departure, the organisation may face unauthorised access, data disclosure or misuse of company resources.

**Recommended Control:** Maintain a documented offboarding process and periodically reconcile HR departure records against active user accounts.

---

**ISO/IEC 27001:2022 Alignment**

- Annex A 5.16 – Identity Management
- Annex A 5.18 – Access Rights
- Annex A 6.5 – Responsibilities After Termination or Change of Employment
- Annex A 8.2 – Privileged Access Rights
- Annex A 8.3 – Information Access Restriction

**Portfolio Disclaimer:** All employee details, notifications, approvals, actions and evidence references are fictional. This record demonstrates a simulated access revocation workflow, not a real offboarding event.
