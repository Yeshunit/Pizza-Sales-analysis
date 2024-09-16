# Pizza-sales-analysis
This project involves analyzing pizza sales data to gain insights into sales patterns, popular pizza types, and revenue trends. The analysis was conducted using SQL, leveraging various queries to process and interpret the data.
# Pizza Sales Analysis

This repository contains the analysis of pizza sales data using SQL. The analysis includes various insights derived from the data on orders, pizza types, and order details.

## Project Structure
Download pizza_sales_zip file to extract all the raw data

- `order_details.csv`: Contains details of each pizza order **(48,620 rows)**.
- `orders.csv`: Contains information about the orders **(21,350 rows)**.
- `pizza_types.csv`: Contains information about the types of pizzas **(32 rows)**.
- `pizzas.csv`: Contains information about the pizzas **(96 rows)**.
- `pizzahut_final_project.pdf`: The final report detailing the analysis.

## Analysis

The analysis was performed using SQL to extract meaningful insights from the data. The following sections outline the key findings:

### Data Overview

- **Order Details:** This file includes columns for order_id, pizza_id, quantity, etc.
- **Orders:** This file includes columns for order_id, date, time, etc.
- **Pizza Types:** This file includes columns for pizza_type_id, name, category, etc.
- **Pizzas:** This file includes columns for pizza_id, pizza_type_id, size, etc.

### Key Findings

1. **Sales by Pizza Type:**
   - Analysis of the most popular pizza types and their sales figures.

2. **Sales Over Time:**
   - Trends in sales over different time periods.

3. **Order Details:**
   - Insights into the order quantities and preferences.

4. **Revenue Analysis:**
   - Calculation of total revenue and revenue by different categories.

   ![Uploading image.png…]()


## Steps for Analysis:
1. **Data Loading:** The CSV files were loaded into a SQL database.
2. **Data Cleaning:** Ensured data integrity and handled any missing or inconsistent values.
3. **Query Execution:** Ran SQL queries to extract insights such as total sales by pizza type, sales trends over time, and revenue calculations.


