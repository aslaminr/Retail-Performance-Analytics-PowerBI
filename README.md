# 📊 Retail Performance Intelligence – Power BI (End-to-End Analytics Project)

**Dashboard URL:** [Click Here](https://shorturl.at/nk2dO)  
**Screenshots:** [Click Here](https://shorturl.at/crv3P)  
**Tool:** Microsoft Power BI  
**Dataset:** AdventureWorks 2019 OLTP  
**Focus Areas:** Sales Performance | Customer Retention | Inventory Optimization  

---

## Executive Summary

This project demonstrates an end-to-end retail analytics solution built using the AdventureWorks 2019 OLTP database. The report integrates Sales, Customer, and Inventory analytics into a single decision-support framework designed to mirror real-world business scenarios.

The objective was not to build decorative dashboards, but to answer operational and strategic questions across revenue growth, retention effectiveness, and working capital efficiency.

---

## Business Problem Statements

### 1️⃣ Sales
- Why has revenue growth fluctuated across territories and categories?
- Which segments are driving sustainable performance?

### 2️⃣ Customer
- Are acquired customers returning?
- How much revenue depends on retention vs acquisition?
- Which customer segments drive long-term value?

### 3️⃣ Inventory
- Where is capital locked in slow-moving stock?
- Which products are inefficient based on turnover and days of inventory?
- Are we exposed to stock risk or overstock risk?

---

## Dashboard Architecture

The report consists of three structured analytical layers:

### 🔹 Sales Performance Dashboard
- Revenue trend analysis (Quarter/ Year logic)
- Category and territory contribution
- Growth diagnostics
- Performance segmentation

**Decision Impact:** Identifies revenue drivers and underperforming segments.

---

### 🔹 Customer Behavior & Retention Dashboard
- Quarter-based cohort retention matrix
- Revenue mix: New vs Returning customers
- Customer Lifetime Sales
- Purchase frequency distribution
- Tenure-based behavioral segmentation

**Decision Impact:** Evaluates acquisition quality and retention strength, highlighting dependency on repeat revenue.

---

### 🔹 Inventory Efficiency Dashboard
- Inventory Turnover by category
- Days of Inventory (stock risk evaluation)
- Top 10 slow-moving products
- Zero-sale products with existing stock
- Inventory value concentration

**Decision Impact:** Identifies working capital inefficiencies and operational risk exposure.

---

## Data Modeling & Technical Approach

- Designed using **Star Schema modeling principles**
- Fact tables separated from dimension tables
- Dedicated Date table created and marked
- Power Query used for transformation and refresh timestamp logic
- Cohort retention built using offset-based DAX calculations
- Measures optimized to respect filter context and avoid logic distortion
- No redundant visuals; each chart supports a distinct decision

---

## 📊 Core Metrics Implemented

- Total Revenue
- Quarterly & Yearly Growth %
- Retention %
- Customer Lifetime Sales
- Average Purchase Frequency
- Inventory Turnover
- Days of Inventory
- Inventory Value

All measures built using DAX with context-aware logic.

---

## 🔍 Analytical Highlights

- Identified revenue concentration across specific categories.
- Retention drops significantly after acquisition period, indicating churn risk.
- Returning customers contribute a substantial portion of revenue stability.
- Multiple SKUs show high Days of Inventory, signaling capital lock.
- Zero-sale stock highlights operational inefficiencies.

---

## 🛠 Skills Demonstrated

- Power BI Data Modeling (Star Schema) [Click Here](https://shorturl.at/oGmvJ)
- Advanced DAX (Cohort logic, context transition, segmentation)
- Business KPI Design
- Inventory Efficiency Analysis
- Retention & Revenue Mix Modeling
- Top N Operational Diagnostics
- Clean, executive-focused dashboard design

---

## Why This Project Matters

This project reflects real-world analyst responsibilities:

- Translating business questions into analytical models
- Designing metrics aligned with operational decisions
- Building retention logic using DAX
- Identifying capital inefficiency in inventory systems
- Delivering clean, decision-driven dashboards

This simulates cross-functional business intelligence reporting across sales, customer strategy, and operations.

---

## 👤 Author

**Aslam PP**  

Power BI | MS SQL | Data Analytics  



