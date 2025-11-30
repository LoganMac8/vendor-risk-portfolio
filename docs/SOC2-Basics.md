# SOC 2 Basics — A Practical Guide for Vendor Risk Analysts

SOC 2 (System and Organization Controls 2) is one of the most widely used security frameworks for evaluating whether a vendor can securely handle customer data. Vendor Risk Analysts rely heavily on SOC 2 reports to understand a vendor’s control environment, uncover weaknesses, and determine risk levels during due diligence.

This document summarizes the essential concepts every Vendor Risk Analyst must know.

---

## 📌 What Is SOC 2?
SOC 2 is an attestation framework developed by the AICPA that evaluates how well an organization safeguards data based on the Trust Service Criteria (TSC).  
It focuses on **controls**, not financial accuracy, and is commonly required when onboarding SaaS, cloud, or third-party service providers.

---

## 📌 Type I vs. Type II (Critical Interview Question)

### **SOC 2 Type I**
Evaluates whether controls are **designed effectively** at a single point in time.

- Snapshot audit  
- Tests design only (not long-term performance)  
- Often used by early-stage companies  

### **SOC 2 Type II**
Evaluates whether controls are both **designed** and **operating effectively** over a period (typically 3–12 months).

- Covers real-world evidence  
- Demonstrates sustained security practices  
- **Most valuable for Vendor Risk assessments**  
- Preferred by nearly all enterprises

**Interview Tip:**  
> “Type II holds more weight because it proves controls are consistently working, not just documented.”

---

## 📌 Why SOC 2 Matters in Vendor Risk Management

Vendor Risk Analysts use SOC 2 reports to:

- Validate a vendor’s security posture  
- Confirm core controls like access control, MFA, logging, and encryption  
- Identify audit exceptions and evaluate their risk impact  
- Determine the vendor’s risk tier (Low/Medium/High)  
- Support go/no-go decisions in vendor onboarding  
- Ensure third parties meet internal and regulatory requirements  

---

## 📌 Trust Service Criteria (TSC) Overview

The SOC 2 framework is built around five categories.  
**Security** is mandatory — the other four are optional based on the vendor’s services.

### **1. Security (Common Criteria) — REQUIRED**
Protects systems and data from unauthorized access.  
Examples:  
- MFA  
- Logging and monitoring  
- Access control  
- Firewalls  

### **2. Availability**
Ensures systems remain reliable and meet uptime commitments.  
Examples:  
- Uptime monitoring  
- Redundancy  
- Incident response  

### **3. Processing Integrity**
Ensures data is processed accurately, completely, and on time.  
Examples:  
- Input validation  
- Error detection  

### **4. Confidentiality**
Protects sensitive information from inappropriate disclosure.  
Examples:  
- Encryption at rest/in transit  
- Data classification  
- Role-based access

### **5. Privacy**
Protects personal data according to commitments and regulations.  
Examples:  
- Data retention  
- Consent mechanisms  
- Privacy notices  

---

## 📌 Core Components of a SOC 2 Report

The sections Vendor Risk Analysts care about most:

### **1. Management Assertion**
Vendor’s internal statement about the system and controls.

### **2. Auditor’s Opinion**
The auditor’s conclusion:  
- Unqualified (clean)  
- Qualified (issues)  
- Adverse (major failures)  
- Disclaimer (insufficient evidence)

### **3. System Description**
Critical for understanding:  
- What is in scope  
- Boundaries of the system  
- Services provided  
- Infrastructure and processes  

### **4. Controls & Testing**
Lists the vendor’s controls, the auditor’s test procedures, and the results.

### **5. Exceptions & Findings**
Where problems are identified.  
Vendor Risk Analysts evaluate the **severity, root cause, impact, and remediation**.

### **6. Subservice Organizations**
Other companies the vendor relies on (e.g., AWS, Okta).  
Important for determining **dependency risk**.

---

## 📌 What Vendor Risk Analysts Look For in a SOC 2

- Missing MFA  
- Weak access control  
- No logging or alerting  
- Encryption failures  
- Incident response gaps  
- High number of exceptions  
- Reliance on subservice organizations without monitoring  
- Outdated policies  
- Incomplete monitoring evidence  

A clear, structured approach to identifying these issues is crucial for making informed risk decisions.

---

## 📌 How to Use SOC 2 in Due Diligence (Your Workflow)

1. Confirm the report is **Type II** (preferred).  
2. Check the **audit period** for freshness (last 12 months ideal).  
3. Review the **scope** to ensure relevant systems are included.  
4. Analyze the **auditor’s opinion** for major issues.  
5. Review **controls and test results** for failures.  
6. Assess **exceptions and gaps** and determine risk severity.  
7. Document risks and recommended remediation.  
8. Assign a **risk score** in your vendor scoring model.

---

## 📌 Final Notes for Interviewers and Recruiters

Being able to read, interpret, and summarize a SOC 2 report is one of the **top skills** hiring managers test for in Vendor Risk, TPRM, and GRC roles.

This foundational knowledge demonstrates:

- Audit comprehension  
- Understanding of control effectiveness  
- Awareness of risk impact  
- Ability to perform due diligence  
- Strong analytical skills  

---

**Author:** Logan McDermott  
