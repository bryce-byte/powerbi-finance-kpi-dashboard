# powerbi-finance-kpi-dashboard
Basic Finance KPI Dashboard built in Power BI using SQL-style measures and time intelligence.
# Power BI Finance KPI Dashboard

An executive-style Finance KPI dashboard built in Power BI using SQL-style modeling and time-intelligence measures.

## 📊 Dashboard Overview
![Dashboard Overview](dashboard-overview.png)

## 🔑 Key Features
- Explicit KPI measures (Revenue, Cost, Profit, Profit Margin)
- Month-over-Month revenue comparison using prior-period logic
- Interactive month slicer with clean date modeling (no hierarchy artifacts)
- Revenue trend over time
- Profit breakdown by department

## 🧠 Modeling Approach
Power BI is used as the presentation layer. All business logic is defined using measures rather than relying on default aggregations.

Key techniques:
- SQL-style aggregation via DAX measures
- Prior-month comparisons using time intelligence
- Explicit separation of data modeling and visualization
- Clean layout optimized for executive review

## 📈 KPIs Included
- Total Revenue
- Total Cost
- Profit
- Profit Margin
- Revenue vs Prior Month (KPI comparison)

## 🛠 Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)

## 📁 Files
- `Finance_KPI_Dashboard.pbix` — main Power BI dashboard file

## 🚀 How to Use
1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Use the Month slicer to explore performance
