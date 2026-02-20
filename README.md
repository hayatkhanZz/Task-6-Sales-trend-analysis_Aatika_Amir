# Task-6-Sales-trend-analysis_Aatika_Amir
Monthly sales trend analysis using SQL aggregation functions

##  Objective
To analyze monthly sales trends using SQL aggregation functions.

---

##  Tools Used
- SQLite (Online SQL Editor)
- SQL
- GitHub

---

##  Dataset Information
Table Name: online_sales

###Columns:
- order_id
- order_date
- amount
- product_id

A sample dataset of 10 records was created for analysis.

---

##  Analysis Performed

### 1.  Monthly Revenue & Order Volume
- Extracted year and month from order_date
- Used SUM(amount) to calculate total revenue
- Used COUNT(DISTINCT order_id) to calculate total order volume
- Grouped data by year and month
- Sorted results using ORDER BY

### 2. Top 3 Months by Revenue
- Ordered revenue in descending order
- Used LIMIT 3 to identify highest performing months

### 3.  Filtered Analysis (Specific Year)
- Applied WHERE clause to filter year 2024
- Performed grouped monthly analysis

---

##  SQL Concepts Used
- CREATE TABLE
- INSERT INTO
- GROUP BY
- ORDER BY
- SUM()
- COUNT(DISTINCT)
- WHERE
- LIMIT
- Date extraction using strftime()

---

##  Outcome
Successfully analyzed sales trends and identified top-performing months using SQL aggregation techniques.
