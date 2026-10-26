---
title: Regulatory Compliance
description: "NIS2 incident reporting under § 32 BSIG, the NIS-2 registration record under §§ 33/34 BSIG, and DSGVO Article 30 records of processing."
nav_title: Regulatory
nav_order: 4
---

**MunichTech GmbH | ISO 27001:2022 ISMS Portfolio**  
**Prepared by:** Austin Bond, Junior GRC Professional

## Folder Overview

This folder demonstrates the critical intersection between cybersecurity engineering and European law. While ISO 27001 provides a voluntary framework for security best practices, the EU NIS2 Directive and DSGVO (GDPR) impose strict, mandatory legal obligations on MunichTech GmbH.

The documents in this folder prove the ability to translate abstract legal statutes into operational, actionable workflows for the IT and DevOps teams, while protecting executive management from personal liability and the company from regulatory fines by the BSI and BayLDA.

---

## Documents in This Folder

### 1. NIS2 Incident Reporting Workflow

**File:** [`MT-NIS2-IRP-001_v1.4_nis2-incident-reporting-workflow.pdf`](MT-NIS2-IRP-001_v1.4_nis2-incident-reporting-workflow.pdf)

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | NIS2 Art. 23 / § 32 BSIG |
| **Format** | PDF Document (Standard Operating Procedure) |
| **Version** | 1.4 (consistency release) |
| **Effective** | 26 October 2026 |

**What this document does:**  
It establishes the mandatory reporting workflow for the MunichTech incident response team. It defines exactly what constitutes a "Significant Incident" and outlines the strict timeline for notifying the German Federal Office for Information Security (BSI).

**Key consulting decisions:**

*   **Defining the Trigger:** Clearly defines the legal moment of "Awareness" to prevent operational delays during a crisis.
*   **The 24-72-30 Timeline:** Operationalizes the phased reporting requirement: a 24-hour early warning, a 72-hour detailed notification, and a 1-month final forensic report.
*   **The "Double Notification" Rule:** Explicitly maps the parallel reporting obligations, acknowledging that a single database breach requires simultaneous notification to both the BSI (under NIS2) and the BayLDA (under DSGVO Art. 33).
*   **DORA flow-down:** The notification-recipients table also records the contractual duty to inform enterprise banking clients under DORA (Reg. (EU) 2022/2554), which has applied since 17 January 2025 in place of BAIT. An incident reportable to the BSI is normally notifiable to affected clients as well, so the workflow tracks both routes rather than treating regulatory notification as the end of the process.

### 2. NIS-2 Betroffenheitsprüfung and BSI Registration Record

**File:** [`MT-NIS2-REG-001_v1.1_nis2-registration-record.pdf`](MT-NIS2-REG-001_v1.1_nis2-registration-record.pdf)

| Field | Detail |
| :--- | :--- |
| **Framework Reference** | § 28(2) BSIG (Anlage 1, Nr. 6.1.4) / §§ 33, 34 BSIG (NIS2 Art. 27) |
| **Format** | PDF Document (Evidence Record) |
| **Version** | 1.1 (entity-type and § 34 correction) |

**What this document does:**  
Records how MunichTech GmbH reached the conclusion that it is a *wichtige Einrichtung* — the sector test against Anlage 1, the establishment test, and the size arithmetic — and then records the registration it submitted to the BSI under § 33 BSIG and the extended submission under § 34 BSIG, field by field.

**Key consulting decisions:**

*   **Written, not assumed:** The BSIG attaches obligations automatically once an entity is in scope; it does not wait for the BSI to certify anything. A dated, approved self-assessment is the only artefact that can still be defended two years later.
*   **The classification corrected in public:** The record withdraws the earlier Annex II position outright, explains why it was wrong — Annex II covers consumer digital services (marketplaces, search engines, social networks), none of which MunichTech provides — and why Anlage 1, Sektor 6 is the correct home.
*   **Entity type corrected, not just the annex:** Within Sektor 6 the record originally cited an Einrichtungsart that the statute does not contain ("IKT-Dienstleistungsmanagement (B2B)"). Version 1.1 replaces it with Anlage 1 Nr. 6.1.4 (Anbieter von Cloud-Computing-Diensten), justifies that choice against the § 2 Nr. 4 BSIG definition, and records the separate rejection of the managed ICT service manager (Nr. 6.1.10) and managed security service provider (Nr. 6.1.11) entity types.
*   **Two registration duties, not one:** The record treats § 33 BSIG and § 34 BSIG as cumulative rather than alternative, tracks the two different change clocks (§ 33(5) — two weeks; § 34(2) — three months), and records § 30(3) BSIG, under which the NIS2 Art. 21(5) implementing act prevails over the baseline measures once it applies.
*   **No simulated BSI letter:** Registration is evidenced through internal evidence IDs rather than a reproduced BSI confirmation that does not exist. Section 10 of the record states exactly what it does and does not prove.

