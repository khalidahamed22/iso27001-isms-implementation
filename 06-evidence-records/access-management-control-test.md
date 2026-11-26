# Access Management Control Test Record

**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Test ID:** CT-001  
**Test Date:** 2026-11-26  
**Control Area:** Identity and Access Management  
**Test Status:** Simulated – Portfolio Evidence  
**Tested By:** GRC Analyst  
**Reviewed By:** Information Security Manager

---

## 1. Test Objective

To assess whether CloudLedger's user access management processes are appropriately designed and operating as intended.

The test evaluates whether:

- User access is authorised before provisioning.
- Access permissions are appropriate to job responsibilities.
- Departing employees have their access revoked.
- Periodic access reviews identify excessive permissions.
- Identified access weaknesses are remediated.

## 2. Control References

| Reference | Control |
|---|---|
| ISO 27001 Clause 8.1 | Operational Planning and Control |
| Annex A 5.15 | Access Control |
| Annex A 5.16 | Identity Management |
| Annex A 5.18 | Access Rights |
| Annex A 6.5 | Responsibilities After Termination or Change of Employment |
| Annex A 8.2 | Privileged Access Rights |
| Annex A 8.3 | Information Access Restriction |

## 3. Test Methodology

The simulated test uses a document inspection and walkthrough approach.

The following portfolio records are examined:

- AR-001 – User Access Request
- AR-002 – User Access Revocation
- UAR-001 – User Access Review Register
- REM-001 – Access Review Remediation Record
- CL-PROC-001 – Joiner–Mover–Leaver Procedure
- CL-POL-002 – Access Control Policy

**Important:** These are simulated records. No live systems, identity-provider configurations or technical access logs were examined.

## 4. Test Results

| Test ID | Test Description | Expected Result | Simulated Result | Status |
|---|---|---|---|---|
| T-001 | Inspect joiner access request | Approval exists before provisioning | Approval dates precede provisioning date | Pass – Simulated |
| T-002 | Inspect access permissions | Permissions match business requirements | Restricted development access documented | Pass – Simulated |
| T-003 | Inspect leaver access revocation | Applicable access is revoked at departure | Revocation documented at departure time | Pass – Simulated |
| T-004 | Inspect periodic access review | Excessive access is identified | Two excessive access cases identified | Pass – Simulated |
| T-005 | Inspect remediation records | Identified weaknesses are addressed | Both findings marked closed | Pass – Simulated |
| T-006 | Inspect privileged access management | Privileged access is appropriately restricted | Time-limited access model documented | Pass – Simulated |

## 5. Exceptions and Limitations

Although the simulated documentation indicates that the processes are operating as intended, the following technical evidence has not been independently verified:

- Identity-provider account configuration.
- AWS IAM permission settings.
- MFA enforcement configuration.
- Actual account disablement logs.
- Privileged session logs.
- Technical evidence of remediation.

These items would require additional evidence in a real assessment.

## 6. Overall Assessment

**Documentation-Based Test Result:** Satisfactory – Simulated

The reviewed portfolio records demonstrate a documented access management workflow covering user provisioning, access modification, revocation, periodic reviews and remediation.

However, operational effectiveness cannot be concluded from documentation alone. Technical configurations and system-generated evidence would be required to establish that the controls operate effectively in a real environment.

## 7. Recommendations

1. Obtain user account exports from the identity provider.
2. Verify AWS IAM permissions against approved access requirements.
3. Review MFA enforcement settings.
4. Inspect actual account revocation logs.
5. Verify privileged access duration and session records.
6. Retain evidence supporting each completed access review.

## 8. Conclusion

The simulated access management documentation provides a foundation for demonstrating ISO 27001 access control implementation.

Further technical verification would be required before making a real-world conclusion about control operating effectiveness.

---

**Portfolio Disclaimer:** This is a fictional control testing record created for educational purposes. No real company systems were tested, and no actual audit or independent assurance conclusion was performed.
