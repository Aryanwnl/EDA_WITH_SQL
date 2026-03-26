# EDA_WITH_SQL

## Project Structure

EDA_WITH_SQL
│
├── Dataset
│   ├── gold.dim_customers.csv
│   ├── gold.dim_products.csv
│   └── gold.fact_sales.csv
│
├── Scripts
│   ├── 00_database.sql
│   ├── 01_database_expploration.sql
│   ├── 02_dimension_exploration.sql
│   ├── 03_date_range_exploration.sql
│   ├── 04_measures_exploration.sql
│   ├── 05_magnitude_analysis.sql
│   ├── 06_Ranking_analysis.sql
│   ├── 07_Change_over_time_analysis.sql
│   ├── 08_Cumulative_analysis.sql
│   ├── 09_performance_analysis.sql
│   ├── 10_data_segmentation.sql
│   ├── 11_Part_to_whole_analysis.sql
│   ├── 12_Report_customer.sql
│   └── 13_Report_product.sql


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
