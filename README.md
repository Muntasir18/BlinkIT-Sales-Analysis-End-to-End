# BlinkIT Grocery Sales Analysis (Python, SQL & Power BI) 

---
## Dashboard Preview
<img width="3224" height="1792" alt="Capture d’écran 2026-05-08 à 19 21 08" src="https://github.com/user-attachments/assets/d6ec991f-e0e2-4baf-9b02-6579dd4734b7" />


## Project Overview
This project provides a comprehensive sales performance analysis for **BlinkIT**, a grocery delivery platform. I developed a full data pipeline to transform raw, fragmented data into actionable business insights, focusing on sales trends, customer satisfaction, and inventory distribution.

The goal was to identify which factors (Fat content, Item type, Outlet size) most impact total revenue and service quality.

## The Data Pipeline
1. **Data Cleaning & Preprocessing (Python):** - Used **Pandas** to handle missing values (NaN) and incorrect data types.
   - Standardized categorical variables (e.g., merging "LF" and "low fat" into "Low Fat").
   - Exported the cleaned dataset for SQL and Power BI consumption.
2. **Data Analysis & Validation (SQL):** - Wrote complex queries to calculate **Total Sales**, **Average Sales**, and **Item Counts**.
   - Performed granular analysis by Outlet size, Location type, and Fat content to validate Power BI metrics.
3. **Data Visualization (Power BI):** - Created an interactive dashboard featuring KPIs, Donut charts for sales distribution, and Column charts for outlet performance.

## Key Business Insights
- **Total Revenue:** Generated over **$1.20M** in total sales with an average rating of **3.97/5**.
- **Top Categories:** "Fruits and Vegetables" and "Snack Foods" are the primary revenue drivers.
- **Outlet Performance:** Medium-sized outlets contribute the most to sales (**42.27%**), while Tier 3 locations show the highest regional growth.
- **Customer Preferences:** Low Fat items account for approximately **64%** of total sales, indicating a strong health-conscious consumer base.

## Technical Highlights
- **Python (Jupyter Notebook):** Pandas, NumPy for data manipulation and exploratory data analysis (EDA).
- **SQL:** Aggregate functions (`SUM`, `AVG`, `COUNT`), `GROUP BY`, `ORDER BY`, and subqueries for percentage calculations.
- **Power BI:** DAX measures, star schema modeling, and interactive filtering.

## Project Resources
- **All Files and Data:** [Blinkit Report](https://drive.google.com/drive/folders/1UuWCEPsKpdjqTcbh76qFkitQ4OvMlaIR?usp=sharing)
