
# 🐄 Moo Farms FP&A Dashboard

## 📎 View the Live Dashboard

👉 [Moo Farms FP&A Dashboard on Tableau Public](https://public.tableau.com/app/profile/angelo.bennett/viz/MooFarmsFPADashboard/FPASalesInsights)

## Overview
This project demonstrates **Financial Planning and Analysis (FP&A)** using transformed dairy sales data for **Moo Farms**, a fictional dairy company. The project showcases how to analyze sales trends and visualize key performance indicators (KPIs) using **Python** (Jupyter Notebook) for data analysis and **Tableau** for creating an interactive dashboard.

### Tools & Technologies
- **Python (Jupyter Notebook)**: Data preprocessing, analysis, and transformation.
- **Tableau**: Interactive dashboard for visualizing KPIs such as sales trends and top-selling products.
- **Pandas**: For data manipulation and cleaning.

### Data
- The dataset used in this project is a **transformed sales dataset** originally in an Indian context, which has been converted to fit U.S.-based standards (i.e., locations and currency formatting were modified).
- The dataset includes sales data such as product names, revenue, quantity sold, and prices.

## Features & Insights
1. **Sales Trend Analysis**: Visualize the total revenue over time, with dynamic moving averages.
2. **Top-Selling Products**: Identify and visualize the products with the highest sales revenue.
3. **Units Sold by Product Category**: Analyze the total quantity sold by product category.
4. **Key Performance Indicators (KPIs)**: Display essential business metrics like total revenue and sales trends via a dynamic Tableau dashboard.
 
## Project Walkthrough

### Data Preprocessing:
The raw dataset was first reviewed and then **transformed to U.S. market standards**:
- Replaced Indian product names and locations with U.S. equivalents.
- Converted currency values to U.S. dollars.

### KPIs Created:
1. **Total Sales Revenue**: Calculated total revenue for each product and by time period.
2. **Units Sold by Category**: Analyzed total quantity sold across different product categories.
3. **Top-Selling Products**: Ranked products by revenue to identify the most profitable ones.
4. **Monthly Sales Trends**: Analyzed revenue trends on a monthly basis, including a moving average.

### Tableau Dashboard:
The project includes a **Tableau dashboard** that presents these KPIs interactively:
- **Sales trend visualization** with the ability to adjust moving averages.
- **Top-selling products by revenue** displayed as a bar chart.
- **KPI metrics** showing total revenue and key performance indicators for Moo Farms.

## Files Included:
- **`dairy_sales.ipynb`**: Jupyter Notebook containing data exploration, preprocessing, and visualizations.
- **`dairy_sales_us_cleaned`**: Transformed sales dataset.
- **`Moo Farms FP&A Dashboard.twbx`**: Tableau packaged workbook for the interactive dashboard.

## Acknowledgements
- Dataset sourced from Kaggle.
