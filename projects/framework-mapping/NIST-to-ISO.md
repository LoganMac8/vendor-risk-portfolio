# NIST 800-53 Rev 5 → ISO 27001:2022 Control Mapping  
This document compares key NIST 800-53 security and privacy controls with ISO 27001:2022 Annex A controls.  
The goal is to show framework literacy, mapping logic, and the ability to translate between regulatory requirements.

---

## 📌 How to Read This Mapping  
Each entry includes:

- **NIST Control Family & ID** - e.g., AC-2 (Access Control)  
- **ISO 27001 Annex A Match** - corresponding ISO control(s)  
- **Match Type** - Direct / Partial / Conceptual  
- **Notes** - what an auditor or assessor should understand about the alignment  

This is a *representative, high-value*, recruiter-friendly mapping — not an exhaustive catalog.

---

# 🔐 Access Control (AC Family)

### **AC-2 - Account Management**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.2 (Privileged Access), A.8.3 (User Access Management) |
| **Match Type** | Direct |
| **Notes** | Both frameworks require provisioning, modification, and revocation processes. |

---

### **AC-6 - Least Privilege**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.2 |
| **Match Type** | Direct |
| **Notes** | Least-privilege expectations fully align across both frameworks. |

---

### **AC-17 - Remote Access**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.20 (Network Security), A.8.26 (Secure Authentication) |
| **Match Type** | Partial |
| **Notes** | ISO does not explicitly call out RDP/VPN controls but addresses them indirectly. |

---

# 🏗️ System & Communications Protection (SC Family)

### **SC-7 - Boundary Protection**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.20 (Network Security), A.8.23 (Segregation) |
| **Match Type** | Direct |
| **Notes** | ISO and NIST both require segmentation and secure network architecture. |

---

### **SC-13 - Cryptographic Protection**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.24 (Use of Cryptography) |
| **Match Type** | Direct |
| **Notes** | Strong alignment in encryption standards and key management practices. |

---

### **SC-28 - Protection of Information at Rest**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.24 |
| **Match Type** | Direct |
| **Notes** | ISO covers encryption at rest and cryptographic governance. |

---

# 🛡️ Audit & Accountability (AU Family)

### **AU-2 - Audit Events**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.15 (Logging), A.8.16 (Monitoring) |
| **Match Type** | Direct |
| **Notes** | NIST requires defining auditable events; ISO requires structured logging and review. |

---

### **AU-6 - Audit Review, Analysis, & Reporting**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.16 |
| **Match Type** | Direct |
| **Notes** | Both require routine analysis and escalation of abnormal events. |

---

# 🚨 Incident Response (IR Family)

### **IR-4 - Incident Handling**
| Field | Value |
|------|-------|
| **ISO Match** | A.5.25 (Reporting), A.5.26 (Response) |
| **Match Type** | Direct |
| **Notes** | Strong alignment in documenting, reporting, and managing incidents. |

---

### **IR-6 - Incident Reporting**
| Field | Value |
|------|-------|
| **ISO Match** | A.5.25 |
| **Match Type** | Direct |
| **Notes** | Both require timely reporting and escalation to stakeholders. |

---

# 🧪 Security Assessment & Authorization (CA Family)

### **CA-2 - Security Assessments**
| Field | Value |
|------|-------|
| **ISO Match** | A.5.32 (Independent Review), A.8.28 (Secure Coding) |
| **Match Type** | Partial |
| **Notes** | ISO doesn’t mandate formal “authorization to operate” but covers periodic review and testing. |

---

# 🔧 Configuration Management (CM Family)

### **CM-2 - Baseline Configuration**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.9 (Configuration Management) |
| **Match Type** | Direct |
| **Notes** | Both frameworks require documented and approved configuration standards. |

---

### **CM-6 - Configuration Management**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.10 (Change Management) |
| **Match Type** | Direct |
| **Notes** | ISO aligns closely with NIST expectations for change control workflows. |

---

# 🎛️ Risk Assessment (RA Family)

### **RA-3 - Risk Assessment**
| Field | Value |
|------|-------|
| **ISO Match** | A.5.7 (Risk Management) |
| **Match Type** | Direct |
| **Notes** | Both require identification, analysis, and prioritization of risk. |

---

### **RA-5 - Vulnerability Scanning**
| Field | Value |
|------|-------|
| **ISO Match** | A.8.8 (Vulnerability Management) |
| **Match Type** | Direct |
| **Notes** | ISO requires scanning, remediation, and verification — similar to NIST. |

---

# 📦 Supply Chain Risks (SR Family)

### **SR-3 - Supply Chain Controls**
| Field | Value |
|------|-------|
| **ISO Match** | A.5.19 (Supplier Security), A.5.20 (Supplier Agreements) |
| **Match Type** | Direct |
| **Notes** | Strong alignment in supplier oversight, assessment, and contractual obligations. |

---

# 📘 Next Document  
Proceed to:  
`projects/framework-mapping/Gaps-and-Recommendations.md`
