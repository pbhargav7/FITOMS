# 🏦 Trade Order Management System Enhancement – Fixed Income, Equities & Derivatives  
**Project Duration:** May 2024 – Present  
**Organization:** STP Investment Services, CA  
**Role:** Sr. Business Analyst  

---

## 📌 Project Overview

This project involved enhancing an in-house **Trade Order Management System (TOMS)** to support **Straight-Through Processing (STP)** across **Fixed Income, Derivatives (Options and Futures), and Equities**. The objective was to reduce manual workflows, automate trade lifecycle processes, and improve regulatory compliance, data quality, and operational efficiency.

The previous legacy system was fragmented, heavily manual, and lacked real-time compliance validation and integrated reporting. We designed and implemented a **modernized trade architecture**, inspired by **Bloomberg TOMS**, with integrated modules for trading, compliance, execution, and settlement.

---

## 💼 My Role – Sr. Business Analyst

As the **Sr. BA**, I was responsible for bridging the gap between the business and technical teams. I led the requirement gathering efforts and ensured that the technical implementation aligned with business goals. Here's what I contributed:

- **Gathered & analyzed requirements** from Portfolio Managers, Traders, and SMEs.
- Performed **GAP Analysis** to identify process improvement areas.
- Created **FRDs, BRDs**, and detailed **workflow diagrams** using MS Visio.
- Led **data mapping** exercises for financial instruments (ISIN, CUSIP, maturity, coupon rate).
- Wrote and executed **SQL queries** to validate data integrity.
- Integrated with **Bloomberg** for real-time market data.
- Facilitated **pre- and post-trade compliance checks** through a third-party API.
- Participated in **sprint ceremonies** (Planning, Daily Standups, Reviews, Retros).
- Reviewed **QA test cases**, supported **UAT**, and handled **defect triaging**.
- Created **RTM (Requirements Traceability Matrix)** for full lifecycle tracking.

---

## 🧩 System Architecture

The updated system consisted of the following layers:

### 📊 Front Office
- Portfolio Managers/Traders initiate trades via the **Trade Order UI**
- Real-time interaction with Market Data APIs (Bloomberg)

### 🛡️ Middle Office
- **Compliance Engine** integration for real-time pre-trade validation
- Risk checks (limit breaches, restricted securities)
- Trade validation and enrichment

### 🏢 Back Office
- Trade settlement and clearing (T+1, T+2)
- Reconciliation and booking via back-office systems
- Trade reporting and dashboard generation

---

## 🖥️ Tech Stack & Tools

| Component                 | Tool/Technology Used                     |
|--------------------------|------------------------------------------|
| Database                 | Oracle DB                                |
| Diagrams                 | MS Visio                                 |
| Reporting                | Excel, Dashboards                        |
| Testing & Defect Mgmt    | JIRA, Confluence                         |
| Market Data Integration  | Bloomberg API                            |
| Compliance Checks        | 3rd Party API (via REST integration)     |
| Querying & Validation    | SQL                                       |
| Project Methodology      | RUP (Rational Unified Process)           |

---

## 🔁 Trade Lifecycle (Simplified)

1. **Trade Initiation** – Order created by Portfolio Manager
2. **Pre-Trade Compliance** – Validated against compliance rules
3. **Enrichment & Validation** – Enriched with market data
4. **Execution** – Routed to brokers via FIX
5. **Settlement** – Back office initiates post-trade settlement
6. **Reporting** – Results delivered via dashboards and exports

---

## ✍️ Sample User Story

**Title**: Validate Trade Against Compliance Rules  
**As a** Portfolio Manager  
**I want** the system to run compliance checks before execution  
**So that** invalid trades are blocked and flagged for correction

**Acceptance Criteria:**
- Trade with restricted security is blocked
- Trade exceeding sector or asset limits is flagged
- Compliance status is shown before execution

---

## 📈 Outcome & Value Delivered

✅ Reduced trade processing time by automating STP  
✅ Improved data accuracy via strong validation & mapping  
✅ Reduced compliance breaches with real-time rules  
✅ Enabled audit-ready reporting & traceability  
✅ Strengthened cross-team collaboration and agile delivery

---

## 👨‍💻 Team Size & Reporting

- **Total Team Size**: 7  
  - 1 Business Analyst (myself)  
  - 2 Developers  
  - 1 Data Modeler  
  - 2 QA Engineers  
  - 1 Scrum Master  
- **Reporting to**: Project Manager & Product Owner

---
## 📎 Attachments

### 🗂 System Architecture Diagram  
![System Architecture Diagram](./SystemArchitecture.png)

### 🔄 Workflow Diagrams  
**Trade Lifecycle & Compliance Checks**  
![Workflow Diagram](./workflow-diagram.png)

### 📄 Sample FRD & Data Mapping Document  
(Available on request)

---

> This GitHub repository documents the structure, contribution, and flow of the STP Investment Services Trade Order Management System modernization project. Feel free to connect for a demo or further documentation.
