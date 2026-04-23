# 📁 Audit & Metrics

**MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
**Prepared by:** Austin Bond, Junior GRC Consultant

## 📌 Folder Overview

This folder proves that an Information Security Management System (ISMS) is not a static, one-time documentation project, but a living, continuously improving operational framework. 

The documents in this folder demonstrate the ability to execute the critical "Check" and "Act" phases of the Deming Cycle (Plan-Do-Check-Act). By conducting rigorous, evidence-based internal audits and translating those technical findings into executive-level management reviews, this folder showcases the operational maturity required to maintain a DAkkS-accredited ISO 27001 certification over time.

---

## 📄 Documents in This Folder

### 1. Internal Audit Checklist & Working Paper

**File:** `MT-ISMS-AUD-001_v1.0.pdf`

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | ISO/IEC 27001:2022 (Clause 9.2) |
| **Format** | PDF Document (Audit Working Paper) |

**What this document does:**  
It provides a structured, evidence-based evaluation of the ISMS controls. Rather than relying on interviews, it demands specific technical artifacts (e.g., AWS console reviews, MDM policies) to prove conformity, and establishes a formal Corrective Action Plan (CAP) tracking mechanism for identified failures.

**Key consulting decisions:**

*   **Evidence Traceability (The "Show Me" Rule):** The audit notes avoid generic statements. They cite exact, verifiable artifacts (e.g., specific AWS Account IDs and signed PDF file names) to ensure the audit trail is legally defensible during an external assessment.
*   **Realistic Non-Conformities:** Includes a deliberate Minor Non-Conformity (MiNC) regarding a missing executive signature. This proves an understanding of the real-world audit lifecycle and the necessity of prescribing Corrective Action Plans (CAPs).
*   **Accountability Mapping:** Every finding that requires remediation is strictly mapped to a specific CAP Owner (e.g., CISO / Head of Engineering) and a target remediation date, closing the loop on identified vulnerabilities.

### 2. Management Review Agenda & Minutes

**File:** `MT-ISMS-MRA-001_v1.0.pdf`

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | ISO/IEC 27001:2022 (Clause 9.3) |
| **Format** | PDF Document (Board Level Minutes) |

**What this document does:**  
It serves as the definitive record of executive oversight for the ISMS. It translates technical DevSecOps metrics, audit findings, and risk treatments into business language, forcing the Executive Board to formally acknowledge risks, allocate budget, and approve the system's readiness for external certification.

**Key consulting decisions:**

*   **Strict Standard Alignment:** The agenda is explicitly structured to mirror the exact mandatory inputs (Clause 9.3.2) and mandatory outputs (Clause 9.3.3) required by ISO 27001, ensuring no compliance gaps exist in executive oversight.
*   **Closing the Traceability Loop:** Demonstrates the interconnected nature of the ISMS by taking the specific Minor Non-Conformity found in the Internal Audit (AUD-001) and forcing the CEO to formally sign off on the associated risk (RR-013) during the Management Review.
*   **German Labor Context:** Incorporates realistic stakeholder feedback, specifically noting positive engagement from the *Betriebsrat* (Works Council) regarding the compliant deployment of endpoint monitoring tools.

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
├── 📁 3 — Statement of Applicability         
│   └── MT-ISMS-SOA-001  SoA — 93 Controls  (Clause 6.1.3)
│
├── 📁 4 — Regulatory Compliance              
│   ├── NIS2 Incident Reporting Workflow    (NIS2 Art. 23)
│   └── DSGVO Records of Processing         (DSGVO Art. 30)
│
└── 📁 5 — Audit & Metrics                    <-- YOU ARE HERE
    ├── Internal Audit Checklist            (Clause 9.2)
    └── Management Review Agenda            (Clause 9.3)
```

---

## ⚖️ Regulatory Alignment

| Regulation | Relevance to This Folder |
| :--- | :--- |
| **ISO/IEC 27001:2022** | Directly fulfills the mandatory requirements of Clause 9.2 (Internal audit), Clause 9.3 (Management review), and Clause 10 (Continual improvement). |
| **EU NIS2 Directive** | Satisfies Article 20 obligations requiring the management body to approve cybersecurity risk-management measures and oversee their implementation. |
| **DSGVO / GDPR** | Aligns with Article 32(1)(d), which requires a process for regularly testing, assessing, and evaluating the effectiveness of technical and organisational measures (TOMs). |

### 📬 Contact

**Austin Bond**  
Junior GRC Consultant | ISO 27001 Provisional Implementer/Auditor, NIS2 Provisional Implementer (in progress)  
[🔗 Connect on LinkedIn](https://www.linkedin.com/in/austingrc)
