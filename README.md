# SQL Sales Data Analysis Project

## Overview

This project demonstrates data analysis using SQL on a sales dataset. The goal of the project is to transform raw transactional data into structured analytical tables that can support business reporting and decision-making.

The analysis includes building a **fact table** and several **dimension tables** to better understand sales performance across products, customers, orders, and shipping companies.

---

## Objectives

* Analyze sales data using SQL
* Build analytical tables for reporting
* Perform aggregation and transformation of transactional data
* Demonstrate SQL skills for data analysis

---

## Dataset

The project uses a sales dataset containing the following tables:

* Orders
* Order Details
* Products
* Customers
* Employees
* Shippers
* Categories
* Suppliers

These tables are joined together to create analytical outputs for business insights.

---

## Data Model

Here is the Star Schema of the project:
<img width="1536" height="1024" alt="Project star schema" src="https://github.com/user-attachments/assets/d8440076-01bc-4e57-9a69-0ccfa908ce90" />


### Fact Table

The fact table combines transactional data to calculate sales values.

Columns include:

* Order ID
* Customer ID
* Employee ID
* Product ID
* Order Date
* Quantity
* Unit Price
* Discount
* Line Total (calculated)

---

### Dimension Tables

Dimension tables are created to analyze sales across different perspectives:

**Product Dimension**

* Product Name
* Category
* Supplier Information
* Total Sales by Product

**Customer Dimension**

* Customer Name
* Country
* Total Sales by Customer

**Shipper Dimension**

* Shipping Company
* Total Sales by Shipper

**Order Summary**

* Total Sales by Order

---

## Key SQL Techniques Used

* Multiple table joins
* Aggregation functions (SUM)
* Data transformation
* Calculated fields
* GROUP BY analysis
* Dimensional analysis

---

## Example Analysis

This project enables analysis such as:

* Total sales by product
* Sales performance by customer
* Sales distribution by shipper
* Order-level revenue analysis

---

## Tools Used

* SQL
* PostgreSQL
* Microsoft Excel
* GitHub

## Power BI Dashboard
Here is the dashboard view:
<img width="1920" height="1050" alt="ScreenShot of CapStoneProject" src="https://github.com/user-attachments/assets/2b74400d-78da-4a8d-ab3c-dfddb468c1ce" />

Download the full Power BI file here:
[Dashboard.pbix](PowerBI/Dashboard.pbix)
---

## Author

**Sat Paing Oo**

Aspiring Data Analyst with experience in laboratory data management and data reporting.
Interested in transforming raw data into useful insights using SQL, Python, Excel, and Power BI.

GitHub Profile:
https://github.com/SatPaing1993
