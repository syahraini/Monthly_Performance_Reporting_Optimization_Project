# Monthly Performance Reporting Optimization Project

## Process Automation • Operational Excellence • Data Governance • FigJam 

---

## Project Overview

This project delivers a structured, end-to-end optimization of the organization’s **monthly performance reporting process**, which was consistently failing to meet executive deadlines and exposed to high data integrity risk. The existing process relied on fragmented email-based submissions and inconsistent legacy templates, resulting in a **3–4 hour manual normalization bottleneck** for Finance and delayed leadership visibility beyond Day 5 of each month.

The objective was to **eliminate manual rework, enforce data quality at the source, and guarantee executive-ready reporting by the 2nd business day** through standardized intake, automation, and governance.

The analysis and design deliverables include:

* Validated As-Is process mapping highlighting systemic handoff failures.
* Root cause analysis of manual normalization and data inconsistency.
* Defined To-Be centralized reporting model with locked templates and automated validation.
* Functional requirements and technical feasibility assessment for immediate execution.

---

## Data Sources

**Datasets**: Monthly Sales and Operations Performance Reports
**Format**: Excel spreadsheets (email attachments, legacy templates)
**Description**: Department-level performance data manually prepared and submitted to Finance for consolidation.

---

## Data Cleaning & Transformation (As-Is State)

In the current state, Finance performed extensive manual intervention to normalize incoming data before consolidation.

Key activities included:

* Manual correction of inconsistent column structures and headers.
* Reformatting dates, currency, and percentage fields.
* Deconstructing pivot tables into raw tabular formats.
* Copy-pasting data into the master report, introducing error risk.

**Result:** 3–4 hours of recurring, non-value-added effort per reporting cycle.

---

## Analytical Framework

### KPI Definition

* Manual Normalization Time (Hours)
* Report Availability Date (Business Day)
* Data Error Exposure (Manual Touchpoints)
* Executive Visibility Lag

### Process Analysis

* Mapped cross-departmental data handoffs using FigJam.
* Identified failure points caused by email-based “push” submissions.
* Assessed data quality issues arising from uncontrolled templates.
* Defined success criteria using SMART objectives.

### Governance & Design Principles

* Single Source of Truth
* Data Quality at Point of Entry
* Automation over Manual Repair
* Role-Based Access and Accountability

---

## Scope Definition

| In-Scope                         | Out-of-Scope                     |
| -------------------------------- | -------------------------------- |
| Monthly Reporting Process Design | KPI definition changes           |
| Standardized Data Intake Model   | BI dashboard development         |
| Locked Reporting Templates       | ERP system replacement           |
| Automated Validation Logic       | Advanced analytics / forecasting |

---

## Key Insights & Findings

* **Fragmented Handoff Failure**
  Finding: Email-based submissions create version conflicts, missing files, and delayed consolidation.
  Implication: A centralized repository is required to replace inbox dependency.

* **Manual Normalization Bottleneck**
  Finding: Finance spends 3–4 hours repairing data before analysis can begin.
  Implication: Data structure must be enforced upstream through locked templates.

* **High Data Integrity Risk**
  Finding: Manual copy-pasting and formatting corrections significantly increase error exposure.
  Implication: System-enforced schemas and validation must replace human policing.

* **Delayed Executive Visibility**
  Finding: Leadership access depends on final distribution emails and password-protected files.
  Implication: Reports must be published directly to a secure, permission-based repository.

---

## Solution Design (To-Be State)

### A. Standardized Digital Repository (Single Source of Truth)

* Central SharePoint / Drive folder serving as the official monthly intake point.
* Role-based permissions:

  * Sales & Operations: Upload-only
  * Finance & Leadership: View/Edit
* Elimination of email-based submissions and private file storage.
* Repository-level version control to prevent legacy template usage.

### B. Locked Master Templates

* Excel templates with:

  * Column structure protection (no additions or deletions)
  * Data validation rules (dropdowns, format enforcement)
  * ISO-standard date, currency, and percentage formats
* Templates engineered for direct, automated ingestion into the master report.

### C. Shift from Manual Repair to Automated Validation

* Automated notification once all required files are uploaded.
* Finance runs a pre-built validation check (e.g., Power Query) to flag:

  * Missing fields
  * Out-of-range values
  * Schema violations
* Review time reduced from hours to minutes.

### D. Leadership Visibility & Distribution

* Final reports published directly to a Leadership Dashboard folder.
* Immediate access for CEO and executives without distribution emails.
* Security governed by corporate credentials, not file passwords.

---

## Business Impact & ROI

| Metric                    | Before     | After         | Improvement             |
| ------------------------- | ---------- | ------------- | ----------------------- |
| Manual Normalization Time | 3–4 hours  | **0 hours**   | **100% eliminated**     |
| Report Availability       | Post-Day 5 | **Day 2 EOD** | **≥3-day acceleration** |
| Data Error Risk           | High       | **Low**       | **~90% reduction**      |
| Executive Access          | Delayed    | **Real-time** | Immediate visibility    |

---

## Deliverables

* Project Charter
* As-Is Process Map (FigJam)
* To-Be Process Map (FigJam)
* Functional Requirements & Data Schema
* Locked Excel Reporting Templates
* Repository Setup & Access Guide
* Executive Summary

---

## Tools & Technologies

| Tool                   | Purpose                                                   |
| ---------------------- | --------------------------------------------------------- |
| **Excel**              | Template locking, data validation, Power Query validation |
| **FigJam**             | As-Is / To-Be process mapping                             |
| **SharePoint / Drive** | Centralized repository and access control                 |
| **Notion**             | Project documentation and requirements                    |
| **Canva**              | Executive presentation                                    |

---

## About the Analyst

Hi, I’m **Syahraini**, transitioning into Business Analysis from an accounting background. I specialize in diagnosing broken financial processes, enforcing data governance, and designing automation that eliminates rework and restores executive trust.

---

## Contact

* **LinkedIn**: [https://linkedin.com/in/nsyahraini](https://linkedin.com/in/nsyahraini)
* **Portfolio**: [https://bit.ly/syahrainiportfolio](https://bit.ly/syahrainiportfolio)
* **Email**: [syahraini.nur@outlook.com](mailto:syahraini.nur@outlook.com)

---
