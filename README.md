📊 Business Insights 360 – AtliQ Hardware (Power BI Case Study)
🧠 Project Overview
AtliQ Hardware, a global manufacturer of computer accessories, had been making decisions based on intuition and fragmented Excel reports. After an unexpected market loss in the U.S., the company committed to building a centralized analytics function. This project aimed to deliver a unified, interactive Power BI dashboard for their C-suite across Finance, Sales, Marketing, and Supply Chain.

This case study was built during my data analytics bootcamp using real-world datasets and simulated stakeholder needs. I managed the entire lifecycle from requirement understanding and data modeling to DAX development and dashboard storytelling.

🎯 Objective
To enable smarter, faster decisions by creating a single source of truth across departments and answering questions like:

Why are certain regions underperforming despite high marketing spends?

Which products are most profitable year-to-date?

How accurate are sales forecasts, and how do they affect supply chain planning?

🔍 Data Sources
Databases:

gdb041 (Operational Data Warehouse)

gdb056 (Manufacturing and Cost Data Warehouse)

Key Tables:

dim_customer, dim_market, dim_product – containing customer types, geographic zones (APAC, EU, LATAM), and SKUs

fact_sales_monthly, fact_forecast_monthly – YTD and forecasted sales by customer, product, and channel

manufacturing_cost, freight_cost, gross_price – production and logistics costs

pre_invoice_deductions, post_invoice_deductions – discounts and rebate structure

Regions Covered:

27 global markets, categorized by subzones and 4 regions: APAC, EU, LATAM, NAN

Sales Channels:

Direct

Retailers

Distributors

Platforms:

Brick & Mortar

E-commerce

Product Categories:

P&A: Notebooks, Desktops, Accessories

N&S: Networking Devices, Storage Equipment

🛠️ Tech Stack
Power BI Desktop + Service

SQL (Joins, Aggregations, CTEs)

DAX Language

DAX Studio for optimization

M-Language for custom date table

Excel for EDA & data cleanup

📌 Key Features
Drill-through navigation between views: Finance, Sales, Marketing, Supply Chain, and Executive

KPI cards with dynamic indicators (Net Sales, Gross Margin %, Forecast Accuracy, ROI)

Interactive filters: Region, Channel, Product Category, Fiscal Year

Row-level security and Power BI App publishing

Dynamic titles, conditional formatting, and page navigation using bookmarks and buttons

🧱 Data Modeling
Snowflake schema structure for clean, optimized relationships

Custom date table generated via M Language

Star schema logic applied using surrogate keys and bridge tables

Validated relationships between 20+ tables with optimized filter flow for performance

🧮 Highlighted DAX Measures
Net Invoice Sales = Gross Price – Deductions

Gross Margin % = (Net Sales – COGS) / Net Sales

Forecast Accuracy % = 1 - DIVIDE(ABS(Forecast - Actual), Forecast)

Year-to-Date and Year-to-Go aggregations for Finance View

📹 Coming Soon: Full Video Walkthrough
This project will also feature a 10-minute video presentation, where I explain business insights domain-by-domain, showcase live dashboard filters, and simulate stakeholder conversations with Ghibli-style animations.

🌐 Live Dashboard
: https://app.powerbi.com/view?r=eyJrIjoiMzJjZjI5YTMtNmYzMS00ZTM5LWI4YjQtZmRhYWUyYjdlMjAxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9 


