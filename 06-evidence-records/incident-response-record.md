# Incident Response Record

**Document ID:** IRR-001  
**Related Incident ID:** INC-002  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Date:** 2026-11-27  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Confidential  

## 1. Incident Overview

| Field | Details |
|---|---|
| Incident Reference | INC-002 |
| Incident Type | Phishing Attempt |
| Detection Source | Employee Report |
| Affected Asset | AST-009 – Corporate Employee Laptops |
| Initial Severity | Medium |
| Incident Owner | Security Analyst |
| Response Status | Simulated Investigation |

## 2. Initial Triage

**Scenario:** An employee reports receiving a suspicious email containing an attachment that may be malicious.

Initial response activities:

- Record the report in the Security Incident Register.
- Obtain the suspicious email and relevant headers.
- Identify the recipient and determine whether the attachment was opened.
- Check whether credentials or sensitive information were submitted.
- Determine whether other employees received the same email.
- Preserve relevant email and endpoint evidence.

**Initial Assessment:** Potential phishing attempt. Successful compromise has not been established.

## 3. Investigation

| Investigation Activity | Expected Evidence | Scenario Status |
|---|---|---|
| Email header analysis | Sender, SPF, DKIM and DMARC results | Pending |
| URL analysis | Reputation and destination information | Pending |
| Attachment analysis | File hash and safe malware-analysis results | Pending |
| Endpoint review | EDR alerts and process execution records | Pending |
| User verification | Employee confirmation | Pending |
| Scope assessment | Other affected recipients | Pending |

## 4. Containment Plan

Proposed actions, subject to investigation findings and authorisation:

1. Quarantine the suspicious email where technically possible.
2. Block confirmed malicious sender addresses, URLs or file hashes.
3. Isolate an endpoint only if evidence indicates compromise and the action is authorised.
4. Reset affected credentials if compromise is suspected or confirmed.
5. Search mailboxes for related messages.
6. Preserve evidence before performing actions that may alter it.

**Containment Status:** Not Performed – Simulated Scenario.

## 5. Eradication and Recovery

If malware execution or account compromise is confirmed:

- Remove malicious files and persistence mechanisms.
- Rebuild affected endpoints where necessary.
- Reset compromised credentials and revoke active sessions.
- Restore systems from trusted sources if required.
- Validate endpoint security controls before returning devices to service.
- Monitor for recurring suspicious activity.

**Recovery Status:** Not Performed – Pending Investigation.

## 6. Communication and Escalation

| Stakeholder | Notification Requirement |
|---|---|
| Information Security Manager | Escalate according to incident severity |
| IT / Endpoint Team | Coordinate endpoint investigation and containment |
| Affected Employee | Provide reporting instructions and updates |
| Management | Escalate significant business impact |
| Legal / Data Protection Contact | Assess potential legal or personal-data implications |

Any external notification must follow applicable legal, regulatory and contractual requirements.

## 7. Root Cause Analysis

**Root Cause:** Not Determined.

The phishing email has not been technically analysed in this simulated scenario. No conclusion can be made about its origin, delivery mechanism or whether a user or system was compromised.

## 8. Corrective and Preventive Actions

| Action ID | Proposed Action | Owner | Status |
|---|---|---|---|
| CAPA-001 | Review email security filtering rules | IT Security | Pending |
| CAPA-002 | Conduct targeted phishing awareness training | HR / Security | Pending |
| CAPA-003 | Review endpoint detection coverage | IT Security | Pending |
| CAPA-004 | Review incident reporting and escalation process | Information Security Manager | Pending |

## 9. Lessons Learned

To be completed after investigation and response activities.

Potential review areas:

- Effectiveness of email security controls.
- Employee awareness and reporting speed.
- Detection and response time.
- Evidence preservation.
- Coordination between security and IT teams.

## 10. Closure Assessment

| Field | Status |
|---|---|
| Investigation Completed | No |
| Incident Confirmed | Not Established |
| Containment Verified | No |
| Recovery Verified | No |
| Corrective Actions Completed | No |
| Closure Approval | Pending |
| Final Incident Status | Open – Simulated |

**Portfolio Disclaimer:** This record documents a fictional phishing scenario for portfolio demonstration. No actual email was received, no endpoint was investigated, and no containment, eradication or recovery activity was performed.
