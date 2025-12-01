# Day 5 — Notes
## Portfolio Project: Vendor Risk Assessment (Cloudflare)

### 1. Choosing the Vendor
I selected **Cloudflare** because:
- It represents a real-world SaaS provider organizations rely on.
- Their public Trust Center allows safe, NDA-free analysis.
- They provide meaningful security features (WAF, DNS, Zero Trust, CDN) that impact risk scoring.

### 2. Reviewing Public Documentation
Today I reviewed:
- Cloudflare Trust Center
- Security whitepapers
- Subprocessor lists
- Incident response commitments
- Public SOC 2 summary information

Notes:
- Cloudflare publishes more security details than most vendors.
- Documentation is structured, clear, and shows strong governance maturity.

### 3. Completing the Vendor Security Questionnaire
I filled out my 25-question security questionnaire based on:
- Public evidence
- Cloudflare’s own published control descriptions
- Industry expectations for SaaS vendors

Key Strengths Observed:
- Strong identity and access management model
- Mature logging and monitoring
- Excellent DDoS, WAF, and Zero Trust posture
- Good transparency around subprocessors

Potential Weaknesses:
- Heavy shared responsibility model
- Misconfiguration risk for customers
- Dependency risk if a company relies heavily on Cloudflare DNS

### 4. Identifying Key Risks
Three primary risks identified:
1. **Dependency Risk** – High organizational reliance on edge/security services.
2. **Shared Responsibility Gaps** – Customer configuration errors.
3. **Subprocessor Dependencies** – Additional external entities in the supply chain.

### 5. Risk Scoring
Using my L × I scoring model:
- Dependency risk: 10 (Medium)
- Shared responsibility gaps: 9 (Medium)
- Subprocessor risk: 6 (Medium)

Residual Risk: **Low–Medium**  
Final Recommendation: **Approved**

### 6. Building the PDF Report
I assembled:
- Executive summary
- Questionnaire summary
- Risk scoring table
- Recommendations
- Final decision

This now exists in the `/portfolio` folder as `Cloudflare_Assessment.pdf`.

### 7. Skills Practiced Today
- Evidence review
- Vendor intake analysis
- Questionnaires
- Risk scoring
- Professional report writing
- Translating technical controls into business risk
