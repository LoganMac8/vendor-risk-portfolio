# SOC 2 Trust Services Criteria Explained for Vendor Risk Analysts

The Trust Services Criteria (TSC) are the backbone of SOC 2. They define the security principles auditors use to evaluate whether a vendor protects customer data effectively. This guide breaks down each criterion in practical terms with examples, typical risks, and how a Vendor Risk Analyst can apply them.

## 1. Security (Common Criteria)

Security focuses on protecting systems and data from unauthorized access, disclosure, or modification. Every SOC 2 engagement includes Security controls.

Examples of Security controls:  
- Multi factor authentication (MFA)  
- Role based access control (RBAC)  
- Logging and monitoring  
- Network segmentation  
- Security awareness training  
- Vulnerability scanning and patching  

What auditors look for:  
- Access is limited to authorized users  
- Activity logs exist and are reviewed  
- Security incidents are detected, escalated, and resolved  

Risks if Security controls are weak:  
- Account compromise  
- Unauthorized system changes  
- Undetected insider activity  
- Increased exposure to external attacks  

Vendor Risk perspective:  
Security is the foundation for the rest of the criteria. Weak Security controls will affect the overall risk rating regardless of how strong other areas are.

## 2. Availability

Availability focuses on system reliability and uptime. Controls in this category help ensure that a vendor can deliver services consistently and recover from disruptions.

Examples of Availability controls:  
- Uptime monitoring and dashboards  
- Documented incident response processes  
- Disaster recovery (DR) plans  
- Redundant infrastructure  
- Capacity planning  

What auditors look for:  
- DR plans exist and are tested  
- Service level agreements (SLAs) are tracked  
- Incidents are logged, analyzed, and resolved  

Risks if Availability is weak:  
- Extended outages  
- SLA violations  
- Service instability  
- Operational disruption for customers  

Vendor Risk perspective:  
Availability matters most for vendors that are critical to your operations. For example, core SaaS platforms, payment processors, and infrastructure providers.

## 3. Processing Integrity

Processing Integrity ensures that systems process data completely, accurately, and in a timely manner.

Examples of Processing Integrity controls:  
- Input validation checks  
- Error detection and logging  
- Reconciliation procedures  
- Batch processing checks  
- Change management for logic or calculations  

What auditors look for:  
- Data is processed as intended  
- Errors are detected and corrected  
- Unauthorized changes are prevented or monitored  

Risks if Processing Integrity is weak:  
- Corrupted or incomplete data  
- Duplicate or missing transactions  
- Incorrect reports and outputs  
- Undetected system logic errors  

Vendor Risk perspective:  
Processing Integrity is especially important for vendors handling financial data, analytics, automated processing, or any high volume transactions.

## 4. Confidentiality

Confidentiality addresses the protection of sensitive information from unauthorized disclosure. This can include source code, internal documents, business plans, and non public customer data.

Examples of Confidentiality controls:  
- Encryption at rest and in transit  
- Data loss prevention (DLP) tools  
- Least privilege access control  
- Secure key management  
- Data classification and handling standards  

What auditors look for:  
- Encryption is implemented and managed correctly  
- Access to sensitive data is restricted and reviewed  
- Data retention and disposal processes exist and are followed  

Risks if Confidentiality is weak:  
- Data leaks or exposures  
- Unencrypted backups or copies  
- Insider misuse of data  
- Loss of customer or partner trust  

Vendor Risk perspective:  
You evaluate whether the vendor can protect any non public data you share with them, even if it is not personal data.

## 5. Privacy

Privacy focuses specifically on personal data, including how it is collected, stored, used, shared, and deleted. This often aligns with regulations and privacy laws.

Examples of Privacy related frameworks:  
- GDPR  
- CCPA  
- Company privacy notices and commitments  

Examples of Privacy controls:  
- Consent and notice mechanisms  
- Data subject access and deletion processes  
- Data retention and deletion schedules  
- Privacy impact assessments  
- Transparency in privacy policies  

What auditors look for:  
- Personal data is handled according to published commitments and laws  
- Users can access, correct, or delete their data where required  
- Retention schedules and deletion processes are followed  

Risks if Privacy controls are weak:  
- Regulatory penalties  
- Legal exposure  
- Customer complaints and reputational damage  
- Privacy incidents and investigations  

Vendor Risk perspective:  
If the vendor processes any customer or employee personal data, Privacy becomes a key factor in the risk rating.

## How the Trust Services Criteria Work Together

While each criterion is distinct, they are closely related:

- Security supports the other four criteria  
- Availability relies on secure and stable systems  
- Confidentiality depends on strong access control and encryption  
- Processing Integrity relies on logging, monitoring, and change management  
- Privacy depends on both Security and Confidentiality  

Understanding how these areas connect helps you evaluate the completeness and maturity of a vendor's control environment.

## How Vendor Risk Analysts Apply the TSC

When reviewing a SOC 2 report, you can use the TSC to:

- Prioritize which controls to review in detail  
- Identify gaps that have the highest impact on your business  
- Assign risk levels such as low, medium, high, or critical  
- Create targeted remediation recommendations  
- Decide whether to approve, conditionally approve, or reject a vendor  

The stronger your understanding of the Trust Services Criteria, the more accurately you can evaluate vendors and explain your decisions.

Author: Logan McDermott
