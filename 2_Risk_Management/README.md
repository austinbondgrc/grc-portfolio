---
title: Risk Management
nav_order: 3
has_children: true
---

# 📁 2 — Risk Management

> **MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
> Prepared by: Austin Bond, Junior GRC Consultant

---

## 📌 Folder Overview

This folder contains the operational engine of the MunichTech GmbH Information 
Security Management System (ISMS). Risk management is the mechanism by which 
the abstract directives in the Information Security Policy are translated into 
actionable, prioritized security controls.

The documents in this folder demonstrate a complete, end-to-end risk lifecycle 
compliant with **ISO 27001:2022 Clauses 6.1.2 and 6.1.3**, moving from asset 
identification through methodology definition, and culminating in a board-ready 
Risk Register.

---

## 📄 Documents in This Folder

### 1. Information Asset Register
`MT-ISMS-IAR-001_v1.0.xlsx`

| Field | Detail |
|---|---|
| **ISO 27001:2022 Reference** | Annex A 5.9 (Inventory of information and associated assets) |
| **Format** | Excel Spreadsheet |

**What this document does:**
Establishes the foundation for risk assessment by cataloging the organization’s 
critical information, software, physical, and human assets. It assigns baseline 
Confidentiality, Integrity, and Availability (CIA) scores to each asset, which 
feed directly into the Risk Register calculations.

**Key consulting decisions:**
- Clear segregation of duties demonstrated between **Asset Owners** (accountability) 
  and **Custodians** (technical management).
- **People as Assets:** Privileged DevOps personnel are explicitly tracked as 
  assets, reflecting advanced threat modeling logic.
- Regulatory flags (DSGVO and NIS2) are embedded at the asset level to instantly 
  identify systems subject to mandatory breach reporting timelines.

---

### 2. Risk Assessment Methodology
`MT-ISMS-RAM-001_v1.0.pdf`

| Field | Detail |
|---|---|
| **ISO 27001:2022 Reference** | Clause 6.1.2 (Information security risk assessment) |
| **Format** | PDF Document |

**What this document does:**
Defines the mathematical and qualitative framework used to identify, analyze, 
and evaluate information security risks. It establishes the criteria for risk 
acceptance (anchored to the board's Risk Appetite Statement in Clause 4) and 
ensures risk assessments produce consistent, valid, and comparable results.

**Key consulting decisions:**
- Utilizes a standard qualitative scoring model: **Risk = Asset Value (CIA) × 
  Threat Likelihood × Vulnerability Severity**.
- Defines clear, business-readable impact thresholds (e.g., defining a "High" 
  impact in terms of actual SLA penalties or DSGVO fines, rather than generic 
  IT metrics).

---

### 3. Information Security Risk Register
`MT-ISMS-RR-001_v1.0.xlsx`

| Field | Detail |
|---|---|
| **ISO 27001:2022 Reference** | Clause 6.1.2, 6.1.3, 6.2 |
| **Format** | Excel Spreadsheet |

**What this document does:**
The central operational artifact of the ISMS. It applies the Methodology to the 
Asset Register to identify specific threat scenarios. It calculates inherent risk, 
documents the selected risk treatment option (Accept, Mitigate, Transfer, Avoid), 
assigns mitigating controls from Annex A, and calculates residual risk.

**Key consulting decisions:**
- Demonstrates translation of highly technical vulnerabilities (e.g., unpatched 
  S3 bucket exposure) into executive-level business risks (financial exposure 
  under DSGVO Art. 83).
- Threat actors modeled against actual financial sector threat intelligence 
  (e.g., ENISA Threat Landscape).
- Connects directly to the Statement of Applicability (SoA) by referencing specific 
  Annex A 2022 controls used for risk mitigation.

---

## 🗺️ How This Folder Fits the Wider ISMS Portfolio

```
ISO 27001:2022 ISMS Portfolio — MunichTech GmbH
│
├── 📁 1 — Governance & Scope
│   ├── MT-ISMS-SCO-001  Scope & Context    (Clause 4)
│   └── MT-ISMS-POL-001  InfoSec Policy     (Clause 5)
│
├── 📁 2 — Risk Management                    ← YOU ARE HERE
│   ├── MT-ISMS-IAR-001  Asset Register     (Annex A 5.9)
│   ├── MT-ISMS-RAM-001  Risk Methodology   (Clause 6.1.2)
│   └── MT-ISMS-RR-001   Risk Register      (Clause 6.1.3)
│
├── 📁 3 — Statement of Applicability
│   └── SoA — 93 Annex A Controls           (Clause 6.1.3)
│
├── 📁 4 — Regulatory Compliance
│   ├── NIS2 Incident Reporting Workflow    (NIS2 Art. 23)
│   └── DSGVO Records of Processing        (DSGVO Art. 30)
│
└── 📁 5 — Audit & Metrics
    ├── Internal Audit Checklist            (Clause 9.2)
    └── Management Review Agenda           (Clause 9.3)
```

## ⚖️ Regulatory Alignment

| Regulation | Relevance to This Folder |
|---|---|
| **ISO/IEC 27001:2022** | Clause 6.1 (Actions to address risks); Clause 8.2/8.3 (Risk assessment & treatment execution); Annex A 5.9 (Asset inventory) |
| **EU NIS2 Directive** | Risk assessments prioritize critical infrastructure availability; aligns with Art. 21 minimum security measure requirements |
| **DSGVO / GDPR** | Confidentiality impacts are scored heavily against DSGVO Art. 32 (Security of processing) requirements |

---

## 📬 Contact

**Austin Bond**  
Junior GRC Consultant | ISO 27001 Provisional Implementer/Auditor, NIS2 Provisional Implementer (in progress)
[LinkedIn](https://www.linkedin.com/in/austingrc)
