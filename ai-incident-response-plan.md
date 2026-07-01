# AI Incident Response Plan

**Version:** 1.0  
**Last Updated:** June 2026  
**Owner:** Compliance Lead  
**Approved By:**  
**Review Date:** June 2027  
**Classification:** Internal  

---

## 1. Purpose

This plan defines how [Organisation Name] identifies, responds to, and learns from incidents involving AI systems. An AI incident is any event where an AI system causes harm, produces a significant error, behaves unexpectedly, or creates legal, regulatory, or reputational risk.

---

## 2. What Counts as an AI Incident

| Incident Type | Examples |
|---|---|
| Harmful output | AI produces content that causes harm to an individual or group |
| Discriminatory decision | AI produces outcomes that unfairly disadvantage protected groups |
| Privacy breach | AI processes personal data in an unauthorised or unexpected way |
| Security incident | AI system is compromised, manipulated, or produces adversarial outputs |
| Performance failure | AI system produces significantly inaccurate or unreliable outputs at scale |
| Regulatory breach | AI system operates in violation of EU AI Act or other applicable regulation |
| Unexpected behaviour | AI system acts outside its intended scope in a way that causes concern |

---

## 3. Incident Severity Classification

| Severity | Description | Examples |
|---|---|---|
| Critical | Immediate harm to individuals or significant regulatory breach | AI credit scoring system denying loans based on protected characteristics, AI system exposed to adversarial attack causing data breach |
| High | Significant risk of harm or major performance failure | AI chatbot providing dangerous advice, systematic bias identified in outputs, High Risk system deployed without conformity assessment |
| Medium | Limited harm or contained performance issue | Isolated inaccurate outputs, minor bias identified in specific scenarios |
| Low | Minor concern requiring monitoring | Unexpected but harmless behaviour, minor performance degradation |

---

## 4. Incident Response Team

| Role | Responsibility |
|---|---|
| Incident Commander | Leads the response and coordinates all actions |
| AI System Owner | Provides technical context and manages system-level response |
| Compliance Lead | Assesses regulatory implications and manages notifications |
| Communications Lead | Manages internal and external communications |
| Data Protection Officer | Advises on personal data implications |
| Legal Counsel | Advises on liability and regulatory obligations |

---

## 5. Incident Response Process

### Phase 1 — Detection and Reporting

- Any employee who identifies a potential AI incident must report it to the Compliance Lead within 24 hours
- The Compliance Lead confirms whether the event constitutes an AI incident
- An incident reference number is assigned
- Severity is classified

### Phase 2 — Containment

- Suspend or restrict the AI system if there is ongoing risk of harm
- Preserve logs and evidence for investigation
- Notify the Incident Response Team
- Assess whether any personal data breach has occurred

### Phase 3 — Investigation

- Identify the root cause of the incident
- Determine the scope of impact — how many individuals were affected
- Assess whether the incident constitutes a regulatory breach
- Document all findings

### Phase 4 — Remediation

- Correct the underlying issue causing the incident
- Retrain or reconfigure the model where required
- Implement additional controls to prevent recurrence
- Validate that the fix is effective before resuming normal operation

### Phase 5 — Notification

- Notify affected individuals where required
- Notify regulators where required (EU AI Act, GDPR, NDPA)
- Notify senior leadership for Critical and High severity incidents
- Document all notifications

### Phase 6 — Post-Incident Review

- Conduct a post-incident review within 2 weeks of resolution
- Document timeline, root cause, response actions, and lessons learned
- Update the AI Risk Assessment for the affected system
- Update this plan if gaps in the response process were identified

---

## 6. Regulatory Notification Requirements

| Regulation | Notification Trigger | Timeframe | Notifying Authority |
|---|---|---|---|
| EU AI Act | Serious incident involving High Risk AI system | Immediately upon becoming aware | National market surveillance authority |
| GDPR | Personal data breach | Within 72 hours | Supervisory authority |
| NDPA 2023 | Personal data breach | Within 72 hours | NDPC |

---

## 7. Evidence to Preserve

For every AI incident the following must be preserved:

- [ ] System logs at the time of the incident
- [ ] Model version and configuration at the time of the incident
- [ ] Data inputs that triggered the incident
- [ ] Outputs produced by the system
- [ ] Communications related to the incident
- [ ] Actions taken in response

---

## 8. Communication Templates

### Internal Notification

Subject: AI Incident Notification — [Incident Reference]

An AI incident has been identified involving [System Name]. Severity: [Level]. The Incident Response Team has been activated. Further updates will follow within [timeframe]. Please direct any questions to [Incident Commander Name].

### Affected Individual Notification

Dear [Name],

We are writing to inform you that an issue was identified with an AI system used by [Organisation Name] that may have affected a decision or output relating to you. [Describe the incident in plain language.] We have taken the following steps to address this: [List actions taken.] You have the right to request human review of any decision made about you. Please contact [contact details] if you have questions or wish to exercise this right.

---

## 9. AI Incident Log

| Incident ID | Date | System | Severity | Description | Status | Date Resolved |
|---|---|---|---|---|---|---|
| | | | | | | |
| | | | | | | |

---

## 10. Testing and Review

This plan is tested through a tabletop exercise at least annually. It is reviewed and updated following any actual incident or significant change to the organisation's AI systems.

---

## Approval

| Role | Name | Signature | Date |
|---|---|---|---|
| Compliance Lead | | | |
| Chief Technology Officer | | | |
| CEO or Director | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*
