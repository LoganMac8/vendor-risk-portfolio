# 🔐 AWS Security Hub → NIST 800-53 Rev5 Control Mapping  
### Definitive Crosswalk for Cloud Security & Compliance Alignment

This document maps AWS Security Hub controls to the corresponding NIST 800-53 Rev5 controls.  
Each row includes:  
- AWS Security Hub Control  
- Primary NIST Control  
- Supporting NIST Controls  
- Mapping Rationale  

This is written to demonstrate clear traceability, compliance maturity, and the ability to manage framework alignment in a real GRC role.

---

## 📘 Legend  
**Primary Match** — Closest NIST control objective  
**Supporting Match** — Additional related control(s)  
**Rationale** — Explanation written in auditor-friendly language  

---

# 🧩 Control Mapping Table

| AWS Security Hub Control | Primary NIST 800-53 Rev5 Control | Supporting Controls | Rationale |
|-------------------------|----------------------------------|----------------------|-----------|
| **IAM.1 – MFA for root user** | AC-2 (Account Management) | IA-2, IA-5 | Requires strong authentication for the highest-privilege account. |
| **IAM.2 – No root access keys** | AC-2 | IA-2, SC-12 | Root keys pose risk; NIST requires secure account provisioning & key protection. |
| **IAM.3 – MFA for console users** | IA-2 (Identity Verification) | AC-2 | MFA satisfies multi-factor verification requirements. |
| **IAM.4 – Unused credentials disabled** | AC-2 | IA-4 | Aligns with periodic account review and access removal. |
| **IAM.6 – Least privilege IAM policies** | AC-6 (Least Privilege) | AC-3, AC-2 | NIST mandates least privilege and controlled access enforcement. |
| **IAM.7 – IAM roles used instead of long-term keys** | AC-3 (Access Enforcement) | IA-5 | Temporary credentials reduce credential exposure. |
| **IAM.8 – No inline IAM policies** | AC-3 | PL-2 | Managed policy structure improves consistency & access governance. |
| **Config.1 – CloudTrail enabled** | AU-2 (Event Logging) | AU-6, AU-12 | AWS CloudTrail aligns with event logging & centralized audit trails. |
| **Config.2 – CloudTrail encryption enabled** | SC-13 (Cryptographic Protection) | AU-9 | Logs must be encrypted at rest to protect audit integrity. |
| **Config.3 – CloudTrail log validation enabled** | AU-10 (Nonrepudiation) | AU-9 | Ensures logs are tamper-evident and trustworthy. |
| **Config.4 – S3 access logging enabled** | AU-2 | AU-12 | Logging S3 access aligns with monitoring access to sensitive objects. |
| **S3.1 – S3 encryption enabled** | SC-28 (At-Rest Data Protection) | SC-13 | NIST requires encryption of stored data. |
| **S3.2 – Public access blocked** | AC-3 | SC-7 | Addresses unauthorized public exposure of data. |
| **S3.4 – Versioning enabled** | CP-9 (Backup & Recovery) | CP-10 | Versioning acts as a lightweight recovery and rollback mechanism. |
| **EC2.1 – EBS encryption enabled** | SC-28 | SC-13 | Ensures confidentiality of stored compute volumes. |
| **EC2.5 – IMDSv2 required** | SC-7 (Boundary Protection) | SC-23 | Protects metadata access from SSRF-style attacks. |
| **EC2.6 – No public AMIs** | AC-3 | CM-8 | Prevents unapproved sharing of machine images. |
| **Lambda.1 – Function-level permissions review** | AC-6 | AC-2 | Least privilege for serverless functions. |
| **Lambda.2 – Environment variables encrypted** | SC-28 | SC-13 | Sensitive configuration must be encrypted at rest. |
| **Lambda.3 – No public Lambda URLs** | AC-3 | SC-7 | Prevents unauthorized public invocation. |
| **RDS.1 – Encryption enabled** | SC-28 | SC-13 | Database encryption protects stored PII and regulated data. |
| **RDS.2 – Backups enabled** | CP-9 | CP-10 | Supports recovery and resilience requirements. |
| **RDS.3 – Public accessibility disabled** | AC-3 | SC-7 | Prevents unauthorized access from the open internet. |
| **VPC.1 – Flow logs enabled** | AU-12 | AC-4 | Required for analyzing network traffic and enforcing segmentation. |
| **VPC.2 – No unrestricted security groups** | SC-7 | AC-4 | NIST requires boundary protections and restricted ingress. |
| **VPC.4 – Subnet segmentation** | SC-7 | AC-4, CM-2 | Network zoning aligns with least privilege and segmentation requirements. |
| **Logging.1 – CloudWatch log retention defined** | AU-11 | AU-12 | Log retention requirements align with auditability and compliance. |
| **Monitoring.1 – GuardDuty enabled** | RA-5 (Vulnerability Monitoring) | SI-4 | Supports continuous threat detection and vulnerability analysis. |
| **Monitoring.2 – Security Hub enabled** | RA-5 | CA-7 | Provides continuous monitoring and control evaluation. |

---

# 📝 Notes  
- All mappings are based on publicly available AWS and NIST documentation.  
- No confidential control objectives are included.  
- Mapping rationale is written in business-friendly, audit-ready language.

---

# ✅ Summary  
This mapping demonstrates the ability to:  
- Interpret complex frameworks  
- Align cloud-native controls to federal baselines  
- Produce polished, defensible compliance documentation  
- Work across security, engineering, and governance domains  
- Deliver work that mirrors real-world GRC program output  

