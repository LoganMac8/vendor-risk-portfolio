# Vendor Risk Scoring Explained

This document explains the approach used to evaluate a vendor's security risk using a structured, repeatable scoring model. Vendor Risk Analysts rely on this process to determine how much risk a vendor introduces, how severe that risk is, and whether additional mitigation steps are required before the vendor can be approved.

The goal of a scoring model is to create a process that is:
- Consistent  
- Repeatable  
- Easy to understand  
- Defensible (you can clearly explain why a vendor received a specific rating)  

---

## 📌 How Vendor Risk Is Measured

Vendor risk is typically evaluated using two main factors:

### **1. Likelihood**  
How probable it is that a security issue, failure, or control breakdown could occur at the vendor.

### **2. Impact**  
How severe the harm would be if an incident occurred at the vendor and affected your organization.

These two values are combined to generate a clear, numerical risk score.

---

## 📌 Likelihood Rating (1–5)

Likelihood reflects the chance that something could go wrong. Analysts assess factors such as:

- Strength and maturity of the vendor’s controls  
- Results from SOC 2 or ISO 27001 reports  
- Past security incidents  
- Gaps identified during questionnaires  
- Complexity of the technology and environment  
- Industry threat exposure  

### **Scale**
- **1 – Very Low**  
- **2 – Low**  
- **3 – Moderate**  
- **4 – High**  
- **5 – Very High**  

---

## 📌 Impact Rating (1–5)

Impact measures the severity of the consequences your organization would face if the vendor experienced a security issue.

Analysts consider:

- Sensitivity of the data shared with the vendor  
- Vendor’s access to internal systems  
- Operational dependency (business impact if vendor goes down)  
- Regulatory exposure  
- Financial and reputational risk  

### **Scale**
- **1 – Very Low**  
- **2 – Low**  
- **3 – Moderate**  
- **4 – High**  
- **5 – Very High**  

---

## 📌 Calculating the Risk Score

Most organizations use a simple formula:

Risk Score = Likelihood × Impact


This results in a score ranging from **1 to 25**.

### **Common Risk Levels**
- **1–5 → Low Risk**  
- **6–12 → Moderate Risk**  
- **13–19 → High Risk**  
- **20–25 → Critical Risk**  

High and critical vendors generally require:
- Additional due diligence  
- Stronger controls or compensating controls  
- Management approval  
- More frequent monitoring  

---

## 📌 Example

- **Likelihood: 4 (High)**  
- **Impact: 5 (Very High)**  

4 × 5 = 20 → Critical Risk Vendor


This vendor likely handles sensitive data, performs critical business processes, or has notable security weaknesses.

---

## 📌 Why a Scoring Model Matters

A clear scoring process enables organizations to:

- Make consistent, risk-based decisions  
- Prioritize vendor reviews  
- Identify vendors that require additional controls  
- Communicate risk in a simple, understandable way  
- Meet audit and compliance expectations  

A straightforward and transparent scoring model is easier to adopt and maintain, especially for growing Vendor Risk or GRC programs.

---

**Author:** Logan McDermott
