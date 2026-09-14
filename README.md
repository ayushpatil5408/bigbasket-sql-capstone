# bigbasket-sql-capstone
# BigBasket SQL & Data Analytics Capstone Project

## Project Overview
This repository contains the end-to-end data analytics and SQL capstone project analyzing BigBasket order data, category revenue performance, and data hygiene cleaning pipelines.

## Project Structure
- **`bigbasket_capstone.db`**: SQLite database containing products, customers, orders, and category targets.
- **`bigbasket_capstone.ipynb`**: Jupyter Notebook detailing data generation, SQL queries, and Pandas data cleaning.
- **`orders_raw.csv` / `orders_cleaned.csv`**: Raw generated dataset with simulated real-world anomalies vs. the cleaned final version.
- **`monthly_category_revenue.csv` & `bigbasket_revenue_analysis.xlsx`**: Monthly category-wise revenue aggregation and spreadsheet pivot table validation.

## Key Highlights & Workflow
1. **Database Setup & SQL Queries**: Built relational tables with foreign keys and executed foundational queries, filtering, aggregation, and JOINs.
2. **Spreadsheet Reconciliation**: Imported category revenue into Google Sheets and validated sums via pivot tables against SQL totals.
3. **Tableau Dashboard**: Visualized monthly revenue trends and category performance against targets.
4. **Data Cleaning (Pandas)**: Addressed casing issues, stripped extra whitespace, imputed missing values, resolved numerical outliers, and removed duplicate entries.

## Tableau Dashboard Link
You can view the interactive Tableau Public dashboard here: [Insert Your Tableau Public URL]
