# Steel Plant KPI Dashboard

## Project Overview

This project is an interactive Power BI dashboard developed for monitoring manufacturing KPIs.

The dashboard provides insights into:

- Production
- Sales
- Inventory
- Rejection
- Profitability
- Customer Performance


Description

# 1. The Landing Page
The Landing Page provides a high-level executive overview of the manufacturing business. It summarizes the most important KPIs and monthly business performance, enabling management to quickly assess overall plant health.

KPIs Included
Plant Capacity
Total Production
Total Inventory
Rejected Tons
Total Sales
Yield %
YoY Growth
YoY %
Visualizations
Monthly Sales Trend
Monthly Profit Trend
Customer & Category Filters
Navigation Buttons to detailed pages

## Business Value:
This page acts as the executive summary of the dashboard, allowing leadership to monitor production efficiency, sales performance, inventory levels, and profitability in one place.


# 🏭 2. Plant Performance Dashboard

Description

The Plant Performance page provides detailed operational insights into production efficiency across different manufacturing plants. Users can analyze production trends, yield performance, product mix, and plant-wise output.

KPIs & Visuals
Monthly Production Trend
Monthly Yield %
Product Mix Distribution
Plant-wise Production Comparison
Plant Performance Funnel
Shift Filter
Plant Filter
Defect Filter


## Business Value
This dashboard helps production managers identify productivity trends, compare plant performance, evaluate product mix, and monitor manufacturing efficiency over time.


# 3. Product Rejection Dashboard
Description
The Product Rejection dashboard focuses on quality analysis by tracking rejected material across customers, products, and manufacturing plants.

KPIs
Total Rejected Tons
Rejection %
Rejection YoY
Customer-wise Rejection
Monthly Rejection Trend
Monthly Rejection Cost
Visualizations
Customer-wise Rejection Bar Chart
Monthly Rejection Trend
Monthly Rejection Cost Trend
Product-wise Rejection Distribution
Plant-wise Rejection Contribution

## Business Value:
This page helps quality engineers identify rejection hotspots, monitor quality trends, evaluate rejection costs, and support root cause analysis for continuous improvement.


# 📦 4. Inventory Dashboard

Description
The Inventory dashboard provides visibility into stock levels, inventory value, inventory ageing, and customer-wise inventory distribution.

KPIs
Total Inventory
Inventory Cost
Cost per Ton
Inventory YoY
Visualizations
Monthly Inventory Trend
Customer-wise Inventory
Plant-wise Inventory Summary
Inventory Ageing Analysis
Category & Grade Filters


## Business Value:
This dashboard enables inventory managers to optimize stock levels, monitor inventory value, identify ageing inventory, and improve warehouse planning.


# 🛠 Data Model
The dashboard is built using a combination of Star Schema and Snowflake Schema.

Fact Tables
Production
Sales
Inventory
Rejection
Dimension Tables
Date
Customer
Plant
Product
Category
Grade
Shift


# 📈 KPIs Calculated
Total Production
Total Sales
Profit
Profit Margin %
Yield %
Inventory
Inventory Cost
Cost per Ton
Rejected Tons
Rejection %
Year-over-Year (YoY)
YoY %


# 🧮 Power BI Skills Demonstrated
Data Modeling (Star & Snowflake Schema)
DAX Measures
Time Intelligence
Power Query (ETL)
Interactive Slicers
Drill-through Navigation
KPI Cards
Bookmarks & Buttons
Custom Dashboard Design
Dynamic Filtering
Performance Optimization


# 📌 Business Problem Solved

The dashboard consolidates production, quality, inventory, and sales data into a single reporting solution, allowing management to:

Monitor production efficiency.
Track inventory and carrying costs.
Analyze rejection trends and quality performance.
Evaluate sales and profitability.
Compare plant-wise performance.
Support data-driven operational decision-making.

**Note:** The original Power BI (.pbix) file cannot be shared because it uses organizational data sources and company credentials. This repository showcases the project through dashboard screenshots and documentation.
