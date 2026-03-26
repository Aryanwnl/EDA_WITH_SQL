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
Understanding available tables and column structures to confirm schema consistency and data readiness.

### 2. Dimension Exploration
Examining customer demographics and product categories to understand the descriptive structure of the business environment.

### 3. Date Range Exploration
Identifying minimum and maximum order dates and customer age boundaries to determine the historical coverage of the dataset.

### 4. Measures Exploration
Calculating foundational business metrics such as total sales, total quantity sold, average price, total orders, total products, and total customers.

### 5. Magnitude Analysis
Measuring overall business scale across categories, countries, customers, and products using aggregated metrics.

### 6. Ranking Analysis
Identifying top-performing and lowest-performing customers and products using ranking logic.

### 7. Change Over Time Analysis
Evaluating how business performance evolves across months and years to identify trends and patterns.

### 8. Cumulative Analysis
Using window functions to compute running totals and moving averages for long-term performance tracking.

### 9. Performance Analysis
Comparing current performance with historical averages and previous time periods to assess growth or decline.

### 10. Data Segmentation
Classifying customers and products into interpretable groups such as:

- VIP customers
- Regular customers
- New customers
- High-performing products
- Mid-range products
- Low-performing products

### 11. Part-to-Whole Analysis
Calculating percentage contribution of each category to total revenue.

### 12. Customer Report
Creating a reusable analytical view containing customer-level KPIs such as:

- total orders
- total revenue
- total quantity purchased
- customer lifespan
- recency
- average order value
- customer segment

### 13. Product Report
Creating a reusable analytical view containing product-level KPIs such as:

- total sales
- total customers
- average selling price
- monthly revenue
- product performance category

---

## Analytical Rigor

This project applies a structured analytical methodology to ensure logical consistency, reproducibility, and interpretability of results.

### Structured Analytical Framework

**Data Understanding**
- Identification of entities, attributes, and relationships
- Validation of schema consistency across fact and dimension tables

**Metric Construction**
- Definition of KPIs using standardized aggregation logic
- Consistent calculation of revenue, quantity, and customer activity measures

**Temporal Consistency**
- Standardization of time intervals using date truncation logic
- Separation of trend analysis from point-in-time evaluation

**Window Function Logic**
- Use of cumulative metrics to analyze long-term growth
- Use of moving averages to reduce volatility in temporal patterns
- Period-over-period comparison using lag functions

**Ranking and Relative Comparison**
- Identification of distribution extremes using ranking logic
- Comparative evaluation across customers and products

**Segmentation Validity**
- Construction of interpretable categorical groupings from quantitative metrics
- Alignment of segmentation thresholds with observed data distribution

**Part-to-Whole Consistency**
- Verification that segmented contributions reconcile with total revenue values

**Reproducibility**
- Modular SQL scripts enabling step-by-step verification
- Logical separation between exploration and reporting layers

**Scalability**
- Dimensional model supports extension to additional entities
- Query design adaptable to larger datasets and BI tools

---

## SQL Techniques Used
- Aggregation functions (SUM, AVG, COUNT)
- Joins between fact and dimension tables
- Window functions (SUM OVER, AVG OVER, LAG, RANK)
- Date functions for time-based analysis
- CASE statements for segmentation
- View creation for reusable reports
- Dimensional modeling concepts

---

## Key Insights Generated
The project enables identification of:

- revenue trends over time
- high-value customers
- top-performing products
- purchasing behavior patterns
- category contribution to total revenue
- long-term business performance indicators

These insights support data-driven decision-making across sales and marketing functions.

---

## Tools and Technologies
- SQL (T-SQL)
- SQL Server
- Dimensional Data Modeling
- Analytical SQL Queries
- Window Functions

## Author
Aryan Ninad Dalvi  
Master of Science in Information Systems   
Pace University, New York
