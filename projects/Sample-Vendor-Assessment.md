Sample Vendor Assessment  
Vendor: Nimbus Analytics  
Assessment Type: Initial Security Review

Summary  
This assessment evaluates Nimbus Analytics as part of the Vendor Risk Management process. Evidence reviewed includes their SOC 2 Type II report, ISO 27001 certification, penetration test summary, security questionnaire responses, and supporting documentation for backup, recovery, and incident response. The goal is to determine whether Nimbus Analytics can be approved for use and whether remediation is required prior to onboarding.

Section 1: Vendor Overview  
Vendor Name: Nimbus Analytics  
Service: Cloud-based analytics platform for reporting and data visualization  
Data Shared: Internal business data and limited customer usage metrics  
Integration Type: API-based  
Assessment Objective: Evaluate security posture, identify risks, and determine onboarding readiness.

Section 2: Evidence Reviewed  
- SOC 2 Type II report (Security & Availability)  
- 25-question security questionnaire  
- ISO 27001 Certificate of Conformity  
- Penetration test summary (last 12 months)  
- Backup & recovery policy documentation  
- Incident response plan  

Section 3: SOC 2 Review Summary  
Scope: Analytics platform, data processing pipeline, logging services, administrative portal  

Strengths  
- Mature access control practices  
- MFA enforced for all administrative access  
- Daily logging and monitoring review  
- Quarterly backup testing performed  
- Well-documented change management program  

Exception Noted  
- One access review completed outside the required window (auditor classified as isolated and remediated)

Conclusion  
SOC 2 controls are mature and effective. The exception noted does not materially reduce Nimbus Analytics’ security posture.

Section 4: ISO 27001 Control Review  
Controls Reviewed: A.5, A.6, A.8, A.10, A.15  

Strengths  
- Annual security policy review  
- Mandatory employee security awareness training  
- Monthly vulnerability scanning  
- Encryption applied to all sensitive data  
- Documented supplier lifecycle processes  

Gap Identified  
- Change management documentation lacks rollback procedures  
  *Impact: Slight operational risk but no material control weakness.*

Section 5: Security Questionnaire Review  
Positive Indicators  
- Encryption in transit and at rest  
- Quarterly backup testing  
- Incident response plan reviewed annually  
- Pre-release application testing performed  
- Annual penetration testing  

Clarifications Required  
1. Customer-managed encryption keys not supported  
   (Low impact for this use case)  
2. No customer-specific audit logs  
   (Acceptable due to shared service architecture)

Section 6: Risk Scoring Summary  
Impact Rating: 4  
The vendor processes internal operational data. Outages may delay reporting functions but would not create regulatory or high financial impact.

Likelihood Rating: 3  
Controls are generally strong, though minor issues exist (delayed access review; incomplete rollback documentation).

Final Risk Rating: High Risk  
A remediation plan is required but vendor may be conditionally approved pending completion.

Section 7: Required Remediation  
1. Add rollback procedures to change management documentation  
2. Provide written confirmation that access review processes have been updated to prevent delays  

Remediation Timeline: 30 days

Section 8: Final Recommendation  
Nimbus Analytics is recommended for **Conditional Approval**.  
The vendor demonstrates strong administrative and technical controls supported by SOC 2 and ISO evidence. Identified gaps are minor and can be fully remediated.

Final Decision: Conditional Approval pending remediation evidence.
