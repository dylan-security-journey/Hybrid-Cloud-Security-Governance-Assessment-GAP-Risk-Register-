# 🔍 Gap Assessment – CloudMed Solutions  
**Consultant:** Dylan Nguyen (IBM SSRC Portfolio Simulation)  
**Client:** CloudMed Solutions  
**Date:** [Insert Date]  
**Framework Baseline:** NIST Cybersecurity Framework (CSF) + HIPAA + SOC 2 Mapping  
**Reference Model:** IBM Active Governance Services (AGS) Capabilities  
**Objective:** Identify control, process, and governance gaps in CloudMed’s hybrid-cloud security posture to improve compliance automation, audit readiness, and executive visibility.

---

## 🧱 Maturity Scale
| Level | Description |
|--------|--------------|
| **1 – Nonexistent** | No formal control, process, or awareness. |
| **2 – Ad Hoc** | Informal or inconsistent practices. |
| **3 – Defined** | Documented but partially implemented. |
| **4 – Managed** | Consistently implemented and measured. |
| **5 – Optimized** | Fully automated and continuously improved. |

---

## 🧩 Gap Assessment Table

| NIST CSF Function | IBM AGS Capability | Current Maturity | Target | Gap | Key Findings | Recommendation |
|--------------------|--------------------|------------------|--------|-----|---------------|----------------|
| **Identify** | **Cyber Risk Management** | 3 | 5 | 2 | Risk register exists but no centralized ownership or automation; risk decisions approved ad hoc by IT Director. | Establish formal risk committee; integrate risk registry into GRC tool for accountability and tracking. |
| **Protect** | **Cyber Policy & Compliance Management** | 2 | 5 | 3 | Policies exist for HIPAA but are manually tracked and not mapped to SOC 2; version control inconsistent. | Implement automated policy management and control mapping; align HIPAA controls to SOC 2 for unified reporting. |
| **Detect** | **Cyber AI & Analytics** | 2 | 4 | 2 | Limited visibility across hybrid environment; no continuous control monitoring or unified dashboard. | Deploy analytics dashboards (PowerBI/watsonx) for continuous control performance and anomaly detection. |
| **Respond** | **Cyber Audit Support** | 3 | 5 | 2 | Audit evidence collection and reporting are manual; high resource drain during audit season. | Automate evidence collection and tracking through a centralized GRC platform (e.g., OpenPages or Archer). |
| **Recover** | **Cyber Strategy & Resiliency** | 3 | 4 | 1 | Business continuity and DR plans exist but are not tested regularly; no simulation exercises. | Conduct executive-level crisis simulations and annual recovery testing for hybrid workloads. |
| **Govern** | **Governance Structure & Oversight** | 2 | 5 | 3 | No formal cybersecurity governance board; decisions remain siloed between IT and compliance. | Establish enterprise-level cyber governance board to oversee policy, risk, and compliance alignment. |
| **Educate** | **People Risk & Awareness** | 3 | 4 | 1 | Basic training and occasional phishing simulations; no ongoing awareness culture or exec participation. | Develop a tiered awareness program (staff → exec) including cyber simulations and GRC accountability modules. |

---

## 📊 Summary of Findings

**Key Strengths:**
- Foundational HIPAA compliance processes are in place.  
- Executive leadership supports maturing compliance posture.  
- Cloud migration provides opportunity for automation and visibility.  

**Key Gaps:**
- Inconsistent IAM and control mapping across on-prem and AWS.  
- Lack of unified GRC platform for policy, audit, and risk tracking.  
- Manual evidence collection causing audit inefficiencies.  
- No cross-functional governance committee or formalized risk acceptance process.  
- Limited automation for continuous monitoring and compliance reporting.  

---

## 💡 Recommendations by Priority

| Priority | Action | Business Impact |
|-----------|---------|-----------------|
| **High** | Implement integrated GRC solution (IBM OpenPages or Archer) to centralize controls, automate evidence, and track risk mitigation. | Reduces audit preparation time by ~40%, improves accountability. |
| **High** | Formalize Cyber Governance Committee with executive visibility. | Ensures ownership and oversight across IT, compliance, and business units. |
| **Medium** | Map HIPAA and SOC 2 controls for cross-framework compliance. | Reduces duplication and audit fatigue. |
| **Medium** | Deploy PowerBI/watsonx dashboards for real-time compliance telemetry. | Improves reporting and risk awareness at the leadership level. |
| **Low** | Expand awareness training to include crisis simulation workshops. | Builds cyber-resilient culture and reduces human risk factors. |

---

## 📁 Deliverables Produced
- `02_Gap_Assessment_Table.md` (this file)  
- `03_Risk_Register.xlsx` *(to be created in next phase)*  
- `04_Executive_Summary.pdf` *(final presentation-style report)*  

---

**End of Document**
