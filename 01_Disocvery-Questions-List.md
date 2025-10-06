# 🧭 Discovery Scope Meeting – Hybrid Cloud Security Governance Assessment

**Client:** CloudMed Solutions (Fictional)  
**Consultant:** Dylan Nguyen (IBM SSRC Portfolio Simulation)  
**Date:** October 2025  
**Project Phase:** Discovery & Scoping  
**Objective:** Identify the client’s current hybrid cloud environment, compliance landscape, and GRC maturity to define the scope for a gap assessment and risk register.

---

## 🧠 1. Business Context & Objectives

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| What are your organization’s most critical business functions or services? | Electronic Health Records (EHR) platform and patient portal — must stay operational 24/7 and process sensitive PHI data. | Identifies mission-critical assets (crown jewels) for prioritizing controls. |
| What recent business changes (cloud migration, acquisitions, AI initiatives) have impacted your security landscape? | Ongoing migration of workloads to AWS; exploring AI-assisted analytics for patient data. Increased cloud footprint has complicated security governance. | Links risk to current transformation activities. |
| What are your primary objectives for this engagement (compliance, audit readiness, resilience improvement)? | Primary goal is audit readiness — streamline overlapping HIPAA and SOC 2 requirements to reduce audit effort and increase consistency. | Defines project success criteria. |
| Who are your key stakeholders (executives, compliance officers, system owners)? | IT Director (project sponsor), Chief Compliance Officer, CFO (budget oversight), DevOps team leads. | Determines roles for data collection and sign-off. |

---

## ☁️ 2. Environment & Technology Landscape

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| Can you describe your current IT environment — on-prem, cloud, or hybrid? | Hybrid — legacy billing and EHR systems on-prem; new patient portal and analytics workloads on AWS. | Defines technical boundaries of assessment. |
| Which cloud providers are in use (AWS, Azure, IBM Cloud, GCP)? | Primarily AWS, limited Azure integration via a third-party vendor. | Framework and shared responsibility mapping differ per provider. |
| Do you currently use a GRC or automation platform? | No formal GRC tool — currently using Excel and SharePoint trackers for compliance and risk tracking. | Reveals tool maturity and integration opportunities. |
| How do you manage access, identity, and data classification across environments? | IAM handled manually in AWS; Active Directory for on-prem; limited integration between environments. No unified DLP. | Identifies IAM or DLP gaps. |
| Are there any third-party integrations or vendors handling sensitive data? | Yes — a billing SaaS vendor processes financial data and backup services are outsourced to a managed provider. | Highlights supply-chain and vendor-risk exposure. |

---

## 🔐 3. Frameworks, Regulations & Compliance Scope

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| Which frameworks or regulations does your organization follow (NIST, ISO 27001, SOC 2, HIPAA, PCI DSS)? | HIPAA for healthcare operations; preparing to add SOC 2 due to new enterprise clients. | Defines control baseline. |
| Do you face overlapping compliance requirements across multiple jurisdictions or clients? | Yes — some clients require SOC 2 evidence while operations must remain HIPAA compliant. No formal control crosswalk yet. | Enables multi-framework crosswalk. |
| When was your last external audit or internal compliance review? | HIPAA audit completed 6 months ago; SOC 2 readiness in progress for next year. | Shows maturity and audit cadence. |
| What challenges did you encounter during past audits or assessments? | Manual evidence collection, unclear ownership, and time-consuming documentation (~200 hours per quarter). | Reveals inefficiencies and manual bottlenecks. |

---

## 🧱 4. Governance, Risk & Control Processes

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| How are policies and standards maintained and updated? | Maintained by IT and Compliance in shared folders; reviewed annually but not version-controlled or linked to frameworks. | Evaluates policy governance lifecycle. |
| Do you have a formal risk management process and risk register? | Basic Excel-based risk list; no centralized ownership or automated tracking. | Indicates ability to quantify and track risks. |
| How often are controls tested or validated? | Controls reviewed semi-annually but only for HIPAA scope; cloud controls not yet integrated. | Measures continuous monitoring maturity. |
| Who approves or owns risk acceptance decisions? | IT Director currently approves; escalates to Compliance or CFO if financial impact. No formal risk committee. | Clarifies accountability and escalation. |
| Do you have automation or dashboards for control performance reporting? | None — all reporting done via manual spreadsheets and PowerPoint summaries. | Shows GRC automation maturity and executive visibility. |

---

## 👥 5. People, Awareness & Training

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| What cybersecurity awareness or simulation programs are currently in place? | Annual mandatory training; occasional phishing simulations. | Evaluates human-layer risk posture. |
| Are executives or board members involved in cyber resilience exercises? | No formal involvement yet; discussed adding executive crisis simulations next year. | Demonstrates tone-from-the-top support. |
| Do you have defined roles and responsibilities for security and compliance teams? | Yes, but functions overlap — IT handles most compliance tasks, limited segregation of duties. | Identifies accountability and potential silos. |

---

## 📊 6. Metrics, Reporting & Business Value

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| How do you currently report cyber risk or compliance status to executives? | Quarterly PowerPoint reports; no live dashboards or continuous metrics. | Links cyber data to business KPIs. |
| Do you have KPIs tied to risk reduction, incident response, or audit readiness? | Informal metrics: time to detect/contain incidents and number of controls reviewed. No formal KPIs yet. | Evaluates measurement maturity. |
| Are there specific reports or dashboards you’d like automated or improved? | Executive visibility into risk posture and audit readiness metrics. | Opens opportunities for automation and analytics. |

---

## 🌐 7. Future Vision & Pain Points

| Discovery Question | Client Response / Notes | Why It Matters |
|--------------------|-------------------------|----------------|
| Where do you see the biggest challenges in your hybrid-cloud security posture today? | Maintaining consistent control implementation and visibility between on-prem and AWS; IAM inconsistencies. | Helps prioritize control domains. |
| If you could change one thing about how compliance is managed today, what would it be? | Automate evidence collection and unify frameworks under one compliance system. | Identifies process bottlenecks and quick wins. |
| How does your organization handle emerging risks like AI governance or data residency? | No formal AI governance policy; early discussions around data usage and model training. | Demonstrates forward-looking governance awareness. |

---

## 🧾 Initial Observations (Consultant Notes)

- CloudMed is migrating 60% of workloads to AWS but lacks unified IAM governance across environments.  
- Policies exist but are not mapped to frameworks; compliance tracking remains manual.  
- Audit preparation consumes ~200 hours per quarter due to lack of automation.  
- Risk ownership is informal, with limited executive oversight.  
- Awareness training is reactive, not continuous, and executives are not yet engaged in simulations.  

---

## 🧭 Proposed Scope of Engagement

| Area | Description |
|------|--------------|
| **Framework Baseline** | NIST CSF & HIPAA (healthcare context), mapping to SOC 2 controls. |
| **Systems in Scope** | AWS Cloud workloads, on-prem EHR servers, internal compliance spreadsheets. |
| **Focus Domains** | Governance, Risk, Compliance Automation, Awareness & Reporting. |
| **Deliverables** | Gap Assessment Matrix, Risk Register, Executive Summary Report. |
| **Timeline** | 2-Week Assessment Simulation. |

---

## ✅ Next Steps

1. Validate scope and stakeholder list.  
2. Collect sample control documentation, audit logs, and GRC tool exports (fictional/dummy data).  
3. Begin Gap Assessment mapping against NIST CSF and IBM Active Governance Services capabilities.  
4. Draft Risk Register aligned to high-impact findings.  
5. Prepare Executive Summary and recommendations.

---

**End of Document**
