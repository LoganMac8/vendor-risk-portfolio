# Exceptions and Impact Analysis  
_Safe, paraphrased summary of observed control deviations_

This document outlines the exceptions identified in the SOC 2 testing results, along with my analysis of their cause, impact, and recommended remediation steps. No confidential or vendor-specific details are disclosed.

---

## ⚠️ Exception 1: Periodic Review Performed Late

### **Why the Control Failed**  
The scheduled review activity was completed a short time after the expected due date. Evidence showed this was an isolated timing issue rather than a process breakdown.

### **Impact**  
Low.  
The delay did not prevent the control from functioning overall and had no effect on data confidentiality or system security.

### **Risk Severity**  
**Low**

### **Recommended Remediation**  
- Automate reminders for recurring security tasks  
- Implement a tracking mechanism with ownership assignments  
- Document late completions for transparency  

---

## ⚠️ Exception 2: Documentation Not Fully Updated

### **Why the Control Failed**  
Supporting documentation for a security control had outdated sections and did not reflect the most recent process revisions.

### **Impact**  
Low.  
Although the documentation lagged behind, the control itself operated effectively.

### **Risk Severity**  
**Low**

### **Recommended Remediation**  
- Update outdated policy or procedure documents  
- Implement a yearly documentation review cycle  
- Assign documentation owners for key processes  

---

## ⚠️ Exception 3: Single Deviation in Control Execution

### **Why the Control Failed**  
A task associated with an operational control was missed once during the audit period but completed consistently for all other cycles.

### **Impact**  
Low to Moderate (depending on context).  
No incidents resulted from the miss, but it demonstrates a dependency on manual oversight.

### **Risk Severity**  
**Low**

### **Recommended Remediation**  
- Add automation where possible  
- Require peer review for recurring operational tasks  
- Add a secondary approval step for high-impact controls  

---

## 🎯 Overall Risk Conclusion
The exceptions identified do not indicate systemic control failures. All deviations were isolated, low-impact, and easily addressed through standard remediation measures.

Combined Risk Rating: **Low**  
Recommended Vendor Status: **Approved with minor follow-up items**

---
