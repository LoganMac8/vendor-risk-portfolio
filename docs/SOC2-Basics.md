# SOC 2 Basics: A Practical Guide for Vendor Risk Analysts

SOC 2 (System and Organization Controls 2) is one of the most widely used security frameworks for evaluating whether a vendor can securely handle customer data. Vendor Risk Analysts rely heavily on SOC 2 reports to understand a vendor's control environment, uncover weaknesses, and determine risk levels during due diligence.

This document summarizes the core concepts every Vendor Risk Analyst should understand.

## What Is SOC 2

SOC 2 is an attestation framework developed by the AICPA that evaluates how well an organization safeguards data based on the Trust Services Criteria (TSC). It focuses on controls, not financial accuracy, and is commonly required when onboarding SaaS, cloud, or third party service providers.

## Type I vs Type II

This is a common interview topic.

### SOC 2 Type I  
Evaluates whether controls are designed effectively at a single point in time.  
- Snapshot style audit  
- Tests control design only  
- Often used by early stage companies  

### SOC 2 Type II  
Evaluates whether controls are both designed and operating effectively over a period of time, typically 3 to 12 months.  
- Uses real world evidence over an extended period  
- Demonstrates that controls work in practice, not just on paper  
- Most valuable format for Vendor Risk assessments  
- Preferred by most mid sized and large enterprises  

A concise way to describe the difference: Type II carries more weight because it shows that controls are consistently operating, not just documented.

## Why SOC 2 Matters in Vendor Risk Management

Vendor Risk Analysts use SOC 2 reports to:

- Validate a vendor's overall security posture  
- Confirm core controls such as access control, MFA, logging, and encryption  
- Identify audit exceptions and evaluate their impact  
- Help determine the vendor's risk tier (low, medium, high)  
- Support go or no go decisions in onboarding  
- Confirm that third parties meet internal and regulatory expectations  

## Trust Services Criteria (TSC) Overview

The SOC 2 framework is based on five categories. Security is mandatory. The other four are included when relevant to the vendor's services.

1. Security (Common Criteria)  
   Protects systems and data from unauthorized access.  
   Examples: MFA, logging and monitoring, access control, firewalls.

2. Availability  
   Focuses on system reliability and uptime commitments.  
   Examples: uptime monitoring, redundancy, incident response.

3. Processing Integrity  
   Ensures data is processed accurately, completely, and on time.  
   Examples: input validation, error detection, reconciliation.

4. Confidentiality  
   Protects sensitive information from inappropriate disclosure.  
   Examples: encryption in transit and at rest, data classification, role based access.

5. Privacy  
   Focuses on personal data and how it is collected, used, stored, and deleted.  
   Examples: data retention, consent mechanisms, privacy notices.

## Core Components of a SOC 2 Report

Sections that Vendor Risk Analysts typically care about most:

1. Management Assertion  
   The vendor's statement describing the system and its controls.

2. Auditor's Opinion  
   The auditor's conclusion, which may be:  
   - Unqualified (clean)  
   - Qualified (issues noted)  
   - Adverse (major failures)  
   - Disclaimer (insufficient evidence)

3. System Description  
   Explains what is in scope, system boundaries, services provided, infrastructure, and key processes.

4. Controls and Testing  
   Lists the vendor's controls, the auditor's testing procedures, and the results.

5. Exceptions and Findings  
   Describes control failures or deviations. Analysts evaluate severity, root cause, impact, and remediation.

6. Subservice Organizations  
   Lists other companies the vendor relies on (for example cloud providers). These introduce dependency risk.

## What Vendor Risk Analysts Look For in a SOC 2

Common areas of focus:

- Missing or weak MFA  
- Poor access control practices  
- Lack of logging or alerting  
- Encryption gaps  
- Incident response coverage  
- Number and nature of exceptions  
- Reliance on subservice organizations  
- Outdated or inconsistent policies  
- Incomplete monitoring or evidence  

A structured approach to reviewing these items is critical for forming a well supported risk conclusion.

## How to Use SOC 2 in Due Diligence

A practical workflow:

1. Confirm that the report is Type II when possible.  
2. Check that the audit period is recent, ideally within the last 12 months.  
3. Review the scope to make sure relevant systems and services are included.  
4. Read the auditor's opinion for any major concerns.  
5. Review controls and test results, paying attention to failures and exceptions.  
6. Assess the severity of any gaps and their potential impact on your organization.  
7. Document risks and recommended remediation steps.  
8. Feed the results into your vendor scoring and approval process.

## Why This Matters in Interviews

Being able to read, interpret, and summarize a SOC 2 report is one of the top skills hiring managers test for in Vendor Risk, TPRM, and GRC roles. It shows:

- Understanding of control effectiveness  
- Awareness of risk and impact  
- Ability to perform due diligence  
- Strong analytical and communication skills  

Author: Logan McDermott

---

**Author:** Logan McDermott  
