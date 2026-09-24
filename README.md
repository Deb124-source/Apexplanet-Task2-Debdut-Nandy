# ApexPlanet Data Analytics Internship — Task 2

This repository contains my work for **Task 2 — SQL for Data Extraction** as part of the ApexPlanet 30-Day Data Analytics Internship.

The task focuses on using SQL to extract, analyze, and summarize data from an E-Commerce Sales dataset while connecting SQL workflows with Python.

## Task Objective

The objective of Task 2 was to develop practical SQL skills and apply them to business-oriented data analysis.

The work includes SQL fundamentals, advanced SQL techniques, business questions, database integration, and Python-SQL integration.

## Dataset

The analysis uses a cleaned **E-Commerce Sales dataset** derived from the Online Retail dataset.

The dataset contains transaction-level information including:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country
- Sales Amount

## Work Completed

### SQL Fundamentals

- SELECT statements
- WHERE filtering
- ORDER BY sorting
- DISTINCT values
- COUNT
- Aggregate functions
- GROUP BY
- HAVING
- Product-level analysis
- Monthly sales analysis

### Advanced SQL

- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- Ranking countries by revenue
- Ranking products by revenue
- SQL Views

### Business Analysis

The SQL analysis addressed 10 business questions related to:

1. Total revenue
2. Top products by revenue
3. Top countries by revenue
4. Countries with the highest number of orders
5. Top customers by revenue
6. Monthly revenue trends
7. Top products by quantity sold
8. Average order value
9. Customers with the highest number of orders
10. Products with high revenue per unit

### Python and SQL Integration

The project also demonstrates integration between Python and SQL using:

- SQLite
- SQLAlchemy
- Pandas
- `pandas.read_sql()`

A reusable SQL utility script was also created to handle database connections, query execution, and table information.

## Repository Structure

```text
apexplanet-data-analytics-task-2/
│
├── data/
│   └── online_retail_cleaned.zip
│
├── notebooks/
│   └── Task_2_SQL_Analysis.ipynb
│
├── scripts/
│   └── sql_utils.py
│
├── sql/
│   └── Task_2_Queries.sql
│
└── README.md

Tools & Technologies

Python

Pandas

SQL

SQLite

SQLAlchemy

Google Colab

Jupyter Notebook

GitHub


Key Learning Outcomes

Through this task, I strengthened my understanding of:

Writing structured SQL queries

Aggregating and filtering business data

Using subqueries and CTEs

Applying window functions for ranking and analysis

Creating SQL views

Connecting Python with SQL databases

Translating business questions into data queries

Building reusable SQL utilities


Task Status

Task 2 — Completed

This repository contains the SQL notebook, SQL queries, utility script, and supporting dataset used for the task.


---

Developed as part of the ApexPlanet 30-Day Data Analytics Internship.