### 3. DSGVO Records of Processing Activities (RoPA)

**File:** [`MT-DSGVO-RoPA-001_v1.0_records-of-processing-activities.xlsx`](MT-DSGVO-RoPA-001_v1.0_records-of-processing-activities.xlsx)

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

## How This Folder Fits the Wider ISMS Portfolio

```text
ISO 27001:2022 ISMS Portfolio — MunichTech GmbH
│
├── 1 — Governance & Scope
│   ├── MT-ISMS-SCO-001  Scope & Context     (Clause 4)
│   └── MT-ISMS-POL-001  InfoSec Policy      (Clause 5)
│
├── 2 — Risk Management
│   ├── MT-ISMS-IAR-001  Asset Register      (Annex A 5.9)
│   ├── MT-ISMS-RAM-001  Risk Methodology    (Clause 6.1.2)
│   └── MT-ISMS-RR-001   Risk Register       (Clause 6.1.3)
│
├── 3 — Statement of Applicability
│   └── MT-ISMS-SOA-001  SoA — 93 Controls   (Clause 6.1.3)
│
├── 4 — Regulatory Compliance                ← YOU ARE HERE
│   ├── NIS2 Incident Reporting Workflow     (§ 32 BSIG)
│   ├── NIS-2 Registration Record            (§§ 33/34 BSIG)
│   └── DSGVO Records of Processing          (DSGVO Art. 30)
│
└── 5 — Audit & Metrics
    ├── Internal Audit Checklist             (Clause 9.2)
    ├── Management Review Agenda             (Clause 9.3)
    └── CAP Closure Memo                     (Clause 10.2)
```

---

## Regulatory Alignment

| Regulation | Relevance to This Folder |
| :--- | :--- |
| **EU NIS2 Directive** | Fulfills Article 23 obligations for reporting significant cyber threats and incidents to national competent authorities. |
| **BSIG (BSI-Gesetz)** | German implementation of NIS2 as amended by the NIS-2-Umsetzungsgesetz (BGBl. 2025 I Nr. 301). Supplies the reporting duty (§ 32), the registration duty (§ 33) together with the extended data set for the entity types in § 60(1) sentence 1 (§ 34), the management-accountability duty (§ 38), and the precedence of the Art. 21(5) implementing act over the baseline risk-management measures (§ 30(3)). |
| **DORA (Reg. (EU) 2022/2554)** | Client flow-down basis for notifying enterprise banking clients of an incident. Has applied since 17 January 2025 in place of BAIT, and is cited alongside § 32 BSIG and DSGVO Art. 33 in the notification-recipients table. |
| **DSGVO / GDPR** | Satisfies the mandatory requirement of Article 30 to maintain a written record of processing activities, which is the primary document requested during a BayLDA privacy audit. |
| **ISO/IEC 27001:2022** | Satisfies Annex A Control 5.31 (Legal, statutory, regulatory and contractual requirements) and 5.5 (Contact with authorities). |

---

## Download Documents

[Incident Reporting Workflow v1.4 — PDF](MT-NIS2-IRP-001_v1.4_nis2-incident-reporting-workflow.pdf){: .btn }
[Incident Reporting Workflow v1.4 — Word](MT-NIS2-IRP-001_v1.4_nis2-incident-reporting-workflow.docx){: .btn }
[NIS-2 Registration Record — PDF](MT-NIS2-REG-001_v1.1_nis2-registration-record.pdf){: .btn }
[NIS-2 Registration Record — Word](MT-NIS2-REG-001_v1.1_nis2-registration-record.docx){: .btn }
[DSGVO RoPA — Excel](MT-DSGVO-RoPA-001_v1.0_records-of-processing-activities.xlsx){: .btn }
[Incident Reporting Workflow v1.3 — Archive (PDF)](MT-NIS2-IRP-001_v1.3_nis2-incident-reporting-workflow.pdf){: .btn }
[Download the full portfolio (ZIP)]({{ '/Austin-Bond-GRC-Portfolio.zip' | relative_url }}){: .btn .btn-primary }

---

## Contact

**Austin Bond**  
Junior GRC Professional | PECB ISO/IEC 27001 Provisional Implementer · PECB ISO/IEC 27001 Provisional Auditor *(In Progress)* · PECB NIS2 Provisional Implementer · Associate of ISC2 CISSP *(In Progress)* [LinkedIn](https://www.linkedin.com/in/austinbondgrc)
