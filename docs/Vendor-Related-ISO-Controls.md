# ISO 27001 Controls Relevant to Vendor Risk  
_A practical overview written for Vendor Risk & GRC analysts_

ISO 27001 includes a broad set of security controls, but only a specific subset directly impacts third-party risk decisions. This document summarizes the ISO 27001 controls that matter most when evaluating vendors and explains how they apply in real vendor due diligence workflows.

My goal with this guide is to highlight the controls that come up repeatedly during vendor assessments and map them to what I actually look for when reviewing questionnaires, SOC 2 reports, or contracts.

---

## 📌 Why ISO 27001 Matters in Vendor Assessments
Many vendors use ISO 27001 as their primary security framework. Even if they don’t have a certification, they often structure their controls “based on ISO.”

Understanding the ISO controls helps you:
- Interpret vendor evidence more confidently  
- Identify gaps in questionnaires or SOC 2 reports  
- Know what good security practices should look like  
- Ask better follow-up questions when something seems unclear  

You don’t need to memorize all ISO controls — just the ones below.

---

## 1. A.5 — Information Security Policies  
**What this control covers:**  
Vendors should have formal, approved, and regularly updated security policies.

**What I look for:**  
- Is there a policy?  
- Has it been reviewed within the last 12–18 months?  
- Does it cover acceptable use, access control, and data handling?  

Strong policies show that security practices are intentional, not ad-hoc.

---

## 2. A.6 — Organization of Information Security  
**Why this is important for vendor risk:**  
This control describes how a vendor organizes its security responsibilities.

**What I check:**  
- Do they have a dedicated security team or shared responsibility model?  
- Who approves access to systems?  
- Are roles clearly defined (IT, security, engineering, etc.)?  
- Do employees receive security training?  

Clear responsibilities make security more reliable and easier to audit.

---

## 3. A.7 — Human Resource Security  
**Focus:** How a vendor screens, trains, and manages its employees.

**What matters for vendor risk:**  
- Background checks (where legally allowed)  
- Security awareness training  
- Confidentiality agreements  
- Termination procedures (revoking access promptly)

This area directly affects insider threat risk.

---

## 4. A.8 — Asset Management  
**Purpose:** Ensures the vendor knows what data, devices, and systems they manage.

**What I look for:**  
- Do they classify data (public, internal, restricted)?  
- Are assets inventoried?  
- Is sensitive data labeled and controlled appropriately?  

Vendors who can’t explain their data classification usually struggle in other areas too.

---

## 5. A.9 — Access Control  
This is one of the most important categories for vendor risk.

**Key questions:**  
- Do they follow least privilege?  
- Is multi-factor authentication enforced?  
- Are access reviews performed regularly?  
- Is access removed promptly when employees leave?  

Weak access control is one of the top causes of security incidents, so this section always gets extra attention.

---

## 6. A.10 — Cryptography  
**What it covers:** Encryption standards, key management, and secure protocols.

**What I expect from vendors:**  
- Encryption in transit (TLS 1.2 or higher)  
- Encryption at rest  
- Documented key management procedures  
- No outdated encryption algorithms  

If a vendor handles sensitive or regulated data, this becomes non-negotiable.

---

## 7. A.12 — Operations Security  
**Focus:** Logging, monitoring, change management, and operational processes.

**What I review:**  
- Logging and monitoring coverage  
- How they detect suspicious activity  
- Whether changes go through formal review and approval  
- Patch management timelines  

A mature operations program reduces the likelihood of unnoticed issues.

---

## 8. A.13 — Communications Security  
This covers network-level protections and secure data transfer.

**Vendor-specific considerations:**  
- Network segmentation  
- Firewalls and intrusion detection  
- Secure API communication  
- Protection of data sent over public networks  

Good controls here reduce exposure to external attacks.

---

## 9. A.14 — System Acquisition, Development & Maintenance  
**Why it matters:**  
If the vendor builds or maintains their own software, this section becomes critical.

**What I look for:**  
- Secure development lifecycle (SDLC)  
- Code reviews  
- Vulnerability scanning (SAST/DAST)  
- Third-party library management  

This control area shows whether a vendor treats security as part of development or an afterthought.

---

## 10. A.15 — Supplier Relationships (Most Relevant)  
This category is directly tied to vendor risk.

**Key areas:**  
- Third-party due diligence processes  
- Contractual security requirements  
- Monitoring of sub-vendors  
- Service level agreements (SLAs)  
- Chain-of-trust controls  

If I see weak controls here, it’s usually a sign that the vendor may not fully understand or manage their own supply-chain risk.

---

## 11. A.16 — Incident Management  
**What I evaluate:**  
- Do they have an incident response plan?  
- Who gets notified internally and externally?  
- Do they test the plan?  
- Are incidents logged and reviewed?  

Good incident response reduces the impact of potential breaches.

---

## Summary  
You don’t need to know every ISO control by heart to perform solid vendor assessments. You just need to understand the ones that show up repeatedly in SOC 2 reports, security questionnaires, and vendor discussions.  
These ISO domains give a clear view of how mature a vendor’s security program is and where additional follow-up may be necessary.

When a vendor demonstrates strong controls in these areas, it’s a good sign that they take security seriously and can be trusted with sensitive data.

