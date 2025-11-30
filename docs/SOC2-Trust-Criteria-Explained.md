# SOC 2 Trust Service Criteria — Explained for Vendor Risk Analysts

The Trust Service Criteria (TSC) are the backbone of SOC 2. They define the security principles auditors evaluate when determining whether a vendor protects customer data effectively.  
This guide breaks down each criterion in clear, practical terms with examples, risks, and how Vendor Risk Analysts should use them.

---

# 🔐 1. Security (Common Criteria) — **Required for all SOC 2 reports**

Security refers to protecting systems and data from unauthorized access, disclosure, or modifications.  
Every SOC 2 engagement includes Security controls.

### **Examples of Security controls**
- Multi-factor authentication (MFA)  
- Role-based access control (RBAC)  
- Logging and monitoring  
- Network segmentation  
- Security awareness training  
- Vulnerability scanning & patching  

### **What auditors check**
- Whether access is limited to authorized users  
- Whether activity logs exist and are reviewed  
- Whether security incidents are detected and resolved  

### **Risks if controls are weak**
- Account compromise  
- Credential stuffing attacks  
- Unauthorized system changes  
- Undetected insider threats  

### **Vendor Risk Analyst perspective**
Security is the foundation of your vendor assessment. If Security controls fail, it affects every other TSC.

---

# 📦 2. Availability

Availability focuses on system reliability and uptime commitments.  
Controls ensure a vendor can deliver services consistently and recover quickly from disruptions.

### **Examples of Availability controls**
- Uptime monitoring dashboards  
- Incident response processes  
- Disaster recovery (DR) plans  
- Redundant infrastructure  
- Capacity management  

### **What auditors check**
- Whether DR plans exist and are tested  
- Whether vendors track SLAs  
- Whether incidents are logged and resolved  

### **Risks if controls are weak**
- Outages impacting business operations  
- SLA violations  
- Service instability  
- Poor vendor reliability  

### **Vendor Risk Analyst perspective**
You evaluate whether the vendor can stay operational during failures.  
This matters heavily for SaaS, payment services, and critical infrastructure vendors.

---

# 📊 3. Processing Integrity

Processing Integrity ensures systems process data completely, accurately, and on time.

### **Examples of Processing Integrity controls**
- Input validation  
- Error detection mechanisms  
- Reconciliation procedures  
- Batch processing checks  
- Change management  

### **What auditors check**
- Whether data is processed correctly  
- Whether errors are logged and corrected  
- Whether unauthorized changes can be made  

### **Risks if controls are weak**
- Corrupted data  
- Duplicate transactions  
- Incorrect or delayed outputs  
- Undetected system errors  

### **Vendor Risk Analyst perspective**
This matters most for vendors handling transactions, analytics, automation, or financial data.

---

# 🕵️‍♂️ 4. Confidentiality

Confidentiality covers protecting sensitive information from unauthorized disclosure.  
This applies to source code, business plans, internal documents, or customer-specific data not considered personal data.

### **Examples of Confidentiality controls**
- Encryption at rest and in transit  
- Data loss prevention (DLP)  
- Access control (least privilege)  
- Secure key management  
- Data classification policies  

### **What auditors check**
- Whether encryption is implemented properly  
- Whether access to sensitive data is restricted  
- Whether data retention and disposal practices exist  

### **Risks if controls are weak**
- Data leaks  
- Insider misuse  
- Unencrypted backups  
- Exposure of proprietary or customer information  

### **Vendor Risk Analyst perspective**
Evaluate whether the vendor protects any non-public data your organization shares with them.

---

# 🧑‍💻 5. Privacy

Privacy specifically refers to **personal** data — how it is collected, retained, used, shared, and disposed of.

This criterion maps heavily to frameworks like:  
- GDPR  
- CCPA  
- HIPAA (where applicable)  
- Company privacy notices  

### **Examples of Privacy controls**
- Consent management  
- Data subject rights processes  
- Data retention and deletion schedules  
- Privacy impact assessments  
- Transparent privacy notices  

### **What auditors check**
- Whether personal data is handled according to commitments  
- Whether users can access, correct, or delete their data  
- Whether retention schedules are followed  

### **Risks if controls are weak**
- Regulatory penalties  
- Legal liability  
- Damaged customer trust  
- Privacy incidents or breaches  

### **Vendor Risk Analyst perspective**
If the vendor processes **any** customer PII or employee PII, Privacy controls become critical in risk scoring.

---

# 🧩 How the Trust Criteria Work Together

Although the criteria are distinct, they overlap significantly:

- **Security** is required and supports all other criteria  
- **Availability** depends on strong Security  
- **Confidentiality** requires proper Access Control  
- **Processing Integrity** relies on Logging, Monitoring, and Change Management  
- **Privacy** depends on both Security and Confidentiality  

Understanding these relationships helps you evaluate the vendor’s maturity and the completeness of their control environment.

---

# 🎯 How Vendor Risk Analysts Apply the TSC in Real Assessments

When reviewing a SOC 2, you use the TSC to:

1. Prioritize controls during review  
2. Identify gaps with the highest business impact  
3. Score risk levels (Low/Medium/High/Critical)  
4. Create remediation recommendations  
5. Determine whether to approve or reject a vendor  

The stronger your understanding of the Trust Criteria, the more accurately you can review vendors.

---

**Author:** Logan McDermott  
