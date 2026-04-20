---
title: Governance and Scope
nav_order: 2
has_children: true
---

# 📁 1 — Governance & Scope

> **MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
> Prepared by: Austin Bond, Junior GRC Consultant

---

## 📌 Folder Overview

This folder contains the foundational governance layer of the MunichTech GmbH 
Information Security Management System (ISMS). These documents represent the 
first and most critical phase of any ISO 27001:2022 implementation — without a 
precisely defined scope and a board-mandated policy, no downstream artifact 
(Risk Register, SoA, or audit programme) has a legitimate anchor.

Both documents have been prepared to a standard suitable for submission to a 
DAkkS-accredited certification body and are cross-referenced throughout the 
wider ISMS portfolio.

---

## 📄 Documents in This Folder

### 1. ISMS Scope and Context Definition
`munichtech_isms-scope-context_v1.0.pdf`

| Field | Detail |
|---|---|
| **Document Reference** | MT-ISMS-SCO-001 |
| **ISO 27001:2022 Clauses** | 4.1, 4.2, 4.3 |
| **Version** | 1.0 |
| **Status** | Final |

**What this document does:**

Defines the precise boundary of the MunichTech GmbH ISMS — what is in scope, 
what is explicitly excluded, and why. It establishes the internal and external 
context in which the ISMS operates, identifying all interested parties and their 
security-relevant needs and expectations.

**Key consulting decisions documented here:**

- Scope boundary defined to satisfy a certifiable audit standard while remaining 
  business-readable for enterprise client due diligence review
- AWS Shared Responsibility Model explicitly articulated to prevent the most 
  common scope confusion in cloud-based ISO 27001 implementations
- Interested Parties table (Clause 4.2) includes the **Betriebsrat (Works 
  Council)** as a formal stakeholder — a German legal requirement under 
  BetrVG § 87 that generic English-language templates consistently miss
- NIS2 entity classification confirmed as **Important Entity (Annex II)** with 
  applicability verified against the BSI NIS2-Betroffenheitsprüfung 
  self-assessment criteria
- Risk Appetite Statement included as a foundational decision-making anchor for 
  the Risk Register — absent from the original template and added based on 
  audit experience
- Correct NIS2 fine tier applied: €7,000,000 / 1.4% global turnover (Important 
  Entity, Article 34) — not the Essential Entity threshold commonly 
  misapplied in generic templates

---

### 2. Information Security Policy
`munichtech_isms-infosec-policy_v1.0.pdf`

| Field | Detail |
|---|---|
| **Document Reference** | MT-ISMS-POL-001 |
| **ISO 27001:2022 Clauses** | 5.1, 5.2, 5.3 |
| **Version** | 1.0 |
| **Status** | Final |

**What this document does:**

Establishes the executive mandate, guiding principles, and accountability 
framework for information security at MunichTech GmbH. This is the top-level 
governance directive from which all subsidiary policies, standards, and 
procedures derive their authority. It fulfils the ISO 27001:2022 Clause 5.2 
requirement for a documented Information Security Policy approved at the 
appropriate level of leadership.

**Key consulting decisions documented here:**

- Executive Policy Statement written as a board-level commitment — not a 
  technical document — reflecting the Clause 5.1 requirement for visible 
  leadership
- **NIS2 Article 20 personal executive liability** explicitly referenced in 
  both the regulatory obligations section and the consequences of 
  non-compliance section — the most effective lever for securing genuine 
  board engagement with the ISMS
- **Key person risk openly acknowledged** in the Roles and Responsibilities 
  section (no dedicated CISO; risk tracked as HR-003 in the Risk Register) — 
  a maturity signal rarely seen in policy documents at this level
- Betriebsrat coordination referenced for both policy communication and 
  disciplinary consequences, reflecting German co-determination law 
  (BetrVG § 87, § 80)
- German translation commitment included — legally and culturally appropriate 
  for a Munich-based workforce
- Policy intentionally concise: ISO 27001:2022 does not reward length — it 
  rewards precision, accountability, and the right content

---

## 🗺️ How This Folder Fits the Wider ISMS Portfolio

```
ISO 27001:2022 ISMS Portfolio — MunichTech GmbH
│
├── 📁 1 — Governance & Scope               ← YOU ARE HERE
│   ├── MT-ISMS-SCO-001  Scope & Context    (Clause 4)
│   └── MT-ISMS-POL-001  InfoSec Policy     (Clause 5)
│
├── 📁 2 — Risk Management
|   ├── Information Asset Register          (Annex A 5.9)
│   ├── Risk Assessment Methodology         (Clause 6.1)
│   └── Risk Register                       (Clause 6.1 / 6.2)
│
├── 📁 3 — Statement of Applicability
│   └── SoA — 93 Annex A Controls           (Clause 6.1.3)
│
├── 📁 4 — Regulatory Compliance
│   |── NIS2 Incident Reporting Workflow    (NIS2 Art. 23)
│   └── DSGVO RoPA Template                 (DSGVO Art. 30)
|
└── 📁 5 — Audit & Metrics
    ├── Internal Audit Checklist            (Clause 9.2)
    └── Management Review Agenda           (Clause 9.3)
```

---

## ⚖️ Regulatory Alignment

| Regulation | Relevance to This Folder |
|---|---|
| **ISO/IEC 27001:2022** | Clauses 4.1–4.3 (Scope); 5.1–5.3 (Policy & Leadership) |
| **EU NIS2 Directive** | Art. 20 (Management accountability); Art. 21 (Security measures); Annex II (Important Entity classification) |
| **DSGVO / GDPR** | Processing context documented; BayLDA identified as regulatory stakeholder |
| **BSI IT-Grundschutz** | Referenced as supplementary implementation guidance |
| **BetrVG** | § 87 (Co-determination); § 80 (Information rights); § 94 (Personnel data) |
| **KWG / BAIT** | Client-imposed requirements from BaFin-regulated banking clients |

---

## 🧠 Portfolio Notes

This folder represents **Phase 1** of a complete, end-to-end ISO 27001:2022 
ISMS implementation for a fictional B2B Financial Data Analytics SaaS company 
operating under German law.

**Client profile:**

| Field | Detail |
|---|---|
| **Company** | MunichTech GmbH |
| **Industry** | B2B Financial Data Analytics (SaaS) |
| **Location** | Munich, Bavaria, Germany |
| **Infrastructure** | AWS Frankfurt (eu-central-1) |
| **Headcount** | 50 employees |
| **Compliance Drivers** | ISO 27001:2022, EU NIS2 Directive, DSGVO |

All documents in this portfolio are fictional consulting deliverables created 
for portfolio demonstration purposes. Any resemblance to real organisations 
is coincidental.

---

## 📬 Contact

**Austin Bond**  
Junior GRC Consultant | ISO 27001 Provisional Implementer/Auditor, NIS2 Provisional Implementer *(in progress)*  
[LinkedIn](https://linkedin.com/in/austinbondgrc)

