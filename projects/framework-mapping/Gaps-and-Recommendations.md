# Gaps & Recommendations  
This document summarizes areas where NIST 800-53, ISO 27001:2022, and SOC 2 criteria diverge — plus recommended remediation steps that real organizations use to unify multi-framework compliance.

The goal is to demonstrate my ability to identify cross-framework control weaknesses and provide practical, audit-focused improvements.

---

# 🔍 Gap Summary

Below are the most common gaps observed when aligning NIST, ISO, and SOC 2:

---

## 1. **Role-Based Access Reviews (RBAC)**
**Gap:**  
ISO 27001 and SOC 2 require periodic access reviews, but NIST defines *more explicit expectations* around frequency, scope, and documentation.

**Impact:**  
Organizations often pass SOC 2 but fall short of NIST rigor.

**Recommendation:**  
- Establish a quarterly access review schedule.  
- Include privileged accounts, service accounts, and API keys.  
- Store review evidence in a centralized repository (e.g., GRC tool, SharePoint, Jira).  

---

## 2. **Change Management Rollback Procedures**
**Gap:**  
ISO 27001 Annex A requires change control but is not explicit about validated rollback plans.  
NIST CM-3/CM-4 requires *documented AND tested* rollback procedures.

**Impact:**  
Operational risk increases if deployments cannot be safely reversed.

**Recommendation:**  
- Document rollback steps for all high-risk changes.  
- Test rollback procedures at least annually.  
- Capture evidence for audit readiness.  

---

## 3. **Incident Response Testing Frequency**
**Gap:**  
SOC 2 requires “periodic testing.”  
ISO suggests a general testing cadence.  
NIST explicitly requires **annual exercises and role-based training**.

**Impact:**  
Companies often meet SOC 2 but fail to satisfy NIST IR-3/IR-4 expectations.

**Recommendation:**  
- Conduct full IR tabletop exercises yearly.  
- Include external parties (e.g., Legal, PR) for realism.  
- Produce a post-incident report with improvement actions.  

---

## 4. **Supplier Lifecycle Management**
**Gap:**  
ISO 27001 has strong supplier lifecycle expectations (A.5.19–5.20).  
NIST has fewer prescriptive requirements outside SR controls.  
SOC 2 focuses more on third-party assurances, not lifecycle.

**Impact:**  
Vendor risk processes may be insufficient for ISO certification.

**Recommendation:**  
- Maintain a vendor tiering model.  
- Require SOC 2/ISO/SLA documents at onboarding.  
- Reassess high-risk vendors annually.  

---

## 5. **Cryptographic Governance**
**Gap:**  
All frameworks require encryption, but NIST includes detailed key management and FIPS expectations not fully matched by ISO or SOC 2.

**Impact:**  
Encryption may be in place but not in compliance.

**Recommendation:**  
- Adopt FIPS-validated modules where possible.  
- Document key rotation cycles (annual minimum).  
- Store keys in managed HSM/KMS solutions.  

---

## 6. **Baseline Configuration Documentation**
**Gap:**  
All frameworks require configuration standards, but NIST CM-2 demands more granular baselines and version-controlled documentation.

**Impact:**  
Teams may have SOPs but lack evidence of “formal baselines.”

**Recommendation:**  
- Create baseline configuration templates per system type.  
- Track baselines in Git or a configuration management tool.  
- Review baselines yearly.  

---

## 7. **Data Lifecycle Documentation**
**Gap:**  
ISO has extensive lifecycle requirements (creation → disposal).  
SOC 2 mentions data lifecycle indirectly.  
NIST requires explicit documentation of retention, sharing, disposal.

**Impact:**  
Organizations may unintentionally fail NIST-style audits.

**Recommendation:**  
- Create a formal data lifecycle policy.  
- Align retention schedules with legal/regulatory needs.  
- Document encryption and destruction workflows.  

---

# 📘 Summary  
Most gaps appear because:

- **SOC 2 is principles-based (less prescriptive).**  
- **ISO 27001 is structured but flexible.**  
- **NIST 800-53 is detailed and strict.**

A strong security program can meet all three by adopting NIST-level rigor and documenting controls thoroughly.

This multi-framework mapping exercise demonstrates competency in:  
- Crosswalk analysis  
- Control interpretation  
- Audit readiness  
- Governance and risk strategy  

---

# ▶️ Next Document  
Proceed to the final file:  
`projects/framework-mapping/Summary.md`
