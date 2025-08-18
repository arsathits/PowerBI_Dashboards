# 🌿 Plant Co. Performance Dashboard

A **Power BI dashboard** designed to track and optimize the operational performance of Plant Co.  
It provides insights into **production, efficiency, downtime, and profitability**, helping stakeholders make data-driven decisions.

---

## 📊 Dashboard Overview
The dashboard consolidates multiple performance metrics into one interactive view:
- **KPI Cards** → Profit, Yield, Efficiency, Downtime, OEE (Overall Equipment Effectiveness)
- **Trend Analysis** → Production over time, downtime causes, efficiency trends
- **Comparisons** → Actual vs Target, Plant-level vs Department-level
- **Drilldowns** → Navigate from company-wide view to specific plant or product line

---

## ⚙️ Features

### 🔑 Key KPIs
- **Production Output** – Units produced vs target
- **Yield %** – Good units / Total units
- **Efficiency %** – Actual run time vs available time
- **Downtime (hrs)** – Lost hours due to breakdowns or planned stops
- **Profit Margin %** – Profit relative to sales
- **OEE (Overall Equipment Effectiveness)** – Combines availability, performance, and quality

### 📈 Visuals Used
- **Card Visuals** → For high-level KPIs
- **Line & Area Charts** → Production & downtime trends
- **Bar/Column Charts** → Plant-wise and department-wise comparisons
- **Gauge/Donut Charts** → Target achievement vs actual
- **Tables/Matrix** → Drill-down details

### 🗂 Data Modeling
- **Fact Tables** → Production, Downtime, Sales
- **Dimension Tables** → Date, Plant, Department, Product
- **Relationships** → Star schema with fact-to-dimension links
- **DAX Measures** → Calculated KPIs like Yield %, Efficiency %, OEE, Profit Margin

---

## 📌 Insights
From the dashboard:
- Identified **production shortfalls** in certain plants
- Highlighted **major downtime reasons** affecting efficiency
- Provided visibility into **profitability trends**
- Enabled **target vs actual performance tracking**

---