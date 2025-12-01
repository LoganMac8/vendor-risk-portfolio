# Vendor Risk Scoring Model  
_A practical scoring method based on Likelihood × Impact_

This model is used to quantify vendor risk using a simple, industry-standard formula:  
**Risk Score = Likelihood × Impact**

Both Likelihood and Impact are rated on a scale of **1–5**, resulting in a total score between **1 and 25**.  
Scores determine the vendor’s overall risk level and required due diligence.

---

## 🔢 1. Scoring Categories

### **Likelihood (1–5)**
How likely a security, privacy, or operational issue is to occur based on:
- Vendor’s control environment  
- Service type and architecture  
- History of incidents  
- Complexity and exposure  
- Subservice dependencies  

**Scale:**
| Score | Likelihood Description |
|-------|-------------------------|
| 1 | Rare — minimal chance of occurring |
| 2 | Unlikely — possible but not expected |
| 3 | Possible — reasonable chance under the right conditions |
| 4 | Likely — expected to occur at some point |
| 5 | Almost Certain — high probability of occurring |

---

### **Impact (1–5)**
The severity of consequences if the risk occurs, based on:
- Data sensitivity  
- Regulatory requirements  
- System criticality  
- Financial impact  
- Customer or operational disruption  

**Scale:**
| Score | Impact Description |
|-------|---------------------|
| 1 | Negligible — no meaningful harm |
| 2 | Minor — limited impact, easy to recover |
| 3 | Moderate — noticeable issue, some business disruption |
| 4 | Major — significant operational or financial impact |
| 5 | Severe — major outage, breach, or regulatory exposure |

---

## 🔢 2. Risk Score Formula

Risk Score = Likelihood × Impact


Score range: **1–25**

Example:
- Likelihood = 4  
- Impact = 5  
- Risk Score = 4 × 5 = **20 (High)**

---

## 🎯 3. Risk Level Thresholds

Use the following thresholds to categorize vendor risk:

| Risk Score | Risk Level | Meaning |
|-----------|-------------|---------|
| **1–5** | **Low** | Minimal risk; standard contract + basic due diligence |
| **6–10** | **Medium** | Some concerns; review evidence and validate controls |
| **11–16** | **High** | Requires deeper review; remediation or compensating controls needed |
| **17–25** | **Critical** | Significant risk; executive approval, strong controls, or do not onboard |

---

## 📝 4. Examples of Risk Scoring

### **Example 1 — Low Risk Vendor**
- Vendor handles no sensitive data  
- Uses strong controls  
- No integrations  

Likelihood: **1**  
Impact: **2**  
Risk Score: **2 (Low)**

---

### **Example 2 — Medium Risk Vendor**
- SaaS tool used by internal team  
- Stores internal-only data  
- SOC 2 provided  

Likelihood: **2**  
Impact: **4**  
Risk Score: **8 (Medium)**

---

### **Example 3 — High Risk Vendor**
- Vendor handles customer PII  
- Uses subservice providers  
- Moderate control gaps  

Likelihood: **3**  
Impact: **5**  
Risk Score: **15 (High)**

---

### **Example 4 — Critical Risk Vendor**
- Vendor processes regulated data (PII/PCI/PHI)  
- Weak controls or no SOC 2/ISO  
- High dependency for core operations  

Likelihood: **5**  
Impact: **5**  
Risk Score: **25 (Critical)**

---

## 🧭 5. How Risk Scores Drive Decisions

| Risk Level | Required Actions |
|------------|------------------|
| **Low** | Standard review; approve with basic controls |
| **Medium** | Validate SOC 2/ISO; review questionnaire responses |
| **High** | Require remediation; escalate to security leadership |
| **Critical** | Executive approval needed; often not recommended |

---

## ✔ Final Summary
This 1–25 scoring model provides a simple, repeatable way to evaluate vendor risk.  
It ensures consistency across assessments and aligns with common frameworks used in TPRM programs.

