# Sales-analysis-using-excel
Analyzing coffee sales data using excel from data cleaning to building an interactive dashboard.
# Excel Project: Coffee Orders Data Analysis

## Introduction
This project focuses on analyzing coffee orders data using Excel. The goal was to extract meaningful insights from the dataset through data cleaning, formula application, and the creation of an interactive dashboard to track key performance indicators (KPIs). This documentation outlines the steps followed, the final insights, and the methods used throughout the analysis.

## Table of Contents
1. [Final Insights](#final-insights)
2. [Data and What it Contains](#data-and-what-it-contains)
3. [KPIs](#kpis)
4. [Formulas Used](#formulas-used)
5. [Data Cleaning Process](#data-cleaning-process)
6. [Interactive Dashboard Building](#interactive-dashboard-building)
7. [Limitations](#limitations)
8. [References](#references)

## Final Insights
After analyzing the data, the following key insights were observed:
- **Top-selling products:** Arabica coffee in light roast was the most popular, generating the highest sales revenue.
- **Peak order times:** Orders peaked during the months of July and December, aligning with holiday seasons and promotions.
- **Customer segmentation:** Repeat customers with loyalty cards contributed significantly to total sales.
- **Revenue trends:** Revenue increased steadily from 2019 to 2021, with the highest sales recorded in July 2021.
- **Currency conversion:** All financial data was standardized in USD for consistent reporting.

## Data and What it Contains
The dataset contains the following fields:
- **Order ID:** Unique identifier for each coffee order.
- **Customer ID:** Unique identifier for each customer.
- **Product ID:** Unique identifier for each coffee product.
- **Quantity:** The number of units ordered.
- **Order Date:** The date when the order was placed.
- **Price (USD):** The total amount for each order, standardized to US Dollars.
- **Coffee Type:** The type of coffee (e.g., Arabica, Robusta).
- **Roast Type:** The roasting level of the coffee (e.g., Light, Medium).
- **Size:** The weight of the coffee in kilograms (e.g., 0.2 kg, 1 kg).

## KPIs
Key Performance Indicators (KPIs) tracked in this project include:
1. **Total Sales Revenue** - The sum of all sales revenue in USD.
2. **Average Order Value (AOV)** - The average amount spent per order.
3. **Total Quantity Sold** - The total units of coffee sold.
4. **Top Products by Sales** - The best-selling products based on revenue and quantity.
5. **Customer Segments** - Identifying repeat customers with loyalty cards vs. one-time buyers.

## Formulas Used
Several Excel formulas were utilized to streamline data analysis:
- **XLOOKUP:** Used to search and pull data from other sheets.
- **INDEX MATCH:** Applied for advanced lookups across multiple tables.
- **IF condition:** Used for logical comparisons and conditional outputs in data analysis.

## Data Cleaning Process
Before analysis, the dataset underwent the following cleaning steps:
1. **Removing Duplicates:** Ensured that each order record was unique.
2. **Date Setting:** Corrected date formats to enable accurate timeline analysis.
3. **Currency Update:** Standardized the currency values into USD for consistency.
4. **Adding Units of Measurement:** Applied `kg` as a standard for coffee weights to ensure consistency in quantity measurements.

## Interactive Dashboard Building
An interactive dashboard was built to display the results of the analysis using:
- **Pivot Tables:** Summarized the dataset to extract key metrics like total sales, product performance, etc.
- **Slicers & Timeline:** Allowed users to filter and drill down on data by categories such as date range, product type, and more.
- **Graphical Representations:** Created visually appealing graphs (bar charts, line graphs, etc.) to showcase trends.
- **Interactivity:** Connected slicers and graphs to make the dashboard fully interactive for dynamic insights.

## Limitations
The analysis had some limitations, including:
1. **Incomplete Data:** Some orders lacked certain details, leading to partial analysis in specific areas.
2. **Currency Conversion Fluctuations:** Exchange rates may vary, which can impact the accuracy of the USD conversion over time.
3. **Data Source:** The dataset may not fully represent all customer behavior or external market factors.

## References
The analysis was informed by resources on Excel data analysis and visualization:
- Excel Documentation: [Microsoft Excel Support](https://support.microsoft.com/excel)
- Interactive Dashboards: Best practices for dashboard creation using Pivot Tables and Slicers.
- Online Tutorials: [Excel Dashboard Tutorial by Learnit Training](https://www.youtube.com/watch?v=m13o5aqeCbM)

