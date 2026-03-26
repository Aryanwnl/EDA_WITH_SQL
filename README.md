# EDA_WITH_SQL

## Executive Summary
This project demonstrates how SQL can be used to perform end-to-end exploratory data analysis (EDA) on structured business data using a dimensional data warehouse model. The objective is to simulate how organizations transform raw transactional data into meaningful insights that support strategic decision-making.

Using customer, product, and sales datasets, the project applies advanced SQL techniques such as joins, aggregations, window functions, ranking, segmentation, and time-based analysis to evaluate business performance. The analysis generates insights related to revenue trends, customer value, product performance, and category-level contribution to overall sales.

The project concludes with reusable reporting views that calculate key performance indicators (KPIs) for customers and products. These outputs illustrate how SQL can be used not only for querying data but also for constructing scalable analytical solutions aligned with real-world data warehouse practices.

---

## Problem Statement
Organizations collect large volumes of transactional data but often lack structured approaches for converting this data into actionable insights. Decision makers require answers to questions such as:

- Which products generate the most revenue?
- Who are the most valuable customers?
- How does revenue change over time?
- What percentage of total revenue comes from each category?
- Which customers should be targeted for retention strategies?
- Which products are high-performing or underperforming?

This project uses SQL-based analytics to answer these business questions through a structured analytical workflow.

## Analytical Approach

### 1. Database Exploration
Initial exploration of available tables and columns to understand the data structure and prepare the environment for analysis.

### 2. Dimension Exploration
Examination of customer and product dimensions to understand categories, geographic spread, and descriptive business attributes.

### 3. Date Range Exploration
Analysis of temporal boundaries in the dataset, including the first and last order date and the customer age range. This helps establish the historical scope of the data.

### 4. Measures Exploration
Calculation of core business metrics such as total sales, total quantity sold, average selling price, total orders, total products, and total customers. This provides a baseline summary of business performance.

### 5. Magnitude Analysis
Evaluation of business size across categories, countries, customers, and products using aggregated metrics.

### 6. Ranking Analysis
Identification of top-performing and low-performing customers and products through ranking logic.

### 7. Change Over Time Analysis
Tracking of sales and business activity across time to identify trends and patterns.

### 8. Cumulative Analysis
Use of window functions to calculate running totals and moving averages for performance tracking.

### 9. Performance Analysis
Comparison of current performance against historical averages and previous periods.

### 10. Data Segmentation
Classification of customers and products into meaningful business groups for decision-making.

### 11. Part-to-Whole Analysis
Measurement of how much each category contributes to total revenue.

### 12. Customer Report
Creation of a reusable reporting layer with customer-level KPIs.

### 13. Product Report
Creation of a reusable reporting layer with product-level KPIs.

## Author
Aryan Ninad Dalvi  
Master of Science in Information Systems   
Pace University, New York
