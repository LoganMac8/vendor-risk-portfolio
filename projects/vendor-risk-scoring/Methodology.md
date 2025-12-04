# Vendor Risk Scoring Methodology  
This document explains how the vendor scoring model evaluates third-party risk using a structured, quantitative, repeatable approach. The methodology is aligned with common GRC and TPRM practices used in modern enterprises.

---

## 1. Purpose of the Scoring Method  
The scoring method ensures every vendor is assessed using **the same objective criteria**, reducing subjectivity and improving auditability.  
The model identifies vendors that require deeper assessment based on:

- Sensitivity of data involved  
- Strength of the vendor’s control environment  
- Regulatory exposure  
- Operational and financial dependency  
- Technology surface area and architectural complexity  

---

## 2. Quantitative Scoring Formula  
The model uses a **Likelihood × Impact** formula commonly used across risk management functions.

### Final Score  

Final Risk Score = Likelihood Score × Impact Score


### Score Range  
- **1–4** → Low Risk  
- **5–12** → Moderate Risk  
- **13–20** → High Risk  
- **21–25** → Critical Risk  

---

## 3. Scoring Dimensions  
Each vendor is evaluated across defined categories. Scores range from **1 (Low)** to **5 (Very High)**.

### 3.1 Likelihood Factors  
1. **Control Maturity**  
   - Based on SOC reports, questionnaires, policies, test history  
2. **History of Incidents**  
   - Breaches, outages, regulatory findings  
3. **Technology Exposure**  
   - Cloud architecture, integrations, attack surface  
4. **Vulnerability Management Strength**  
5. **Operational Stability & Staffing**  

### 3.2 Impact Factors  
1. **Data Sensitivity**  
   - Internal, confidential, customer, regulated  
2. **Regulatory Obligations**  
   - GDPR, CCPA, HIPAA, PCI-DSS, SOX  
3. **Business Criticality**  
   - Dependency level and downstream impact  
4. **Financial Exposure**  
5. **Customer or Reputation Risk**  

---

## 4. Weighting  
Certain factors carry more weight depending on business needs. Example weighting:

| Category | Weight |
|---------|--------|
| Data Sensitivity | 30 percent |
| Control Maturity | 25 percent |
| Business Criticality | 20 percent |
| Technology Exposure | 15 percent |
| Regulatory Impact | 10 percent |

Weighted scoring ensures high-impact areas drive the final result.

---

## 5. Evidence Sources  
Vendor scores must be based on **verifiable evidence**, not assumption.  
Accepted evidence types include:

- SOC 2 Type II reports  
- ISO 27001 certificates  
- Penetration test summaries  
- Security questionnaires  
- Architectural diagrams  
- Data flow diagrams  
- Policies and procedures  
- Incident history reports  

---

## 6. Tier Mapping  
The final score automatically determines the vendor’s **risk tier**:

| Tier | Score Range | Due Diligence Requirements |
|------|-------------|----------------------------|
| Low | 1–4 | Basic questionnaire |
| Moderate | 5–12 | Questionnaire + evidence review |
| High | 13–20 | Deep-dive review + remediation tracking |
| Critical | 21–25 | Executive review, mandatory controls, annual reassessment |

---

## 7. Reassessment Triggers  
Vendors must be rescored when:

- A major incident occurs  
- The product architecture changes  
- New types of data are shared  
- Regulations change  
- A contract renewal requires a new review  

---

## 8. Audit Traceability  
All scoring decisions must be documented with:

- Evidence references  
- Calculation logs  
- Reviewer name and date  
- Vendor tier justification  
- Any remediation actions required  

This ensures readiness for internal audit, external audit, or regulatory review.

---

