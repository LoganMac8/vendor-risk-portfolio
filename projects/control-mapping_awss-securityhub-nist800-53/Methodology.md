# Methodology  
**AWS Security Hub → NIST 800-53 Control Mapping**

This methodology explains the approach, standards, and decision logic used to map AWS Security Hub controls to the NIST 800-53 Rev 5 security framework. The intent is to provide a transparent, repeatable process that demonstrates strong analytical rigor—mirroring how real governance, risk, and compliance teams build enterprise-scale mappings.

---

## 1. Purpose of This Methodology
The purpose of this methodology is to clearly define how each AWS Security Hub control was evaluated, interpreted, and mapped to the appropriate NIST 800-53 control families.  
This establishes:

- Consistency  
- Repeatability  
- Auditability  
- Alignment with industry frameworks  
- A traceable linkage between AWS-native security findings and compliance requirements  

---

## 2. Data Sources Reviewed
The following documentation sources were used to develop accurate and defensible mapping relationships:

### **AWS Documentation**
- AWS Security Hub Controls Reference  
- AWS Foundational Security Best Practices Standard  
- AWS CIS Benchmark (as referenced by Security Hub)  
- AWS Well-Architected Security Pillar documentation  
- AWS shared responsibility model  

### **NIST 800-53 Rev 5 Documentation**
- Full control catalog  
- Control enhancements  
- Supporting assessment procedures (NIST 800-53A)  
- NIST mappings for cloud environments (as available)

### **Industry Resources**
- CSA Cloud Controls Matrix  
- FedRAMP moderate/high mappings  
- AWS compliance pages for NIST, FedRAMP, and ISO  
- Public AWS-to-NIST mapping tables (where authoritative)

---

## 3. Mapping Logic & Decision Criteria
Each AWS Security Hub control was analyzed using a structured decision workflow:

### **Step 1 — Understand AWS Intent**
- Determine what the AWS control *actually measures*.
- Identify whether it evaluates configuration, monitoring, encryption, IAM, logging, or architecture.

### **Step 2 — Identify Security Outcomes**
For each control, define the specific security objective:
- Prevent?  
- Detect?  
- Correct?  
- Enforce configuration?  
- Reduce attack surface?  

### **Step 3 — Match to NIST 800-53 Control Families**
Using the control objective, map to one or more relevant NIST control families:
- AC (Access Control)  
- AU (Audit & Accountability)  
- CM (Configuration Management)  
- SC (System & Communications Protection)  
- SI (System & Information Integrity)  
- etc.  

### **Step 4 — Select Exact NIST Controls**
A mapping is only accepted if **ALL** criteria are true:

✔ The NIST control aligns directly with the AWS control’s purpose  
✔ The NIST control governs the same security outcome  
✔ A real organization could cite the AWS control as evidence for the NIST requirement  
✔ No contradictory or partially related NIST control is more appropriate  

### **Step 5 — Document Rationale**
For each mapping, we document:

- Why the mapping fits  
- Any limitations  
- Whether the mapping is partial or full coverage  
- Any expected compensating controls  

This ensures transparency and audit-readiness.

---

## 4. Handling Partial vs. Full Mappings

### **Full Mapping**
AWS Security Hub control fully satisfies the intent of the NIST requirement.

### **Partial Mapping**
AWS Security Hub control provides *some* evidence toward the NIST requirement but does not independently satisfy it.

Reasons for partial coverage might include:
- AWS control is technical, while NIST requires administrative controls  
- NIST requires policies/procedures in addition to configuration  
- AWS control only covers detection, not prevention  

### **No Mapping**
If the AWS control does not meaningfully support the NIST requirement, it is marked **No Mapping**.

This protects the integrity of the mapping process.

---

## 5. Treatment of Shared Responsibility
Cloud compliance requires differentiating:

- **AWS responsibility** (infrastructure, hardware, physical security)  
- **Customer responsibility** (configurations, IAM, data security, monitoring)

Mappings only include controls relevant to **customer responsibility**, ensuring the work reflects what a GRC analyst would actually own.

---

## 6. Quality Assurance & Validation
To ensure accuracy, each mapping underwent:

- Cross-checking with authoritative AWS/NIST mappings  
- Validation against multiple AWS controls to ensure no over-mapping  
- Logical consistency review across families  
- Duplicate mapping elimination  
- Review for gaps or missing control families  

---

## 7. How This Methodology Demonstrates Professional Skill
This document showcases:

- Deep understanding of cloud security  
- Strong analytical thinking  
- Ability to interpret complex frameworks  
- Real-world GRC and compliance methodology  
- Professional documentation standards  
- Enterprise-quality mapping practices  

Recruiters and hiring managers expect analysts to articulate **how** they think—not just what they produce.  
This methodology gives you exactly that advantage.

---

## 8. Next Steps
This methodology is applied in:

- `Mappings/NIST-to-SOC2.md`  
- `Mappings/SOC2-to-ISO.md`  
- `Mappings/NIST-to-ISO.md`  
- `Control-Mapping.md`  
- `Gaps-and-Recommendations.md`  
- `Summary.md`

