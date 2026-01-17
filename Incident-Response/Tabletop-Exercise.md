# Incident Response Tabletop Exercise

## 1. Purpose
The purpose of this tabletop exercise is to evaluate TujaePay’s ability to detect, respond to,
contain, and recover from a cybersecurity incident. The exercise also tests communication,
decision-making, and coordination across teams.

---

## 2. Scope
This exercise covers:
- Security incident detection and triage
- Incident escalation and communication
- Containment and remediation actions
- Internal and external communications
- Recovery and lessons learned

---

## 3. Participants and Roles

- Incident Commander: Security Lead
- Technical Response: Engineering / IT
- Communications: Management / Legal
- GRC / Compliance: GRC Team
- Observers: Executive Leadership

---

## 4. Exercise Objectives

- Validate incident response roles and responsibilities
- Test decision-making and escalation paths
- Evaluate communication effectiveness
- Identify gaps in procedures or tooling
- Improve organizational readiness

---

## 5. Scenario Overview

TujaePay’s monitoring platform alerts the security team to unusual activity originating from
a cloud workload hosting internal services. Shortly after, multiple failed authentication
attempts and abnormal outbound traffic patterns are detected.

Initial indicators suggest a compromised service account may be attempting to access internal
systems and exfiltrate data.

---

## 6. Scenario Timeline (Injects)

### Phase 1: Detection
- Security monitoring alerts on anomalous behavior
- Engineering confirms suspicious outbound connections

Discussion Points:
- Who investigates first?
- How is the incident classified?
- Who is notified?

---

### Phase 2: Analysis
- Logs show use of a valid service account from an unknown IP address
- Activity includes enumeration of internal resources

Discussion Points:
- Is this a security incident?
- What data or systems may be impacted?
- What is the severity?

---

### Phase 3: Containment
- Decision required: disable service account or isolate workload
- Risk of service disruption must be considered

Discussion Points:
- What action is taken first?
- Who approves disruptive actions?
- How is impact assessed?

---

### Phase 4: Eradication and Recovery
- Root cause identified as leaked credentials
- Credentials are rotated and access keys invalidated
- Monitoring is increased

Discussion Points:
- What additional systems need to be checked?
- When is the incident considered contained?
- How is service integrity validated?

---

### Phase 5: Communication
- Management asks whether customer notification is required
- Legal and GRC evaluate regulatory impact

Discussion Points:
- Who communicates internally?
- Who communicates externally?
- What is the messaging?

---

## 7. Success Criteria

- Incident is properly identified and escalated
- Roles and responsibilities are followed
- Decisions are documented
- Communication is timely and appropriate
- Gaps and improvement areas are identified

---

## 8. Exercise Results

- Date Conducted:
- Participants:
- Overall Assessment:
  - Effective
  - Needs Improvement

Key Observations:
- 
- 
- 

---

## 9. Identified Gaps and Improvement Actions

| Gap | Impact | Action | Owner | Target Date |
|-----|--------|--------|-------|-------------|
|     |        |        |       |             |

---

## 10. Lessons Learned and Follow-Up

- Summary of lessons learned:
- Updates required to policies or procedures:
- Training or tooling improvements needed:

---

## 11. Review and Approval

- Exercise Facilitated By:
- Reviewed By:
- Review Date:
- Next Scheduled Exercise:
