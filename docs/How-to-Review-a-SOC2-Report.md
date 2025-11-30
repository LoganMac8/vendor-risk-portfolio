# How to Review a SOC 2 Report  
_A practical guide for Vendor Risk and GRC Analysts_

A SOC 2 report is one of the most important documents used in Vendor Risk Management. It shows how well a service provider protects customer data and whether their controls actually work in real life—not just on paper.  
This guide explains the exact steps I follow when reviewing a SOC 2 report as part of a real vendor due diligence workflow.

---

## 1. Start by Identifying the Report Type  
Before anything else, confirm whether the report is **Type I** or **Type II**.

- **Type I** → A snapshot in time (design only)  
- **Type II** → Controls tested over several months (design + operating effectiveness)

Type II gives a much clearer picture of how mature and consistent a vendor’s security program really is, so it’s the preferred version for vendor risk assessments.

---

## 2. Confirm the Scope of the Audit  
The scope tells you exactly what the auditors examined. This is critical because a vendor may only audit certain services, not their entire platform.

Key things to look for:
- System description  
- Services included (and excluded)  
- Defined system boundaries  
- Infrastructure and software components  
- Processes, teams, and functions in scope  

If the scope doesn’t align with the product your organization will use, that’s a red flag.

---

## 3. Identify Which Trust Service Criteria (TSC) Are Covered  
Every SOC 2 includes **Security**, but the other categories are optional:

- Security (always included)  
- Availability  
- Confidentiality  
- Processing Integrity  
- Privacy  

A broader set of TSC categories generally gives better insight into the vendor’s overall security posture.

---

## 4. Review the Vendor’s Control Activities  
This is where you start understanding *how* the vendor protects data. I evaluate each control area for maturity and alignment with best practices.

Common areas I focus on:
- Access control & least privilege  
- Logging, monitoring, and alerting  
- Change management  
- Encryption and key management  
- Vulnerability management & patching  
- Incident response preparedness  
- Backup and recovery processes  

At this stage, I’m asking:  
**“Do these controls make sense for the type of data the vendor handles?”**

---

## 5. Look at the Auditor’s Testing Procedures and Results  
In Type II reports, auditors test controls over several months. I pay close attention to:

- How the auditors tested each control  
- Whether any deviations were found  
- Comments explaining how issues occurred  
- Whether exceptions were isolated or repeated  
- Any patterns that might suggest a process weakness  

One-off issues aren’t unusual, but repeated exceptions often signal operational inconsistency.

---

## 6. Identify Exceptions and Assess Their Risk  
Most SOC 2 reports include a few exceptions. Not all of them are severe, but they still need to be understood.

Common types of exceptions include:
- Access reviews completed late  
- Patches not applied within expected timeframes  
- Missing or incomplete logs  
- Outdated documentation  
- Gaps in change management processes  

When I see an exception, I evaluate:
- What caused it  
- Whether it impacted security  
- If it’s a recurring issue  
- Whether the vendor already remediated it  

If a remediation plan isn’t mentioned, that usually becomes a requirement before approval.

---

## 7. Review Complementary User Entity Controls (CUECs)  
These are controls **your organization** must perform for the vendor’s controls to be effective.

Examples:
- Enforcing strong authentication for accounts accessing the vendor  
- Limiting permissions to only what your users need  
- Securing your network configurations  
- Reviewing vendor access regularly  

Ignoring CUECs can create risk even if the vendor’s own controls are strong.

---

## 8. Form Your Final Risk Conclusion  
After reviewing everything, I summarize the vendor’s risk posture in clear, plain language.

My conclusion typically includes:
- Whether the SOC 2 report is acceptable  
- Key risks identified  
- Likelihood and impact  
- Required remediation items  
- Overall vendor risk rating  
- Whether the vendor is recommended for approval  

This summary is what leadership and procurement rely on when deciding whether to move forward with the vendor.

---

## Summary  
Reviewing a SOC 2 report isn’t just about reading an audit—it’s about understanding how a vendor operates, where their risks are, and whether they meet your organization’s security requirements.  
A structured review process helps ensure vendors are evaluated consistently and that any gaps are addressed before onboarding.

