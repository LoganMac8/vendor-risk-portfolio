# NIST 800-53 → SOC 2 Trust Services Criteria Mapping  
This document provides a structured crosswalk between NIST 800-53 (Rev. 5) controls and SOC 2 Trust Services Criteria (TSC).  
Mappings include direct, partial, conceptual, and gap-based relationships to reflect real-world alignment.

---

## 📌 How to Read This Mapping
Each row includes:

- **NIST Control ID** - Source control  
- **Description** - Summary of NIST control intent  
- **SOC 2 Criteria Match** - Corresponding SOC 2 TSC ID(s)  
- **Match Type**  
  - **Direct** - Strong alignment  
  - **Partial** - Needs additional controls to fully match  
  - **Conceptual** - Aligns philosophically, not technically  
  - **Gap** – No meaningful match  
- **Rationale** - Explanation of why this mapping applies  

This file includes a representative sample of mappings appropriate for portfolio demonstration.

---

# 🔐 Access Control (AC Family)

### **AC-1 - Access Control Policy and Procedures**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC1.2, CC6.1 |
| **Match Type** | Partial |
| **Rationale** | SOC 2 requires documented controls but is less prescriptive than NIST regarding access governance procedures. |

---

### **AC-2 - Account Management**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC6.2, CC6.3, CC6.6 |
| **Match Type** | Direct |
| **Rationale** | SOC 2 explicitly requires provisioning, modification, and deprovisioning of accounts similar to NIST requirements. |

---

### **AC-3 - Access Enforcement**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC6.1, CC6.6 |
| **Match Type** | Partial |
| **Rationale** | SOC 2 requires enforcement of access restrictions, but NIST provides more granular guidance. |

---

### **AC-5 - Separation of Duties**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC1.2, CC7.2 |
| **Match Type** | Direct |
| **Rationale** | SOC 2 requires SoD in risk management and operations, aligning closely with NIST AC-5. |

---

# 📝 Audit & Accountability (AU Family)

### **AU-2 - Audit Events**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC7.2, CC7.3 |
| **Match Type** | Partial |
| **Rationale** | SOC 2 requires logging of security-relevant events, though NIST defines more specific event categories. |

---

### **AU-6 - Audit Review, Analysis, and Reporting**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC7.2, CC7.3 |
| **Match Type** | Direct |
| **Rationale** | Both frameworks require regular analysis and review of audit logs for anomalies. |

---

# 🔄 Configuration Management (CM Family)

### **CM-2 - Baseline Configuration**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC8.1 |
| **Match Type** | Direct |
| **Rationale** | SOC 2 includes requirements around baseline configuration and hardening. |

---

### **CM-6 - Configuration Settings**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC8.1 |
| **Match Type** | Partial |
| **Rationale** | SOC 2 requires secure configuration but NIST provides deeper technical control. |

---

# 🛡️ System & Communications Protection (SC Family)

### **SC-7 - Boundary Protection**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC6.6, CC6.7 |
| **Match Type** | Partial |
| **Rationale** | SOC 2 requires perimeter protections but NIST is more explicit about segmentation. |

---

### **SC-12 - Cryptographic Key Establishment**  
| Field | Value |
|------|-------|
| **SOC 2 Match** | CC6.7 |
| **Match Type** | Conceptual |
| **Rationale** | SOC 2 references encryption requirements but does not define key establishment processes in detail. |

---

# 📉 Unmapped Controls (Gaps)
Some NIST controls have no meaningful SOC 2 equivalent, including:

- **PM-1 to PM-30 (Program Management Family)**  
- **PE Controls** involving physical access hardware  
- **MA Controls** relating to maintenance personnel authorization  
- **IR-4 enhancements** requiring specific federal incident response capabilities  

These are documented in more detail in `Gaps-and-Recommendations.md`.

---

# 📘 Next Document  
Proceed to:  
`projects/framework-mapping/SOC2-to-ISO.md`

