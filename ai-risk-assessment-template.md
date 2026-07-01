# AI Risk Assessment Template

**Version:** 1.0  
**Last Updated:** June 2026  
**Organisation:**  
**AI System Name:**  
**System Owner:**  
**Assessor:**  
**Assessment Date:**  
**EU AI Act Risk Classification:** Minimal / Limited / High / Prohibited  

---

## 1. System Overview

**What does this AI system do?**

**What business problem does it solve?**

**Who uses this system?**

**What data does it process?**

**Where is it deployed?** (Internal only / Customer facing / Third party)

**Is this system developed internally or provided by a vendor?**

---

## 2. Risk Identification

Identify all risks associated with this AI system across the following categories:

### 2.1 Data Risks

| Risk | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation |
|---|---|---|---|---|
| Training data contains biased or unrepresentative samples | | | | |
| Personal data processed without adequate legal basis | | | | |
| Data quality issues affecting model accuracy | | | | |
| Unauthorised access to training or inference data | | | | |
| Data used beyond its original purpose | | | | |

### 2.2 Model Risks

| Risk | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation |
|---|---|---|---|---|
| Model produces inaccurate or unreliable outputs | | | | |
| Model exhibits discriminatory behaviour toward protected groups | | | | |
| Model is vulnerable to adversarial attacks or manipulation | | | | |
| Model behaviour changes unexpectedly after updates | | | | |
| Model is used for purposes beyond its intended scope | | | | |

### 2.3 Operational Risks

| Risk | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation |
|---|---|---|---|---|
| Insufficient human oversight of automated decisions | | | | |
| Staff lack training to use or oversee the system appropriately | | | | |
| No process to detect or respond to model failures | | | | |
| Vendor dependency creates single point of failure | | | | |
| System deployed without adequate testing | | | | |

### 2.4 Regulatory and Compliance Risks

| Risk | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation |
|---|---|---|---|---|
| System classified as High Risk under EU AI Act without conformity assessment | | | | |
| Processing of personal data without GDPR compliance | | | | |
| Lack of transparency to users about AI decision making | | | | |
| No mechanism for users to contest AI decisions | | | | |
| System not registered in EU AI Act database where required | | | | |

### 2.5 Reputational Risks

| Risk | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation |
|---|---|---|---|---|
| AI system makes a high profile error causing public harm | | | | |
| Discriminatory outcomes damage brand reputation | | | | |
| Lack of explainability erodes customer trust | | | | |

---

## 3. Risk Scoring Guide

| Score | Likelihood | Impact |
|---|---|---|
| 1 | Very unlikely | Negligible impact |
| 2 | Unlikely | Minor impact |
| 3 | Possible | Moderate impact |
| 4 | Likely | Significant impact |
| 5 | Very likely | Severe impact |

**Risk Score = Likelihood x Impact**

| Risk Score | Risk Level | Action Required |
|---|---|---|
| 1-4 | Low | Monitor, review annually |
| 5-9 | Medium | Implement controls, review quarterly |
| 10-16 | High | Immediate action required |
| 17-25 | Critical | Do not deploy until mitigated |

---

## 4. Human Oversight Assessment

- [ ] Human review is required before any automated decision takes effect
- [ ] Users are informed when a decision is made by an AI system
- [ ] Users can request human review of AI decisions
- [ ] A process exists to override or correct AI decisions
- [ ] Staff responsible for oversight are trained on the system

---

## 5. Explainability Assessment

- [ ] The system can explain why it produced a specific output
- [ ] Explanations are understandable to non-technical users
- [ ] Explanations are provided to affected individuals on request
- [ ] Decision logic is documented and available for audit

---

## 6. Bias and Fairness Assessment

- [ ] Training data has been reviewed for bias
- [ ] Model outputs have been tested across demographic groups
- [ ] Discriminatory outcomes have been identified and addressed
- [ ] Ongoing monitoring for bias is in place

---

## 7. Overall Risk Summary

**Highest Risk Identified:**

**Key Mitigations Required:**

**Recommendation:** Approve for deployment / Approve with conditions / Do not deploy

**Conditions for Approval (if applicable):**

---

## 8. Sign Off

| Role | Name | Signature | Date |
|---|---|---|---|
| Assessor | | | |
| AI System Owner | | | |
| Compliance Lead | | | |
| Approving Authority | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*
