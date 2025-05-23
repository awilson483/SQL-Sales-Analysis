# SQL Sales Analysis

![SQL](https://img.shields.io/badge/Language-SQL-blue)
![SQLite](https://img.shields.io/badge/Database-SQLite-green)
![Data Analysis](https://img.shields.io/badge/Skill-Data_Analysis-lightgrey)
![Portfolio Project](https://img.shields.io/badge/Project_Type-Portfolio-orange)
  
Mini-project analyzing fictional sales data using SQL queries to find sales trends, top products, and customer behavior patterns.

---

## 🛠️ Skills Used
- SQL (SQLite3)
- Data Analysis
- Aggregations (SUM, AVG, COUNT)
- Grouping and Sorting Data
- Filtering with WHERE Clauses

---

## 📈 Project Overview
This project focused on using SQL to analyze a simple sales dataset.  
Key tasks included:
- Calculating total revenue and average sales.
- Identifying top-selling products.
- Analyzing customer spending behavior.

The dataset included sales information such as product name, amount, customer ID, and sale date.

---

## 📂 Files Included
- `Day1_SalesData_Setup.sql` — SQL script to recreate and populate the SalesData table
- `Day1_SQL_Practice_Checklist.xlsx` — Challenge tracker to monitor learning progress

---

## 🚀 How to Use
1. Download the `SalesPractice.db` file or run the `Day1_SalesData_Setup.sql` script using [DB Browser for SQLite](https://sqlitebrowser.org/) or any SQL tool.
2. Explore the database by running SQL queries.
3. Replicate the practice challenges listed in the checklist.

Example query to get started:
```sql
SELECT product, SUM(amount) AS total_sales
FROM SalesData
GROUP BY product
ORDER BY total_sales DESC;
```
## 📸 Screenshots

### 1. Query: Select All Sales Data
This query retrieves all sales records from the SalesData table.
![Sales Data](Day1_Screenshots/selectall.jpg)

### 2. Query: Top Selling Products
This query shows the top-selling products by total sales amount.
![Top Selling Products](Day1_Screenshots/amount_descending.jpg)

### 3. Customer Spending Behavior
This query calculates how much each customer has spent and how many purchases they made.
![Customer Spending](Day1_Screenshots/Report.jpg)

### 4. Grouping - Sales by Product
Find the total sales amount per product.
![Sales by Product](Day1_Screenshots/product_amount.jpg)

### 5. Aggregation - Average Sale Amount
Find the average amount per sale.
![Average Sales](Day1_Screenshots/average_sales.jpg)

### 6. Aggregation - Total Sales Amount
Find the total amount of all sales.
![Total Sales](Day1_Screenshots/total_sales.jpg)

### 7. Highest Sale Amount First
Show all sales ordered by amount from highest to lowest.
![Sales Ranked from Highest to Lowest](Day1_Screenshots/amount_descending.jpg)

### 8. Only Laptop Sales
Find sales where the product is 'Laptop'.
![laptop Sales](Day1_Screenshots/laptop.jpg)

# 📊 Day 2: Customer Purchase Behavior Analysis (SQL Joins Project)

---

## 🛠️ Skills Practiced
- SQL Joins (INNER JOIN)
- Aggregations (SUM, AVG, COUNT)
- Conditional Logic (CASE WHEN)
- Grouping and Sorting Data
- Data Analysis across multiple tables

---

## 📚 Project Overview
In this project, I analyzed customer purchasing behavior by joining a `SalesData` table with a `CustomerInfo` table.  
I extracted insights such as:
- Total amount spent by each customer
- Spending trends by loyalty status (Gold, Silver, Bronze)
- Categorization of sales into "High Value Sales" vs. "Regular Sales"
- Summary reports showing customer behavior metrics like total purchases and average purchase amount.

This exercise focused on **data joining**, **data aggregation**, **conditional transformations**, and **summary reporting** — key skills for a data analyst.

---

## 📂 Files Included
- `Day2_CustomerInfo_Setup.sql` — Script to create and populate the CustomerInfo table
- `Day2_CustomerBehavior_Queries.sql` — All SQL queries for challenges and mini-project
- `/Day2_Screenshots/` — Folder containing screenshots of query results

---

## 📸 Day 2 Screenshots

### Challenge 1: Customer Purchases
![Customer Purchases](Day2_Screenshots/challenge1_customer_purchases.JPG)

### Challenge 2: Total Spent per Customer
![Total Spent](Day2_Screenshots/challenge2_total_spent_per_customer.JPG)

### Challenge 3: Loyalty Status Spending
![Loyalty Status Spending](Day2_Screenshots/challenge3_loyalty_status_spending.JPG)

### Challenge 4: High Value Sales
![High Value Sales](Day2_Screenshots/challenge4_high_value_sales.JPG)

### Mini Project: Customer Behavior Report
![Customer Behavior Report](Day2_Screenshots/mini_project_customer_behavior_report.JPG)

---

## 🚀 Key Learnings
- How to combine multiple tables in SQL to create richer insights
- How to use aggregation and grouping to summarize customer behavior
- How to apply conditional logic inside SQL queries
- How to document and present SQL results professionally

