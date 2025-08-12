AdventureWorks Sales Dashboard
📌 Summary
Power BI dashboard analyzing reseller sales from the AdventureWorks dataset.
Includes key sales KPIs, interactive visuals, and Role-Level Security (RLS) for restricted data access.

🗂 Data Model
Fact Table:

FactResellerSales – sales transactions

Dimension Tables:

DimEmployee – employee & manager details

DimProduct – products & categories

DimReseller – reseller details

DimSalesTerritory – regions & countries

OrderDate, DueDate, ShipDate – date dimensions

Structure: Star schema with one-to-many relationships.

📊 Dashboards & Metrics
Home Dashboard
Sales by employee: Lifetime, Current Year, Previous Year, YoY%

Filters: Order Year, Sales Group, Sales Country

Drill-through to Employee Dashboard

Employee Dashboard
Profile: Name, Title, Hire Date, Region, Lifetime Sales

Year-over-Year sales bar chart

Yearly summary table (Total, PY, YoY%, YTD)

Top products & regions

Monthly cumulative sales trend

Key Measures:
Total Sales, Total Sales PY, Total Sales YTD, Total Sales PY YTD, Total Sales QTD, Total Sales YoY%, Total Lifetime Sales

🔒 Role-Level Security (RLS)
Role	Access
VP	All data
Sales Manager	Themselves + team
Sales Rep	Own data only

Filters applied on DimEmployee using EmployeeKey and Supervisor EmailAddress.

🚀 Features
📈 Sales KPIs with YoY and trend analysis

🎯 Product and region performance insights

🔍 Drill-through navigation for detailed views

🔒 Role-based security for data privacy

⚡ Star schema model for performance optimization

