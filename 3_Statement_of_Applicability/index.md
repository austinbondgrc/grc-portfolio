---
title: 📁 Statement of Applicability
parent: 🛡️ Governance, Risk & Compliance (GRC) Portfolio
nav_order: 3
has_children: true
---

# Statement of Applicability

**MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
**Prepared by:** Austin Bond, Junior GRC Professional

## 📌 Folder Overview

This folder contains the definitive bridge between risk assessment and operational security. The Statement of Applicability (SoA) is the most heavily scrutinized document during an ISO 27001 certification audit. It dictates exactly which security controls the organization has chosen to implement to treat the risks identified in the Risk Register.

The document in this folder demonstrates a comprehensive, audit-ready matrix aligned strictly to the newly updated ISO/IEC 27001:2022 framework, consolidating the historical 14 domains into the modern 4-theme structure (Organizational, People, Physical, and Technological).

---

## 📄 Documents in This Folder

### 1. Statement of Applicability (SoA) — Current Release

**File:** `MT-ISMS-SOA-001_v1.1_statement-of-applicability.xlsx`

| Field | Detail |
| :--- | :--- |
| **ISO 27001:2022 Reference** | Clause 6.1.3(d) (Information security risk treatment) |
| **Format** | Excel Spreadsheet |
| **Status** | Current — v1.1 (continual improvement release) |

**What this document does:**  
It evaluates all 93 controls from Annex A, explicitly stating whether they are applicable or not. It provides the business and regulatory justification for that decision, details the current implementation status, and references the specific technical tools or governance policies used by MunichTech to satisfy the requirement.

**Key consulting decisions:**

*   **Risk-Driven Traceability:** Rather than treating the SoA as a generic compliance checklist, every control features a **Linked Risk ID** column connecting it directly back to the Risk Register (`MT-ISMS-RR-001`). This proves the security architecture is built specifically to address actual business risks.
*   **Modern DevSecOps Architecture:** Control implementations are not based on legacy IT. They explicitly reference modern cloud-native tooling necessary for an AWS-hosted SaaS company, including HashiCorp Terraform (IaC), AWS GuardDuty, CrowdStrike EDR, and Snyk Software Composition Analysis.
*   **German Regulatory Integration:** Legal justifications are woven directly into the control selections. The matrix explicitly references the **Betriebsrat** (Works Council) regarding employee monitoring controls, the **HinSchG** (Whistleblower Act) for incident reporting, and BayLDA/DSGVO requirements for log retention.

**v1.1 release notes (continual improvement):**

*   **A.5.13 — Labelling of information:** moved from **Partially Implemented** to **Fully Implemented**; the labelling scheme is now standardised and technically enforced across M365 and Atlassian.
*   **A.5.27 — Learning from information security incidents:** moved from **Partially Implemented** to **Fully Implemented**; the post-incident review workflow is standardised with tracked actions and board visibility.
*   **Audit linkage:** updates align to internal audit and CAP closure practice (`MT-ISMS-AUD-001`, `MT-ISMS-CAP-001`), closing the Check → Act loop.

### 2. Statement of Applicability (SoA) — Baseline Archive

**File:** `MT-ISMS-SOA-001_v1.0_statement-of-applicability.xlsx`

The v1.0 SoA is retained unchanged as the baseline implementation snapshot. Keeping prior versions immutable demonstrates audit-trail integrity and continual-improvement discipline.

---

## 🗺️ How This Folder Fits the Wider ISMS Portfolio

```text
ISO 27001:2022 ISMS Portfolio — MunichTech GmbH
│
├── 📁 1 — Governance & Scope
│   ├── MT-ISMS-SCO-001  Scope & Context    (Clause 4)
│   └── MT-ISMS-POL-001  InfoSec Policy     (Clause 5)
│
├── 📁 2 — Risk Management                    
│   ├── MT-ISMS-IAR-001  Asset Register     (Annex A 5.9)
│   ├── MT-ISMS-RAM-001  Risk Methodology   (Clause 6.1.2)
│   └── MT-ISMS-RR-001   Risk Register      (Clause 6.1.3)
│
├── 📁 3 — Statement of Applicability         <-- YOU ARE HERE
│   └── MT-ISMS-SOA-001  SoA — 93 Controls  (Clause 6.1.3)
│
├── 📁 4 — Regulatory Compliance
│   ├── NIS2 Incident Reporting Workflow    (NIS2 Art. 23)
│   └── DSGVO Records of Processing         (DSGVO Art. 30)
│
└── 📁 5 — Audit & Metrics
    ├── Internal Audit Checklist            (Clause 9.2)
    └── Management Review Agenda            (Clause 9.3)
```

---

## ⚖️ Regulatory Alignment

| Regulation | Relevance to This Folder |
| :--- | :--- |
| **ISO/IEC 27001:2022** | Fulfills the mandatory requirement of Clause 6.1.3(d) to produce a Statement of Applicability containing necessary controls, justifications, and implementation status. |
| **EU NIS2 Directive** | The SoA directly maps to the "minimum security measures" mandated by NIS2 Article 21, specifically regarding incident handling, supply chain security, and cryptography. |
| **DSGVO / GDPR** | The SoA serves as the definitive, auditable ledger of the Technical and Organizational Measures (TOMs) required by DSGVO Article 32 (Security of Processing). |
| **BaFin BAIT** | Client flow-down requirements regarding Identity & Access Management and IT Operations are documented and justified within the matrix. |

---

## 📥 Download Documents
[📁 Browse folder on GitHub](https://github.com/austinbondgrc/grc-portfolio/tree/main/3_Statement_of_Applicability){: .btn }
[⬇ Download full portfolio (ZIP)](https://github.com/austinbondgrc/grc-portfolio/archive/refs/heads/main.zip){: .btn .btn-primary }

---

## 📬 Contact

**Austin Bond**  
Junior GRC Professional | ISO 27001 Provisional Implementer *(Completed)*/Auditor *(In Progress)*, NIS2 Provisional Implementer *(Completed)*  [LinkedIn](https://linkedin.com/in/austinbondgrc)
