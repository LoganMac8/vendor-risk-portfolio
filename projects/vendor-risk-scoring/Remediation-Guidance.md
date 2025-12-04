# Vendor Risk Remediation Guidance  
This document provides standardized remediation recommendations based on common gaps identified during vendor assessments.  
Recommendations are aligned with SOC 2, ISO 27001 Annex A, NIST 800-53, and industry TPRM expectations.

---

## 1. Access Control Remediation  

### **1.1 Missing or Weak MFA**
**Issue:** Vendor does not enforce MFA for admin or remote access  
**Recommended Fix:**  
- Implement MFA for all privileged accounts  
- Require MFA for SSO, VPN, and cloud consoles  
- Align with NIST IA-2 and SOC 2 CC6.3  

---

### **1.2 Excessive Privilege / No Role Separation**
**Issue:** Users have broad or unnecessary access  
**Recommended Fix:**  
- Implement least privilege and role-based access control  
- Document access roles and approval workflows  
- Conduct quarterly access reviews  

---

### **1.3 Incomplete Offboarding**
**Issue:** Delays in removing terminated employee accounts  
**Recommended Fix:**  
- Establish a documented offboarding process  
- Remove or disable accounts within 24 hours  
- Add automated HR-to-IT notifications  

---

## 2. Data Protection Remediation  

### **2.1 No Encryption at Rest or Transit**
**Issue:** Sensitive data not fully encrypted  
**Recommended Fix:**  
- Apply TLS 1.2+ for data in transit  
- Use AES-256 or equivalent for data at rest  
- Implement encryption key rotation  

---

### **2.2 Insufficient Data Classification**
**Issue:** Vendor does not classify data by sensitivity  
**Recommended Fix:**  
- Establish a data classification policy  
- Train staff to label and handle data accordingly  
- Align with ISO 27001 A.8 and SOC 2 CC6.x  

---

### **2.3 Customer-Owned Keys Not Supported**
**Issue:** Vendor does not allow customer KMS keys  
**Recommended Fix:**  
- Offer tenant-managed key options (if feasible)  
- Document key governance for transparency  

---

## 3. Logging & Monitoring Remediation  

### **3.1 Limited Log Retention**
**Issue:** Logs retained for less than 90 days  
**Recommended Fix:**  
- Increase retention to 12 months for security events  
- Store logs in tamper-resistant systems (SIEM)  

---

### **3.2 No Continuous Monitoring**
**Issue:** Vendor relies on manual or infrequent review  
**Recommended Fix:**  
- Implement automated alerting  
- Centralize logs across infrastructure  
- Align with NIST AU-6 and SOC 2 CC7.x  

---

### **3.3 Incomplete Incident Response Process**
**Issue:** Incident plan is not fully tested  
**Recommended Fix:**  
- Perform annual tabletop exercises  
- Define roles, responsibilities, and escalation paths  
- Notify customers per regulatory requirements  

---

## 4. Vulnerability Management Remediation  

### **4.1 No Routine Scanning**
**Issue:** Lack of scheduled vulnerability scanning  
**Recommended Fix:**  
- Implement monthly internal and external scans  
- Assign SLAs for critical vulnerability remediation  

---

### **4.2 No Penetration Testing**
**Issue:** No penetration testing in the last 12 months  
**Recommended Fix:**  
- Conduct annual independent penetration testing  
- Provide summaries to customers under NDA  

---

### **4.3 Slow Patch Management**
**Issue:** Critical patches not applied promptly  
**Recommended Fix:**  
- Establish risk-based patching timelines:  
  - Critical → 7 days  
  - High → 30 days  
- Implement automated patch reporting  

---

## 5. Cloud & Infrastructure Remediation  

### **5.1 Misconfigured Cloud Resources**
**Issue:** Open ports, public S3 buckets, weak IAM controls  
**Recommended Fix:**  
- Run CIS benchmark assessments  
- Enforce IAM least privilege policies  
- Set default encryption and logging for cloud storage  

---

### **5.2 Weak Network Segmentation**
**Issue:** Flat internal network  
**Recommended Fix:**  
- Segment workloads by sensitivity  
- Restrict lateral movement  
- Document network diagrams and firewall rules  

---

## 6. Business Risk Remediation  

### **6.1 Lack of Third-Party Oversight**
**Issue:** Vendor does not assess their subprocessors  
**Recommended Fix:**  
- Maintain an up-to-date subprocessor list  
- Perform annual assessments  
- Include security obligations in contracts  

---

### **6.2 Missing BCP/DR Testing**
**Issue:** No record of recent business continuity testing  
**Recommended Fix:**  
- Perform annual BCP/DR tests  
- Document RTO and RPO metrics  
- Share summaries upon request  

---

## 7. Documentation & Policy Remediation  

### **7.1 Missing Core Policies**
**Issue:** Vendor cannot provide standard security policies  
**Recommended Fix:**  
- Publish policies for access control, incident response, encryption, and vendor management  
- Review policies annually  

---

### **7.2 Incomplete Evidence Packages**
**Issue:** Vendor fails to provide SOC 2, pentest reports, or security docs  
**Recommended Fix:**  
- Create a standardized customer security packet  
- Include SOC reports, IR plan, security whitepaper, and data flow diagram  

---

## 8. General Recommendations  

### **8.1 Improve Transparency**
- Maintain a customer-facing Trust Center  
- Publish certifications, uptime dashboards, and architecture summaries  

### **8.2 Strengthen Employee Training**
- Conduct annual security awareness training  
- Provide phishing simulation campaigns  
- Require acknowledgement tracking  

### **8.3 Establish Risk-Tracking Metrics**
- Track control gaps, remediation timelines, and incident metrics  
- Provide dashboards for internal leadership  

---

## 9. Conclusion  
This remediation guidance ensures consistent, actionable recommendations across all vendor assessments.  
It helps reduce risk, strengthen vendor accountability, and maintain audit-ready compliance across the Third-Party Risk Management program.

