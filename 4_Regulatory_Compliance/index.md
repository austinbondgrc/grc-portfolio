---
title: Regulatory Compliance (In progress)
parent: 🛡️ Governance, Risk & Compliance (GRC) Portfolio
nav_order: 4
has_children: true
---

# 📁 4 — Regulatory Compliance

**MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
**Prepared by:** Austin Bond, Junior GRC Consultant

## 📌 Folder Overview

This folder demonstrates the critical intersection between cybersecurity engineering and European law. While ISO 27001 provides a voluntary framework for security best practices, the EU NIS2 Directive and DSGVO (GDPR) impose strict, mandatory legal obligations on MunichTech GmbH.

The documents in this folder prove the ability to translate abstract legal statutes into operational, actionable workflows for the IT and DevOps teams, while protecting executive management from personal liability and the company from regulatory fines by the BSI and BayLDA.

---

## 📄 Documents in This Folder

### 1. NIS2 Incident Reporting Workflow

**File:** `MT-NIS2-IRP-001_v1.0.pdf`

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | EU NIS2 Directive (Art. 23) / BSIG § 32 & 35 |
| **Format** | PDF Document (Standard Operating Procedure) |

**What this document does:**  
It establishes the mandatory reporting workflow for the MunichTech incident response team. It defines exactly what constitutes a "Significant Incident" and outlines the strict timeline for notifying the German Federal Office for Information Security (BSI).

**Key consulting decisions:**

*   **Defining the Trigger:** Clearly defines the legal moment of "Awareness" to prevent operational delays during a crisis.
*   **The 24-72-30 Timeline:** Operationalizes the phased reporting requirement: a 24-hour early warning, a 72-hour detailed notification, and a 1-month final forensic report.
*   **The "Double Notification" Rule:** Explicitly maps the parallel reporting obligations, acknowledging that a single database breach requires simultaneous notification to both the BSI (under NIS2) and the BayLDA (under DSGVO Art. 33).

### 2. DSGVO Records of Processing Activities (RoPA)

**File:** `MT-DSGVO-RoPA-001_v1.0.xlsx`

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | DSGVO Article 30 / GDPR Article 30 |
| **Format** | Excel Spreadsheet |

**What this document does:**  
The *Verarbeitungsverzeichnis (VVT)* is the foundational legal ledger for data privacy. It documents exactly who processes data, the lawful basis for doing so, the sub-processors involved, and the required data retention periods.

**Key consulting decisions:**

*   **Controller vs. Processor Delineation:** The RoPA is cleanly split to demonstrate understanding of MunichTech's dual role: acting as a Data Controller for internal HR/Sales data, and strictly as a Data Processor (*Auftragsverarbeiter*) for the financial data of enterprise banking clients.
*   **German-Market Realities:** Accurately applies Article 9 (Special Categories of Data) to German payroll realities, specifically noting the processing of religious affiliation for *Kirchensteuer* (Church Tax).
*   **Transatlantic Data Flows:** Explicitly addresses the post-Schrems II landscape by identifying US-based sub-processors (Salesforce, Splunk) and documenting the use of EU Standard Contractual Clauses (SCCs) and the Data Privacy Framework.

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
├── 📁 4 — Regulatory Compliance              <-- YOU ARE HERE
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
| **EU NIS2 Directive** | Fulfills Article 23 obligations for reporting significant cyber threats and incidents to national competent authorities. |
| **BSIG (BSI-Gesetz)** | Aligns the European NIS2 directives directly into German federal law requirements for reporting via the BSI portal. |
| **DSGVO / GDPR** | Satisfies the mandatory requirement of Article 30 to maintain a written record of processing activities, which is the primary document requested during a BayLDA privacy audit. |
| **ISO/IEC 27001:2022** | Satisfies Annex A Control 5.31 (Legal, statutory, regulatory and contractual requirements) and 5.5 (Contact with authorities). |

---

## 📥 Download Documents
[📁 Browse folder on GitHub](https://github.com/austinbondgrc/grc-portfolio/tree/main/4_Regulatory_Compliance){: .btn }  [⬇ Download full portfolio (ZIP)](https://github.com/austinbondgrc/grc-portfolio/archive/refs/heads/main.zip){: .btn .btn-primary }

---

### 📬 Contact

**Austin Bond**  
Junior GRC Consultant | ISO 27001 Provisional Implementer/Auditor, NIS2 Provisional Implementer (in progress)  
[🔗 Connect on LinkedIn](https://www.linkedin.com/in/austingrc)
```
