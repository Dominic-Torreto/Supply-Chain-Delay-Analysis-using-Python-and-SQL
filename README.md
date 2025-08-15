# Supply Chain Delay Analysis — DataCo Case Study
# Overview
This project analyzes DataCo Supply Chain data to uncover operational inefficiencies, focusing on shipment delays, inventory turnover, and seasonal delivery trends. By combining SQL, Python, and Power BI, we deliver both deep analytical insights and dynamic visual dashboards for data-driven decision-making.

The analysis identifies the root causes of delayed deliveries, highlights inefficiencies in inventory management, and provides actionable recommendations to improve on-time shipment rates and operational performance.

#  Key Objectives
Detect patterns and causes behind shipment delays.

Analyze inventory turnover rates to highlight overstock or understock issues.

Explore seasonal trends affecting delivery performance.

Develop an interactive Power BI dashboard for real-time tracking of KPIs.

Enable data-driven improvements in supply chain processes.

# Methodology
1. Data Collection & Preprocessing
Source: DataCo Supply Chain dataset (Kaggle).

Tools: SQL for querying and cleaning; Python (pandas, numpy) for preprocessing.

Steps:

Handling missing and inconsistent data.

Normalizing date formats for shipment and order timelines.

Merging relevant tables for shipment, inventory, and sales.

2. Exploratory Data Analysis (EDA)
Shipment delay frequency and distribution.

Analysis of delivery lead times by region, product category, and carrier.

Correlation between order size, seasonality, and delays.

Inventory turnover analysis to detect slow-moving products.

3. KPI Development
Key performance indicators tracked in the dashboard:

On-Time Delivery Rate (%)

Average Shipment Delay (Days)

Inventory Turnover Ratio

Seasonal Delivery Performance

4. Dashboard Creation
Tool: Microsoft Power BI.

Features:

Shipment delays heatmap.

Seasonal trends visualization.

Inventory turnover drill-down by category.

Interactive filters by region, category, and time period.

Technologies Used
SQL — Data extraction, cleaning, and joining multiple tables.

Python — EDA, data wrangling, and initial KPI calculations.

Power BI — Interactive KPI dashboards and visual reporting.

# Business Value
This analysis empowers supply chain managers to:

Reduce average shipment delays through targeted process optimization.

Improve inventory management by identifying overstock/understock patterns.

Anticipate seasonal challenges and plan resource allocation accordingly.

# How to Run the Project
SQL & Python Steps
Load dataset into a SQL Server or local database.

Run SQL scripts in /SQL_Scripts to clean and preprocess the data.

Use /Python_Scripts to run EDA and calculate KPIs.

# Power BI Dashboard
Open SupplyChain_Dashboard.pbix in Power BI Desktop.

Connect to the preprocessed dataset.

Refresh visuals to explore shipment and inventory performance.

# Dataset
Name: DataCo Supply Chain Dataset

Source: Kaggle Link


