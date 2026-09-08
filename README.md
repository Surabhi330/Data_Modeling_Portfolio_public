# Data_Modeling_Portfolio_public
Creating a Sales dashboard 2026 report using Power Bi, mainly focused on Data Modeling layer

# Sales Dashboard 2026 — Power BI Report

## Overview
This Power BI dashboard provides a consolidated view of sales performance, customer activity, regional order distribution, product category performance, and marketing campaign budgets for the reporting period (Apr 2025 – Oct 2026).

## Key Metrics (KPI Cards)
| Metric | Value | Description |
|---|---|---|
| Base Total Customers | 60 | Total number of customers in the customer base |
| Total Orders | 80 | Total number of orders placed |
| Total Sales | 527K | Total sales revenue generated |
| Total Active Customers | 47 | Customers with recent/active purchase activity (~78% of base) |

## Visuals Included

### 1. Total Sales by Order Date (Line Chart)
Tracks daily/periodic total sales trends from April 2025 to October 2026. Highlights peak sales days and overall seasonality/volatility in revenue.

### 2. Total Orders by Region (Bar Chart)
Breaks down order volume by region: Europe, Middle East, Asia Pacific, Latin America, and North America — helping identify top-performing markets.

### 3. Total Sales by Category (Pie Chart)
Shows the percentage contribution of each product category (Electronics, Apparel, Home, Sports, Beauty, Industrial) to total sales.

### 4. Sum of Budget by Campaign Name (Bar Chart)
Compares marketing budget allocation across campaigns (e.g., Black Friday, Summer Sale, Spring Launch, Back to School, New Year Clearance), useful for evaluating spend distribution.

## Data Sources
- Sales/Orders data (order date, order value, region)
- Customer data (customer count, activity status)
- Product data (category classification)
- Marketing/Campaign data (campaign name, budget)

## How to Use This Report
1. Open the `.pbix` file in Power BI Desktop.
2. Use slicers/filters (if available) to drill down by date, region, or category.
3. Hover over visuals for tooltips with exact values.
4. Refresh data via **Home > Refresh** to pull the latest figures (ensure data source connection is active).

## Tools Used
- **Power BI Desktop** — report design and visualization
- **Power Query** — data transformation (if applicable)
- **DAX** — calculated measures for KPIs

## Author / Maintainer
Surabhi Gawade
sbgawade555@gmail.com

