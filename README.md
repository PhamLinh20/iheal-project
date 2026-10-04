# 🌿 iHeal E-Commerce System — Sales Portal

> A multi-role wellness e-commerce platform developed as a Capstone Project, specializing in premium dietary supplements.

---

## 📌 Project Overview
- **System URL:** [https://ihealwehear.site/](https://ihealwehear.site/)
- **Sales Portal Workspace:** `https://sales.ihealwehear.site`
- **Context & Objective:** Developed to migrate an established supplement store away from high-fee, fragmented third-party marketplaces (Shopee, Facebook). iHeal centralizes order processing, builds a direct-to-consumer (D2C) wellness community, and provides dedicated internal workspaces for **Customers, Sales Agents, and Brand Operators**.

---

## 🛠️ Tech Stack & Tooling
- **Core Platform:** WordPress 6.9.4 & WooCommerce 10.7.0 (High-Performance Order Storage - HPOS enabled)
- **Frontend & UI Theme:** Custom `ihear_sales_module` (HTML5, CSS3, JavaScript, jQuery 3.7.1)
- **Database & Hosting:** MySQL (Shared multi-subdomain schema), Hostinger, Cloudflare SSL/TLS
- **Testing & Project Management:** Jira Software (Project CP1G), Google Chrome Desktop, Excel

---

## 💼 My Key Roles & Contributions

### 1. Business Analysis & System Specification
- **Requirement Engineering:** Authored the comprehensive **Sales Portal Functional Specification** document covering 13 functional modules (Authentication, Dashboard Analytics, Order Fulfillment, Returns & Refunds, Customer Profiles, Payments, Exporting, Real-time Chat, Protocol Journeys, and Localization).
- **Process & Model Design:** Formulated system boundaries (In-Scope/Out-of-Scope), Use Case Diagrams, and detailed Use Case specifications (SA-001 → SA-012).
- **UI/UX Prototyping:** Designed high-fidelity, interactive prototypes and responsive wireframes on Figma adhering to the platform's wellness visual identity.
  - 🔗 [Figma Prototype & Design Workspace](https://www.figma.com/design/qSLfmgE1ncx1NiXbs8BxWa/Sales-portal?node-id=0-1&t=nZMEdQWA5Mzheqx8-1)

### 2. Software Quality Assurance & Defect Management
- **Test Planning:** Developed the formal **System Test Plan & Report** outlining risk-based manual functional testing, suspension/exit criteria, and test design techniques (Equivalence Partitioning, Boundary Value Analysis, State Transition Testing).
- **Test Case Design & Execution:** Authored and executed **52 comprehensive test cases** across 3 mission-critical operational modules:
  - `LOGIN_TC` (12 Test Cases): Positive/Negative login authentication, RBAC authorization guards, 30-day session persistence, whitespace trimming, and multilingual switching.
  - `ORDER_TC` (23 Test Cases): Order lookup, multi-condition status filtering, order lifecycle transitions (Processing → Shipped → Completed), internal note logging, and 1-to-1 active return request constraints.
  - `DASHBOARD_TC` (17 Test Cases): Real-time KPI formulas (Total Orders, Total Sales, 30% Profit margin), dynamic AJAX time-filter switches (fixing chart-freezing bug CP1G-72), keyword exclusion logic, and global header navigation.
- **Defect Tracking on Jira:** Identified, logged, and tracked **7 functional defects** in Jira Project CP1G (including `CP1G-72`, `CP1G-73`, `CP1G-134`, `CP1G-135`, `CP1G-136`, `CP1G-265`, `CP1G-266`). Verified bug fixes across regression cycles, achieving a **100% Resolution Rate (0 Open Defects)**.

---

## 📊 Testing Metrics Summary

| Testing Module | Authored TCs | Executed | Passed | Failed | Final Pass Rate |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **Module 1: Authentication & RBAC** | 12 | 12 | 12 | 0 | 100% |
| **Module 2: Order Management & Refunds** | 23 | 23 | 23 | 0 | 100% |
| **Module 3: Dashboard KPIs & Analytics** | 17 | 17 | 17 | 0 | 100% |
| **Total** | **52** | **52** | **52** | **0** | **100%** |

- **Execution Rate:** 100% (52/52)
- **Defect Resolution:** 7 / 7 resolved (100% Done on Jira)
- **Quality Gate:** Met all predefined Exit Criteria (Zero Blocker/Critical defects remaining).

---

## 📂 Deliverables in this Repository
- 📄 `iHeal_SalesPortal_Functional_Specification.docx` — Complete business & functional requirements specification with embedded UI screens.
- 📋 `iHeal_SalesPortal_TestPlan_and_Report.docx` — Formal System Test Plan, exit criteria assessment, and Jira bug resolution report.
- 📊 `Test Case.xlsx` — Detailed 5-column test case repository structured across 3 dedicated sheets (`LOGIN_TC`, `ORDER_TC`, `DASHBOARD_TC`).
