# Analytical SQL Project: Exploring Trends, Segmentation, and KPIs

## Introduction
A complete SQL analytics project using a simulated data warehouse. This project analyzes sales, customer, and product data to deliver insights on trends and segmentation. The goal is to demonstrate how SQL can be used for data-driven decisions without relying on BI tools.

## Dataset
The dataset consists of three main tables:
* `sales.csv`: Contains transactional data, including product IDs and customer IDs.
* `customers.csv`: Contains demographic information about customers.
* `products.csv`: Contains details about each product.

## Tools Used
* **SQL Dialect:** PostgreSQL (or MySQL, T-SQL, etc.)
* **Database:** [Name of the database software you used]

## How to Run This Project
1.  Set up a [Database Name] instance.
2.  Create the schema and import the `.csv` files into their respective tables.
3.  Run the queries in the `your_sql_script.sql` file in sequential order.

## Key Queries and Findings
* **Customer Segmentation:** Used CTEs and window functions to segment customers into 'High-Value' and 'Regular' tiers based on purchase frequency and value.
* **Sales Trends:** Analyzed monthly sales growth, identifying the top-performing products.

## Future Improvements
* Incorporate more complex window functions to analyze customer churn.
* Automate the data import and query execution process.
