# pizza-sales-sql
# 🍕 Pizza Sales Analysis using MySQL

## Overview

This repository contains an end-to-end data analysis project focused on understanding sales performance for a pizza business. The project demonstrates proficiency in database management, SQL querying, data analysis, and business intelligence.

The analysis is performed using MySQL by importing raw CSV datasets into a relational database and executing various SQL queries to uncover meaningful business insights.

---

## Dataset

The dataset consists of four primary tables:

- **orders** – Contains order-level information such as order date and time.
- **order_details** – Stores details of pizzas included in each order.
- **pizzas** – Contains pizza size and pricing information.
- **pizza_types** – Includes pizza names, categories, and ingredients.

The raw data is provided in CSV format and imported into a MySQL database for analysis.

---

## Technologies Used

- MySQL
- MySQL Workbench
- SQL

---

## Key SQL Concepts Demonstrated

### Joins
Used to combine data across multiple tables for comprehensive analysis.

### Aggregations
Applied functions such as:
- `SUM()`
- `COUNT()`
- `AVG()`
- `GROUP BY`

to calculate revenue, order counts, and quantity metrics.

### Window Functions
Used for:
- Ranking pizza types
- Calculating cumulative revenue
- Comparing category-wise performance

### Subqueries
Implemented nested queries to solve complex analytical requirements and filtering conditions.

---

## Project Objectives

This project aims to answer the following business-critical questions:

1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Determine the most commonly ordered pizza size.
5. List the top 5 most ordered pizza types along with their quantities.
6. Find the total quantity ordered for each pizza category.
7. Analyze the distribution of orders by hour of the day.
8. Determine the category-wise distribution of pizzas.
9. Calculate the average number of pizzas ordered per day.
10. Identify the top 3 pizza types based on revenue within each category.

---

## Analysis Highlights

The project provides insights into:

- Overall sales performance
- Customer ordering patterns
- Popular pizza categories and sizes
- Revenue contribution by pizza type
- Peak ordering hours
- Category-wise sales trends

These insights can help businesses make informed decisions regarding inventory management, marketing strategies, and menu optimization.

---

## How to Use

### Step 1: Import Dataset
Import the provided CSV files into MySQL Workbench.

### Step 2: Create Database and Tables
Create the required database schema and tables corresponding to the dataset.

### Step 3: Load Data
Load the CSV files into their respective tables.

### Step 4: Execute SQL Queries
Run the SQL scripts provided in this repository to perform the analysis.

### Step 5: Review Insights
Analyze the query outputs to understand sales trends and business performance.

---

## Learning Outcomes

By completing this project, you will gain hands-on experience with:

- Relational database design
- Data cleaning and preparation
- Complex SQL querying
- Business-oriented data analysis
- Data-driven decision making

---

## Author

Developed as a portfolio project to demonstrate practical SQL and data analysis skills using real-world business data.
