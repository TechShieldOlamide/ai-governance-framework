# EU AI Act Risk Classification Checklist

**Version:** 1.0  
**Last Updated:** June 2026  
**Organisation:**  
**AI System Being Assessed:**  
**Assessor:**  
**Assessment Date:**  

---

## Purpose

The EU AI Act classifies AI systems into four risk levels, each with different compliance obligations. This checklist helps you determine the correct risk classification for each AI system in your organisation.

---

## Step 1 — Check for Prohibited Practices

If your AI system does any of the following it is prohibited under the EU AI Act and must not be deployed:

- [ ] Uses subliminal techniques to manipulate behaviour without awareness
- [ ] Exploits vulnerabilities of specific groups (age, disability, social situation)
- [ ] Performs social scoring by public authorities
- [ ] Uses real-time remote biometric identification in public spaces (with limited exceptions)
- [ ] Infers emotions in workplace or educational settings
- [ ] Creates facial recognition databases by scraping the internet
- [ ] Predicts criminal behaviour based on profiling

**If any box above is checked — STOP. This system cannot be deployed under the EU AI Act.**

---

## Step 2 — Check for High Risk Classification

AI systems are classified as High Risk if they are used in any of the following areas:

**Critical Infrastructure**
- [ ] Safety components of critical infrastructure (transport, water, gas, electricity)

**Education and Vocational Training**
- [ ] Determining access to educational institutions
- [ ] Evaluating learning outcomes or student performance

**Employment and Workers Management**
- [ ] Recruitment and selection of candidates
- [ ] Making decisions about promotion, termination, or task allocation
- [ ] Monitoring and evaluating employee performance

**Essential Private and Public Services**
- [ ] Credit scoring or assessing creditworthiness
- [ ] Risk assessment for life and health insurance
- [ ] Emergency services dispatch

**Law Enforcement**
- [ ] Assessing risk of offending or reoffending
- [ ] Detecting emotional states during investigations
- [ ] Analysing evidence for crime detection

**Migration and Border Control**
- [ ] Assessing migration and asylum applications
- [ [ Detecting threats at border crossings

**Administration of Justice**
- [ ] Assisting courts in researching and interpreting facts

**If any box above is checked — this system is HIGH RISK and requires conformity assessment before deployment.**

---

## Step 3 — Check for Limited Risk Classification

AI systems have Limited Risk if they:

- [ ] Interact directly with humans (chatbots, virtual assistants) — transparency obligation applies
- [ ] Generate synthetic content (images, audio, video, text) — labelling obligation applies
- [ ] Use emotion recognition or biometric categorisation

**If any box above is checked — this system is LIMITED RISK and has transparency obligations.**

---

## Step 4 — Minimal Risk

If none of the above apply, the system is classified as Minimal Risk with no specific EU AI Act obligations, though voluntary codes of practice are recommended.

---

## Classification Summary

| Question | Response |
|---|---|
| Does the system fall under prohibited practices? | Yes / No |
| Does the system qualify as High Risk? | Yes / No |
| Does the system qualify as Limited Risk? | Yes / No |
| Final Risk Classification | Prohibited / High / Limited / Minimal |

---

## Compliance Obligations by Risk Level

| Risk Level | Key Obligations |
|---|---|
| Prohibited | Cannot be deployed |
| High Risk | Conformity assessment, technical documentation, human oversight, data governance, accuracy and robustness requirements, registration in EU database |
| Limited Risk | Transparency obligations — users must be informed they are interacting with AI |
| Minimal Risk | No mandatory obligations, voluntary codes of practice recommended |

---

## High Risk Compliance Checklist

If your system is classified as High Risk, complete the following before deployment:

- [ ] Risk management system established and documented
- [ ] Training data governance process documented
- [ ] Technical documentation prepared
- [ ] Automatic logging and record-keeping enabled
- [ ] Transparency information prepared for users
- [ ] Human oversight measures implemented
- [ ] Accuracy, robustness, and cybersecurity requirements assessed
- [ ] Conformity assessment completed
- [ ] System registered in EU AI Act database
- [ ] Post-market monitoring plan established

---

## Assessment Sign Off

| Role | Name | Signature | Date |
|---|---|---|---|
| Assessor | | | |
| AI System Owner | | | |
| Compliance Lead | | | |

---

*Developed by TrustGrid Technology Limited — github.com/TechShieldOlamide*
