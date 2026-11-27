# Business Continuity Exercise Plan

**Document ID:** BCEP-001  
**Organisation:** CloudLedger Technologies (Pvt) Ltd  
**Status:** Draft – Simulated Portfolio Document  
**Classification:** Internal  
**Plan Owner:** Information Security Manager  
**Approval Authority:** Senior Management  
**Planned Exercise Date:** 2027-01-15

## 1. Purpose

The purpose of this exercise plan is to establish a structured approach for testing CloudLedger's business continuity and disaster recovery arrangements.

The exercise will assess whether assigned personnel understand their responsibilities, whether communication and escalation arrangements are effective, and whether recovery priorities are appropriate.

## 2. Exercise Objectives

The exercise aims to:

1. Evaluate awareness of business continuity responsibilities.
2. Test disruption identification and escalation.
3. Assess the effectiveness of management decision-making.
4. Evaluate internal and external communication arrangements.
5. Review the proposed recovery priorities and objectives.
6. Identify weaknesses in the Business Continuity Plan and Disaster Recovery Plan.
7. Record improvement opportunities and corrective actions.

## 3. Exercise Scope

The exercise will cover:

- SaaS application disruption.
- AWS infrastructure dependencies.
- Production database availability.
- Security incident escalation.
- Customer communication.
- Business recovery coordination.
- Management decision-making.

No production systems will be disrupted during the planned tabletop exercise.

## 4. Exercise Type

**Exercise Type:** Tabletop Exercise

A tabletop exercise is a discussion-based activity in which participants respond to a simulated disruption scenario using existing plans and procedures.

Participants will discuss decisions and expected actions without performing actual production recovery activities.

## 5. Exercise Scenario

**Scenario ID:** EX-001

**Scenario:** Major Cloud Infrastructure Disruption

A simulated AWS infrastructure incident affects CloudLedger's production application and database services.

Customers are unable to access the SaaS financial management platform. The technical team receives alerts indicating that several production resources are unavailable.

The disruption has the potential to affect customer financial operations and service availability.

### Scenario Injects

| Inject ID | Simulated Event | Expected Response |
|---|---|---|
| INJ-001 | Production application becomes unavailable | Identify disruption and assess impact |
| INJ-002 | Database connectivity fails | Escalate to database and cloud administrators |
| INJ-003 | Customers report service disruption | Activate customer communication arrangements |
| INJ-004 | AWS provider reports a regional service issue | Assess provider dependencies and recovery options |
| INJ-005 | Management requests recovery estimates | Review proposed RTO and RPO targets |
| INJ-006 | Service recovery is proposed | Define technical and business validation requirements |

## 6. Participants and Responsibilities

| Participant | Exercise Responsibility |
|---|---|
| Senior Management Representative | Make simulated activation and prioritisation decisions |
| IT Manager | Coordinate continuity and recovery discussions |
| Information Security Manager | Assess security implications |
| Cloud Administrator | Explain infrastructure recovery options |
| Head of Engineering | Discuss application recovery |
| Head of Finance | Assess financial business impact |
| Customer Support Manager | Explain customer communication arrangements |
| Exercise Facilitator | Introduce scenario events and record observations |

## 7. Exercise Schedule

| Activity | Planned Duration |
|---|---|
| Opening and exercise briefing | 15 minutes |
| Scenario introduction | 10 minutes |
| Incident identification and escalation | 15 minutes |
| Recovery planning discussion | 25 minutes |
| Stakeholder communication discussion | 15 minutes |
| Lessons learned and closing | 10 minutes |

**Estimated Total Duration:** 90 minutes

## 8. Evaluation Criteria

| Evaluation ID | Evaluation Area | Expected Result |
|---|---|---|
| EVA-001 | Disruption identification | Participants identify critical service disruption |
| EVA-002 | Escalation | Correct roles and escalation paths are identified |
| EVA-003 | Plan activation | Participants understand activation authority |
| EVA-004 | Recovery prioritisation | Recovery sequence reflects business impact |
| EVA-005 | RTO and RPO awareness | Participants understand proposed recovery targets |
| EVA-006 | Communication | Appropriate stakeholder communication is identified |
| EVA-007 | Security considerations | Security and evidence-preservation requirements are considered |
| EVA-008 | Recovery validation | Participants identify required technical and business checks |

## 9. Evidence to Be Collected

The exercise facilitator shall maintain:

- Participant attendance.
- Exercise scenario and injects.
- Discussion notes.
- Decisions made by participants.
- Identified gaps and weaknesses.
- Evaluation results.
- Lessons learned.
- Corrective action references.

## 10. Exercise Success Criteria

The exercise will be considered satisfactory when:

- Participants can identify their responsibilities.
- Escalation and activation arrangements are understood.
- Critical recovery priorities are recognised.
- Stakeholder communication requirements are addressed.
- Security considerations are incorporated into recovery discussions.
- Identified weaknesses are recorded for follow-up.

Any significant gaps shall be documented regardless of the overall exercise outcome.

## 11. Exercise Safety and Limitations

- The exercise is discussion-based only.
- No production systems will be modified or interrupted.
- No actual customer notifications will be sent.
- No real disaster recovery activities will be performed.
- All scenario information is fictional.
- Exercise observations must not be represented as evidence of successful technical recovery.

## 12. Approval

| Role | Approval Status |
|---|---|
| Information Security Manager | Pending |
| IT Manager | Pending |
| Senior Management | Pending |

**Exercise Status:** Planned – Not Conducted

## 13. Portfolio Disclaimer

This is a fictional Business Continuity Exercise Plan prepared for a simulated ISO/IEC 27001:2022 implementation portfolio. The exercise has not been conducted and no actual participant performance or recovery capability has been demonstrated.
