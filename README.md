# 📊 Customer Support Analytics Dashboard (Looker Studio + BigQuery)

## 🔹 Overview
This project is an end-to-end Business Intelligence dashboard built using **BigQuery and Looker Studio** to analyze customer support tickets data.

The dashboard is designed for:
- Executive leadership (high-level KPIs & trends)
- Operations teams (deep-dive into ticket distribution, backlog, and workload mix)

---

## 🔧 Tech Stack
- BigQuery (SQL, data storage, aggregation)
- Looker Studio (Dashboarding & Visualization)

---

## 📈 Dashboards

### 1️⃣ Executive Overview
![Executive Overview](screenshots/executive_overview.png)

**KPIs:**
- Total Tickets
- Open Tickets
- Resolved Tickets
- Resolution Rate

**Charts:**
- Tickets Over Time
- Backlog vs Resolved Over Time
- Tickets by Priority
- Tickets by Channel

---

### 2️⃣ Operational Analysis
![Operational Analysis](screenshots/operational_analysis.png)

**Charts:**
- Tickets by Type
- Tickets by Status
- Tickets by Product
- Ticket Status by Priority (Stacked)

---

## 🧠 Key Business Insights

- A large proportion of tickets are related to **refunds, technical issues, and cancellations**.
- **Pending Customer Response** forms a significant portion of the backlog.
- **Medium and Critical priority tickets** still have high open volumes → operational risk.
- Some products generate **disproportionately high support load**, indicating quality or UX issues.

---

## 🗄️ Data Preparation

Data was cleaned and modeled in **BigQuery using SQL**:
- Standardized status & priority fields
- Created flags for open, resolved, pending, backlog
- Aggregated data for dashboard consumption

---

## 🚀 What This Project Demonstrates

- Real-world BI dashboard design
- SQL-based data modeling in BigQuery
- KPI design & business storytelling
- Executive + Operational analytics views

---

## 📌 Use Case

This dashboard can be used by:
- Support Operations Managers
- Product Teams
- Business Leadership
To monitor support health, backlog risk, and product quality signals.
