# ⚠️ Risk Register – CloudMed Solutions  
**Consultant:** Dylan Nguyen (IBM SSRC Portfolio Simulation)  
**Client:** CloudMed Solutions  
**Date:** October 2025  
**Framework Baseline:** NIST CSF + HIPAA + SOC 2  
**Reference Model:** IBM Active Governance Services (AGS) Risk Management Methodology  

---

## 🧩 Purpose  
This register identifies and prioritizes key cybersecurity and compliance risks observed during the hybrid-cloud gap assessment.  
Each risk is evaluated using qualitative ratings for **Likelihood** and **Impact** (1–5 scale), producing an overall **Risk Score (L × I)** to guide remediation priorities.

| Rating | Description |
|--------|--------------|
| **1 – Very Low** | Rare occurrence / minimal business disruption |
| **2 – Low** | Occasional occurrence / minor impact |
| **3 – Moderate** | Possible occurrence / limited operational impact |
| **4 – High** | Likely occurrence / significant impact on operations or compliance |
| **5 – Very High** | Frequent occurrence / severe or regulatory impact |

---

## 🧾 Risk Register Table

| ID | Risk Description | Likelihood (1–5) | Impact (1–5) | Risk Score | Control Domain | Current Mitigation / Observations | Recommended Action | Owner | Status |
|----|------------------|------------------|---------------|-------------|----------------|----------------------------------|--------------------|--------|---------|
| R1 | **Inconsistent IAM governance across on-prem and AWS environments may result in unauthorized access or privilege escalation.** | 4 | 5 | **20 (High)** | Identity & Access Management | Separate identity systems (AD + AWS IAM) not federated; manual provisioning/deprovisioning. | Implement centralized IAM via SSO/Federation; enforce MFA and least privilege across all environments. | IT Director | Open |
| R2 | **Manual evidence collection process leads to audit delays and non-compliance risk for HIPAA/SOC 2.** | 4 | 4 | **16 (High)** | Compliance & Audit | Audit evidence gathered manually via spreadsheets and email. | Deploy GRC platform (OpenPages or Archer) to automate evidence collection and workflow tracking. | Compliance Officer | Open |
| R3 | **Lack of unified risk management process results in limited visibility into enterprise risks.** | 3 | 5 | **15 (High)** | Governance & Risk | No formal risk committee; Excel risk list only. | Establish formal risk governance board; use centralized risk register integrated with GRC tool. | CISO / Compliance | Open |
| R4 | **Policy and control documentation not mapped to frameworks or version-controlled, increasing audit inconsistencies.** | 3 | 4 | **12 (Medium)** | Policy Management | Policies exist but unlinked to NIST/HIPAA/SOC 2; revisions ad hoc. | Create control mapping matrix; automate versioning and review workflow. | Compliance Officer | Open |
| R5 | **Limited visibility and alerting across hybrid environment may delay detection of security incidents.** | 3 | 5 | **15 (High)** | Monitoring & Detection | No unified SIEM or monitoring dashboard; alerts handled per system. | Deploy central log aggregation (e.g., CloudWatch + on-prem SIEM integration); develop detection KPIs. | IT Security Lead | Open |
| R6 | **No formal AI governance framework for patient data analytics could lead to privacy violations or model bias.** | 2 | 5 | **10 (Medium)** | Data Governance / AI Ethics | Early-stage AI use; no policy on training data or model transparency. | Establish AI governance policy aligned to IBM watsonx governance principles. | Data Science Lead | Planned |
| R7 | **Insufficient security awareness and executive-level involvement in cyber resilience exercises.** | 3 | 3 | **9 (Medium)** | People & Awareness | Basic annual training; no simulations for leadership. | Develop tiered cyber awareness program including executive crisis simulations. | HR / CISO | Open |
| R8 | **Third-party vendors with access to sensitive data lack continuous compliance monitoring.** | 3 | 4 | **12 (Medium)** | Third-Party Risk | Vendor assessments occur annually via spreadsheets; no real-time visibility. | Implement vendor risk management module in GRC tool; automate evidence requests. | Compliance Manager | Open |
| R9 | **Disaster Recovery and Business Continuity plans are outdated and untested for hybrid workloads.** | 2 | 5 | **10 (Medium)** | Resilience & Continuity | DR tested annually for on-prem only; AWS workloads excluded. | Conduct hybrid DR testing and include cloud failover in continuity planning. | IT Operations | Planned |
| R10 | **Lack of real-time compliance dashboard limits executive visibility into risk posture.** | 4 | 3 | **12 (Medium)** | Reporting & Metrics | Reports are manual PowerPoints; limited KPIs. | Build automated PowerBI or watsonx dashboards for compliance telemetry. | IT / Compliance | Open |

---

## 📊 Summary Insights

- **Top 3 Risks (by score):**  
  1. R1 – Inconsistent IAM Governance (Score 20)  
  2. R2 – Manual Audit & Evidence Collection (Score 16)  
  3. R3 – Lack of Formal Risk Governance (Score 15)

- **Themes Identified:**  
  - Fragmented identity and control ownership between environments.  
  - Overreliance on manual processes for compliance tracking.  
  - Limited automation and visibility at the governance layer.  

---

## 🎯 Strategic Recommendations

1. **Implement Integrated GRC Platform:** Automate control mapping, risk tracking, and evidence collection across HIPAA and SOC 2.  
2. **Strengthen Governance Structure:** Create a Cyber Governance Committee and define clear risk ownership.  
3. **Centralize Identity and Monitoring:** Integrate IAM and SIEM tools for unified hybrid-cloud visibility.  
4. **Develop Executive Dashboards:** Translate technical risk metrics into business-impact visuals for leadership.  
5. **Adopt AI Governance Policy:** Address emerging risks proactively aligned with IBM’s watsonx governance framework.  

---

**End of Document**
