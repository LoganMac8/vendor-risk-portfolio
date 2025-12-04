# SOC 2 Trust Services Criteria → ISO 27001:2022 Control Mapping  
This document provides a structured mapping between SOC 2 Trust Services Criteria (TSC) and ISO 27001:2022 Annex A controls.  
Mapping types include direct, partial, conceptual, and no-alignment (gap).

---

## 📌 How to Read This Mapping
Each entry includes:

- **SOC 2 TSC** – The Trust Services Criteria requirement  
- **ISO 27001 Control** – Corresponding Annex A control(s)  
- **Match Type**  
  - **Direct** – Strong alignment  
  - **Partial** – Covers some but not all requirements  
  - **Conceptual** – Related in principle, not in scope  
- **Notes** – Context for auditors or assessors  

This crosswalk is optimized for recruiters and hiring managers to quickly confirm your familiarity with frameworks.

---

# 🔐 Security (Common Criteria CC Series)

### **CC1.1 — Control Environment**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.1 (Policies), A.5.2 (Roles & Responsibilities) |
| **Match Type** | Direct |
| **Notes** | Both require a governance foundation and structured responsibilities. |

---

### **CC1.2 — Commitment to Integrity and Ethical Values**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.1, A.5.4 |
| **Match Type** | Conceptual |
| **Notes** | ISO addresses high-level ethics indirectly through policy expectations. |

---

### **CC2.1 — Board Oversight**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.3 (Segregation of duties), A.7.7 (Monitoring) |
| **Match Type** | Partial |
| **Notes** | ISO does not explicitly require board governance but overlaps in oversight expectations. |

---

### **CC3.1 — Risk Assessment Process**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.7 (Risk Management), A.8.16 (Monitoring Activities) |
| **Match Type** | Direct |
| **Notes** | Both frameworks require structured risk assessments and periodic reviews. |

---

### **CC3.2 — Fraud Risk Assessment**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.6.9 (Information Security in Supplier Relationships) |
| **Match Type** | Conceptual |
| **Notes** | SOC 2 calls out fraud explicitly; ISO references it indirectly through trust and supplier integrity. |

---

### **CC4.1 — Monitoring of Internal Controls**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.16 (Monitoring), A.7.8 (Independent Review) |
| **Match Type** | Direct |
| **Notes** | Strong alignment between SOC 2 monitoring requirements and ISO’s periodic control review. |

---

# 🔐 Logical & Physical Access

### **CC6.1 — Logical Access Security**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.2 (Privileged Access), A.8.3 (User Access Management) |
| **Match Type** | Direct |
| **Notes** | Both require access restriction, centralized management, and secure authentication. |

---

### **CC6.2 — User Access Provisioning**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.3, A.8.4 |
| **Match Type** | Direct |
| **Notes** | Strong alignment in provisioning, modification, and deprovisioning controls. |

---

### **CC6.6 — Network Security & Perimeter Controls**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.20 (Network Security), A.8.23 (Segmentation) |
| **Match Type** | Direct |
| **Notes** | ISO includes explicit segmentation guidance that mirrors SOC 2 network control expectations. |

---

# 🔄 Change Management (CC8 Series)

### **CC8.1 — Change Management**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.32 (Change Management), A.5.1 |
| **Match Type** | Direct |
| **Notes** | ISO and SOC 2 both require structured change processes and approval workflows. |

---

# 🛡️ Security Operations (CC7 Series)

### **CC7.2 — Log Monitoring**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.8.15 (Logging), A.8.16 (Monitoring Activities) |
| **Match Type** | Direct |
| **Notes** | Nearly identical requirements around logging, retention, and analysis. |

---

### **CC7.3 — Incident Detection & Response**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.25 (Incident Reporting), A.5.26 (Incident Response) |
| **Match Type** | Direct |
| **Notes** | Clear alignment between SOC 2 IR expectations and ISO’s structured IR program. |

---

# 🧾 Vendor & Third Party Management

### **CC9.2 — Vendor Risk Management**
| Field | Value |
|------|-------|
| **ISO Control Match** | A.5.19 (Supplier Security), A.5.20 (Supplier Agreements) |
| **Match Type** | Direct |
| **Notes** | Both frameworks require oversight, review, and contractual controls for suppliers. |

---

# 📘 Next Document  
Proceed to:  
`projects/framework-mapping/NIST-to-ISO.md`

