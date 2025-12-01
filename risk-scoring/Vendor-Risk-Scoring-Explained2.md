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

