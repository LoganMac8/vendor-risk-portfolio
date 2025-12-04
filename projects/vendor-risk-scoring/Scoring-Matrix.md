# Vendor Risk Scoring Matrix  
This scoring matrix defines the numeric values used to calculate a vendor’s final risk score using the Likelihood × Impact model.  
Each factor is scored from **1 (Low)** to **5 (Very High)** and mapped to consistent definitions to ensure repeatability across assessments.

---

## 1. Likelihood Scoring Matrix  

### **1.1 Control Maturity**
| Score | Description |
|-------|-------------|
| 1 | Strong controls, SOC 2 Type II, ISO 27001, no exceptions |
| 2 | Strong controls with minor exceptions or gaps |
| 3 | Basic controls, limited testing, questionnaire only |
| 4 | Weak controls, multiple gaps, inconsistent practices |
| 5 | No controls, no testing, significant cybersecurity exposure |

### **1.2 Incident History**
| Score | Description |
|-------|-------------|
| 1 | No security incidents in past 3 years |
| 2 | Minor incidents with complete remediation |
| 3 | One moderate incident, controlled impact |
| 4 | Multiple incidents or repeat issues |
| 5 | Recent major breach or public compromise |

### **1.3 Technology Exposure**
| Score | Description |
|-------|-------------|
| 1 | Simple SaaS, minimal data handling, limited integration |
| 2 | API usage with minor exposure |
| 3 | Multi-system integration, moderate attack surface |
| 4 | High exposure (network access, SSO admin, data sync) |
| 5 | Deep access into environment or critical production systems |

### **1.4 Vulnerability Management**
| Score | Description |
|-------|-------------|
| 1 | Mature patching program, monthly scans, proven remediation |
| 2 | Strong process with occasional gaps |
| 3 | Basic program with inconsistent timelines |
| 4 | Weak patching, limited scanning |
| 5 | No formal vulnerability management observed |

### **1.5 Operational Stability**
| Score | Description |
|-------|-------------|
| 1 | Stable company with strong processes |
| 2 | Minor operational risks |
| 3 | Noticeable gaps in staffing or documentation |
| 4 | High turnover, inconsistent service delivery |
| 5 | Operational instability or financial risk indicators |

---

## 2. Impact Scoring Matrix  

### **2.1 Data Sensitivity**
| Score | Description |
|-------|-------------|
| 1 | Public or non-sensitive data only |
| 2 | Internal-only data |
| 3 | Confidential business data |
| 4 | Customer or regulated personal data |
| 5 | Highly sensitive PII, PHI, financial data, or authentication data |

### **2.2 Regulatory Obligations**
| Score | Description |
|-------|-------------|
| 1 | No regulatory relevance |
| 2 | Minor contractual obligations only |
| 3 | CCPA/GDPR exposure (non-sensitive) |
| 4 | HIPAA, PCI, or significant privacy obligations |
| 5 | Multiple regulatory frameworks with financial penalties possible |

### **2.3 Business Criticality**
| Score | Description |
|-------|-------------|
| 1 | Nice-to-have tool, minimal impact |
| 2 | Important but non-essential |
| 3 | Supports critical team workflows |
| 4 | Major business dependency |
| 5 | System outage would halt operations or revenue |

### **2.4 Financial Exposure**
| Score | Description |
|-------|-------------|
| 1 | Negligible financial risk |
| 2 | Low potential cost impact |
| 3 | Noticeable operational cost or downtime risk |
| 4 | Significant potential financial loss |
| 5 | High potential regulatory or breach-related penalties |

### **2.5 Reputation & Customer Risk**
| Score | Description |
|-------|-------------|
| 1 | No customer-facing impact |
| 2 | Very limited customer exposure |
| 3 | Moderate customer impact potential |
| 4 | High customer dependency |
| 5 | Direct impact to customer trust or brand damage |

---

## 3. Scoring Table Summary  
This table provides a quick visual reference for all scoring values.

| Category | 1 | 2 | 3 | 4 | 5 |
|----------|---|---|---|---|---|
| Control Maturity | Strong | Minor Gaps | Basic | Weak | None |
| Incident History | None | Minor | Moderate | Repeated | Major |
| Tech Exposure | Minimal | Low | Medium | High | Extreme |
| Vulnerability Mgmt | Mature | Good | Basic | Weak | None |
| Operational Stability | Stable | Minor Risk | Moderate | Weak | Failing |
| Data Sensitivity | Public | Internal | Confidential | Customer | Regulated |
| Regulatory | None | Low | Medium | High | Very High |
| Criticality | Low | Moderate | Important | Major | Critical |
| Financial Exposure | Low | Low-Med | Medium | High | Severe |
| Reputation | None | Low | Medium | High | Severe |

---

## 4. Usage  
This matrix is used by the Vendor Risk Team to ensure every vendor is scored using **identical definitions**.  
This eliminates subjective judgment and ensures fair, consistent, audit-ready assessments.

---

