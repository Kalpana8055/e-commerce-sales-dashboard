🛒 Kalpana E-Commerce Sales Dashboard (Power BI)
<img width="1912" height="980" alt="image" src="https://github.com/user-attachments/assets/91b69e05-9e95-444e-99c4-0c73d55176e4" />

📊 Project Overview

The Kalpana E-Commerce Sales Dashboard is an interactive Power BI report designed to analyze key business metrics such as sales, profit, quantity, and customer behavior.
It helps stakeholders monitor performance trends, identify top-performing states and categories, and make data-driven decisions.

🎯 Objectives

To visualize sales and profit performance across different states, categories, and months.

To track payment modes, average order value (AOV), and top customers.

To provide actionable insights using an interactive and dynamic dashboard.

🧠 Key Insights

Total Sales Amount: ₹438K

Total Profit: ₹37K

Total Quantity Sold: 5615

Average Order Value (AOV): ₹121K

Top Performing Category: Clothing (63%)

Most Used Payment Mode: Cash on Delivery (44%)

Highest Sales State: Maharashtra

Top Profit Sub-Category: Printers

📈 Dashboard Features

KPIs: Total Amount, Profit, Quantity, and AOV cards at the top.

State-wise Performance: Bar chart showing sales contribution by states.

Category Insights: Donut chart for quantity share by category.

Monthly Trend: Clustered column chart showing profit trends over months.

Customer Insights: Sales amount by customer names.

Payment Analysis: Quantity distribution by payment mode.

Sub-Category Profit: Bar chart showing profit across sub-categories.

Quarterly Filter: Dynamic slicers for Q1–Q4 selection.

🧰 Tools & Technologies

Power BI Desktop

Data Cleaning & Modeling using Power Query

DAX Measures for KPI Calculations

Excel Dataset as Data Source

🧩 DAX Measures Used
Sum of Amount = SUM(Sales[Amount])
Sum of Profit = SUM(Sales[Profit])
Sum of Quantity = SUM(Sales[Quantity])
AOV = [Sum of Amount] / DISTINCTCOUNT(Sales[Order ID])

📷 Dashboard Preview

🚀 How to Use

Open Power BI Desktop.

Load the .pbix file from the repository.

Refresh data connection if needed.

Interact with filters and visuals to explore insights.

💡 Future Enhancements

Add sales forecasting using Power BI AI visuals.

Integrate real-time data refresh from SQL Server or Azure.

Include region-wise profit trend analysis.
