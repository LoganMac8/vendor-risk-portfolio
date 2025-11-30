# Day Two — Learning Journal

**Focus Area:** Reading SOC 2 Reports Like an Auditor  
**Daily Goal:** Learn how to break down a SOC 2 report, identify key sections, interpret audit findings, and understand subservice organizations.  
**Time Spent:** ~6 hours  

---

## 📘 What I Studied Today
### **1. Structure of a SOC 2 Report**
I learned how SOC 2 reports are organized and what each section is used for:
- Management Assertion  
- Independent Auditor’s Report  
- System Description  
- Trust Services Criteria & Controls  
- Testing Procedures and Results  
- Exceptions & Findings  
- Complementary User Entity Controls (CUECs)  
- Subservice Organizations  

### **2. How to Read a SOC 2 Like an Auditor**
Key lessons:
- Focus on *scope* first — what systems and services were actually included  
- Identify the control boundaries  
- Understand the audit period  
- Check for carve-outs and subservice providers  
- Pay attention to any qualified or adverse opinions  
- Look for repeated exceptions year-over-year  

### **3. Exceptions & Control Failures**
I studied examples of control exceptions and how they’re described:
- Missing evidence  
- Incomplete logs  
- Delayed patching  
- Inconsistent access reviews  
- Policies not followed consistently  

Learned how to classify exceptions by:
- Severity  
- Frequency  
- Potential impact  
- Control category affected  

### **4. Evaluating Subservice Organizations**
Subservice organizations (like AWS, Okta, or Stripe) play a major role in vendor ecosystems.  
Today I learned:
- The difference between **carve-out** and **inclusive** reporting  
- Why dependency risk matters  
- How to identify CUECs that my organization must fulfill  

---

## 🧠 Key Takeaways
- SOC 2 reports tell a story — not just about controls, but about the maturity of the vendor’s entire security program.  
- Exceptions don’t automatically disqualify a vendor; they show where risk lives.  
- Understanding **scope** and **subservice providers** is critical for evaluating risk correctly.  
- CUECs highlight responsibilities that *my organization* must follow for the vendor’s controls to be effective.  

---

## 🔍 What I Found Interesting
- Many vendors rely heavily on AWS or similar platforms, and those relationships shape large portions of their security posture.  
- Some SOC 2 exceptions are low-severity but show patterns, which auditors use to gauge process maturity.  
- The “Testing Procedures” section is full of clues about how deeply the auditors reviewed each control.  

---

## 📝 Skills Practiced Today
- Reading actual SOC 2 report excerpts  
- Identifying scope and boundaries  
- Spotting exceptions and interpreting their severity  
- Understanding how auditors test operating effectiveness  

---

## 🚀 What I Completed Today
- Downloaded and reviewed a sample SOC 2 report  
- Created the `SOC2_Report_Analysis.md` file  
- Documented the key report sections  
- Started analyzing sample exceptions  
- Added notes to GitHub for transparency and consistency  

---

## 🎯 Tomorrow’s Goals
- Create a full SOC 2 analysis document  
- Write findings in professional auditor-style language  
- Begin drafting recommendations for remediating exceptions  
- Continue preparing for Portfolio Project #1 (Vendor Risk Assessment)

---

**Author:** Logan McDermott
