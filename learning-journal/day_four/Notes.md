# Day 4 Notes — Questionnaire + Risk Scoring Model

## What I Worked On Today
Today I focused on building two core tools used in real Vendor Risk programs:
1. A 25-question Vendor Security Questionnaire  
2. A full Likelihood × Impact Risk Scoring Model  

These are foundational artifacts in TPRM and are used every time a new vendor is onboarded.

---

## Notes on Questionnaire Design
I started by reviewing the major security domains used in SOC 2, ISO, and TPRM frameworks. The goal was to cover each relevant area without overwhelming vendors with unnecessary questions.

Key categories included:
- Access control  
- Policies & HR security  
- Asset management & data protection  
- Logging, monitoring, and incident response  
- Cloud security & shared responsibility  
- Subprocessors and supply chain risk  
- Change management / SDLC  
- Business continuity  

I kept the questionnaire to 25 questions because that’s a realistic number that companies actually use. Anything above ~35 questions becomes excessive and hurts response quality.

---

## Notes on the Risk Scoring Model
The core formula is:
**Risk Score = Likelihood × Impact**

- Likelihood = how often something could go wrong  
- Impact = how bad it would be if it did  

1–5 scoring for both gives a consistent 1–25 range.

I created clear thresholds for risk levels:
- **1–5: Low**  
- **6–10: Medium**  
- **11–16: High**  
- **17–25: Critical**

These thresholds map cleanly to actions:
- Low → simple review  
- Medium → validate SOC2/ISO evidence  
- High → remediation required  
- Critical → leadership approval or reject  

---

## Why These Tools Matter
These two documents form the backbone of vendor reviews:
- The questionnaire tells me whether the vendor’s controls are mature  
- The scoring model quantifies risk in a way leadership can understand  

Both tools will be used directly in my Day 5 Vendor Assessment project.

---

## Portfolio Files Added Today
- `questionnaires/Vendor-Security-Questionnaire.md`
- `risk-scoring/Vendor-Risk-Scoring-Explained.md`
- `risk-scoring/Risk-Heatmap.png`

