🛍️ Myntra Retail Analytics — Power BI

</p>📌 Project Overview

This project uses Microsoft Power BI to analyze Myntra retail data through three report pages covering sales performance, product analysis, and web catalog insights.

The report includes KPI cards, charts, and interactive slicers to explore the available data.

📊 Report Pages

1. Sales Overview

- Total Net Revenue
- Total Orders
- Total Quantity
- Average Discount
- Orders by Category
- Orders by Brand, with a Top 10 filter
- Category tiles
- Slicers for City Tier, Category, Brand Name, and Order Date

2. Product Analysis

- Product Distribution by Category
- Revenue by Brand
- Revenue by Season
- Top Products
- Additional product and order analysis using available fields
- Category and Brand Name slicers

3. Customer & Web Insights

- Average Web Rating by Brand
- Total Reviews by Brand
- Products by Category
- Brand Name slicer

🧹 Power Query Transformations

The following transformations were performed in the "myntra_orders_master" query:

- Promoted Headers
- Changed Type
- Trimmed Text
- Cleaned Text
- Removed Duplicates
- Capitalized Each Word
- Additional text cleaning
- Added a conditional revenue-band column

The conditional column categorizes "Net_Revenue" into Low, Medium, and High bands using the configured thresholds.

🗂️ Datasets

Dataset| Description

"myntra_orders_master.csv"| Main order and sales data

"myntra_product_catalog.csv"| Product catalog

"myntra_web_catalog.csv"| Web catalog, ratings, and reviews

"myntra_summer_orders.csv"| Summer orders

"myntra_festive_orders.csv"| Festive orders

"myntra_winter_orders.csv"| Winter orders

Seasonal datasets were checked against the master orders. Overlapping orders should not be counted twice in sales calculations.

🛠️ Tools Used

- Microsoft Power BI Desktop
- Power Query
- CSV datasets
- GitHub for project documentation

🎛️ Interactivity

The report includes slicers and interactive visual filtering. Selecting a category or brand can update relevant charts and KPI cards, allowing the data to be explored from different perspectives.

🚀 How to Open the Report

1. Download the Power BI ".pbix" file from this repository.
2. Open it in Microsoft Power BI Desktop.
3. If prompted, check the dataset file paths.
4. Navigate through the three report pages and use the available slicers.
