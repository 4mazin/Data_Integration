📊 Amazon India Sales Analysis Project
This project demonstrates a full ETL + Dashboard solution for analyzing Amazon India sales data. It integrates multiple data sources, cleans and standardizes date formats using SSIS (SQL Server Integration Services), and delivers an interactive Power BI dashboard to uncover key business insights.

🔧 Project Overview
ETL with SSIS: Extracted raw files in .csv, .xlsx, and .txt formats

Date Standardization: Converted inconsistent date fields from MM/DD/YYYY to YYYY-MM-DD

Data Cleaning: Removed nulls, formatted fields, and prepared unified sales data for analysis

Power BI Dashboard: Visualized total sales, sales by city, category, size, shipping status, and over time

🧰 Tools Used
Visual Studio SSIS – ETL pipeline (extract, clean, transform, load)

Power BI – Dashboard design and visual storytelling

Excel – Raw data preparation and early formatting

| Feature                        | Description                                                       |
| ------------------------------ | ----------------------------------------------------------------- |
| 💰 Total Sales KPI             | Displays total sales amount with dynamic time filtering           |
| 🏙️ Sales by City              | Donut chart showing sales distribution across major Indian cities |
| 🚚 Sales by Ship Service Level | Tree map comparing Expedited vs Standard shipping                 |
| 📦 Sales by Size               | Identifies top-selling clothing sizes                             |
| 📂 Sales by Category & Status  | Shows top-selling product types and shipping performance          |
| 📈 Daily Sales Trend           | Line chart tracking sales patterns over time                      |


📁 Dataset
Source: Amazon India sales (from Kaggle)

Contains order-level data from April to June 2022

Includes: order_date, city, category, size, status, shipping_method, sales

<img width="1517" height="799" alt="image" src="https://github.com/user-attachments/assets/7d826516-affa-4703-911b-2dc0525de1a5" />
