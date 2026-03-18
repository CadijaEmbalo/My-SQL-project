#🗄️ SQL Retail & Sales Data Analysis
A Data Technician Bootcamp Project
---
# 🔍 Overview
This project was completed during my Data Technician Bootcamp, where I used SQL to analyse retail and sales data using the Northwind database. The goal was to apply core SQL techniques — such as filtering, sorting, grouping, and joining tables — to extract meaningful insights that support real business decision‑making.
The project demonstrates my ability to work with relational databases, write efficient SQL queries, and analyse structured datasets in a professional context.
---

# 🛠️ Key Skills Demonstrated

🔎 Querying & Filtering Data

• 	Retrieved specific fields using SELECT

• 	Applied WHERE conditions to filter data by price, country, category, and customer behaviour

• 	Identified high‑value products, key customers, and targeted segments

### 📊 Sorting & Organising Results

• 	Used ORDER BY to sort results by sales, price, date, and customer attributes

• 	Created ranked outputs to highlight top‑performing products and regions

### 📦 Aggregation & Grouping

• 	Applied GROUP BY to summarise data at product, category, and regional levels

• 	Used aggregate functions such as:

• 	 for total sales

• 	 for customer or order volume

• 	 for average price or discount

• 	Generated KPI‑style summaries for business reporting

### 🔗 Joining Tables

• 	Performed INNER JOIN, LEFT JOIN, and RIGHT JOIN to combine related tables

• 	Connected customers, orders, products, suppliers, and categories

• 	Enabled multi‑dimensional insights such as:

• 	Sales by region

• 	Profit by product category

• 	Customer purchasing patterns

### 📸 Northwind Database

This project uses the Northwind sample database, a realistic retail dataset widely used for SQL learning and analytics.

Key tables include:

• 	Customers

• 	Orders

• 	OrderDetails

• 	Products

• 	Categories

• 	Suppliers

• 	Employees

• 	Shippers

These tables allow for real‑world analysis of sales, logistics, customer behaviour, and product performance.

### 🎓 Key Learning Outcomes

Through this project, I developed the ability to:

• 	Write clean, efficient SQL queries

• 	Analyse structured datasets using relational database concepts

• 	Combine multiple tables to uncover deeper insights

• 	Use SQL to answer real business questions

• 	Translate raw data into meaningful summaries and trends

• 	Work confidently with the Northwind database schema

• 	Apply analytical thinking to retail and sales scenarios

### 🧰 Tools Used

• 	SQL (MySQL / PostgreSQL / SQL Server depending on environment)

• 	Northwind Database – primary dataset

• 	MySQL Workbench / Azure Data Studio / DBeaver – query execution

• 	Excel / CSV files – dataset validation

• 	GitHub – version control and documentation

---

### 🧪 Practical Real‑World Scenarios
As part of the bootcamp, I completed a series of real‑world tasks as a Junior Data Analyst at Northwind Traders.

Each task required writing SQL queries to support business operations.



---

### 1. Retrieve Full Customer Data Your manager has asked you to export the full list of all customer details into a report. 
➡️ Write a SQL query to retrieve all columns from the Customers table. 

```
select * from customers; 
```
 
### 2.Customer Names and Cities for  marketing analyst is targeting a campaign based on customer names and their cities. 
➡️ Write a SQL query to retrieve only the CustomerName and City columns from the Customers table. 

```
select customername,
city from customers; 
```

 
###  3.Unique Cities for Delivery Network Expansion ,The logistics team wants to know all the different cities where customers are located (no duplicates). 
➡️ Write a SQL query to retrieve distinct values from the City column in the Customers table. 

```
select count(distinct city) 
from customers; 
```

 

### 4.High-Value Products Report 
The product manager wants to analyse products priced over £50. 
➡️ Write a SQL query to retrieve all columns from the Products table where the Price is greater than 50. 

```
select * from products where price >50; 
```
 










