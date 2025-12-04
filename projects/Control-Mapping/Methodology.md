# 🔍 Methodology  
### How This Control Mapping Was Created

This document explains the exact process used to build the AWS Security Hub → NIST 800-53 Rev5 control mapping. The goal is to demonstrate clear methodology, traceability, and maturity in GRC practices — the same approach used in real vendor risk and compliance programs.

---

## 1️⃣ Scope Definition  
Before any mapping work began, I defined the scope clearly:

- **Framework A:** AWS Security Hub security standards  
- **Framework B:** NIST 800-53 Rev5 (moderate baseline)  
- **Mapping Goal:** Establish traceability between AWS automated controls and corresponding NIST control families  
- **Use Case:** Evidence readiness, gap analysis, and audit preparation  

**Outcome:** A clean, understandable mapping that aligns cloud-native controls with federal security baselines.

---

## 2️⃣ Source Documentation Collection  
All mappings were based on publicly available, authoritative sources:

- AWS Security Hub control reference  
- AWS Audit Manager documentation  
- NIST SP 800-53 Rev5 (official NIST publication)  
- NIST control families & assessment objectives  

No proprietary or confidential content was used.

---

## 3️⃣ Control Breakdown  
Each AWS Security Hub control was analyzed for:

- **Purpose of the control**  
- **What the control enforces**  
- **Whether it is automated or partially automated**  
- **Which NIST objectives it supports**  

Controls were categorized by their **primary security domain**:
- Access Control  
- Logging & Monitoring  
- Network Protections  
- Data Protection  
- Incident Response  
- Configuration Management  

---

## 4️⃣ Direct Control Mapping  
Using the control objectives from both frameworks, each AWS Security Hub control was mapped to:

- 1 primary NIST control  
- 0–3 secondary supporting NIST controls  
- Notes explaining *why* the mapping is valid  

Mappings avoid one-to-many inflation unless justified.  
Every mapping includes a **reasoning statement** written in plain, auditor-friendly language.

---

## 5️⃣ Validation Pass  
After initial mapping, the mappings were validated against:

- Overlapping NIST families (AC, AU, CM, CP, IR, MP, PL, RA, SC, SI)  
- AWS well-architected guidance  
- NIST assessment objectives (AOs)

This ensures:
- No gaps  
- No duplicated or incorrect mappings  
- Clear traceability for audit teams  

---

## 6️⃣ Documentation Standards  
To ensure recruiter readability and audit-level clarity:

- Clean formatting  
- No unexplained abbreviations  
- Notes written in business-friendly language  
- Clear separation between control source, mapping, and justification  

This mirrors real GRC documentation — structured, defensible, and review-ready.

---

## 7️⃣ Final Output  
The completed mapping:

- Helps identify cloud security gaps  
- Supports audit readiness for NIST-aligned programs  
- Demonstrates ability to translate technical controls into compliance requirements  
- Reflects real-world vendor risk and security governance workflows  

---

## ✅ Summary  
This methodology demonstrates practical experience in:

- Control mapping  
- Framework interpretation  
- AWS security controls  
- Compliance documentation  
- NIST 800-53 governance work  
- Attention to detail and repeatable processes  

It's a polished example of how I approach structured, high-quality GRC work with clarity and audit-focused precision.

