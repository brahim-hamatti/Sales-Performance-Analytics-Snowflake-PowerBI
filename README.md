# Sales Performance Analytics Dashboard (Snowflake & Power BI)

## 📌 Project Overview
This project demonstrates an end-to-end data analytics solution, connecting a cloud data warehouse (**Snowflake**) to **Power BI**. The primary goal is to analyze retail sales performance against monthly strategic targets, providing actionable insights into revenue trends, profitability, and target achievement across different product categories.

## 🚀 Live Preview & Visuals
![Dashboard Screenshot](https://github.com/brahim-hamatti/Sales-Performance-Analytics-Snowflake-PowerBI/blob/main/Capture%20d'%C3%A9cran%202026-02-14%20190101.png?raw=true)

## 🛠️ Tech Stack
- **Data Warehouse:** Snowflake (SQL)
- **BI Tool:** Power BI Desktop
- **Data Modeling:** Star Schema / Snowflake Schema
- **Languages:** SQL (CTEs, Views), DAX (Advanced Measures)

## 💡 Key Features & Metrics
- **Actual vs. Target Analysis:** A dynamic comparison of monthly sales against pre-defined targets.
- **Target Achievement %:** A sophisticated DAX measure using `SUMX` and `SUMMARIZE` to ensure data accuracy by eliminating "fan-out" issues from table joins.
- **AOV (Average Order Value):** Calculated to monitor customer purchasing behavior.
- **Profit Margin %:** Real-time tracking of profitability per category and sub-category.
- **Time Intelligence:** Month-over-Month (MoM) performance tracking.

## 🏗️ Data Architecture
1. **Data Sourcing:** Raw data stored in Snowflake.
2. **Data Transformation (SQL):** Used Common Table Expressions (CTEs) and Views in Snowflake to clean data, handle date formats, and prepare the final dataset for BI consumption.
3. **Semantic Layer (DAX):** Developed complex measures in Power BI to handle business logic and KPIs.
4. **Visualization:** Designed an intuitive, dark-themed dashboard focused on executive-level decision-making.

## 📂 Repository Structure
- `Sales_Analysis.pbix`: The core Power BI project file.
- `queries.sql`: Contains the SQL scripts used in Snowflake for data preparation.
- `screenshots/`: Folder containing dashboard visuals.

## 📝 How to Use
1. Clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Review the `queries.sql` file to understand the data transformation logic used in the cloud.
Brahim Hamatti
www.linkedin.com/in/brahim-hamatti-7157731a2

---
**Author:** [Your Name]  
**LinkedIn:** [Your LinkedIn Profile Link]
