# data_warehouse
# SQL Data Warehouse and Analytics Project

## Project Overview

This project demonstrates the design and implementation of an end-to-end SQL Data Warehouse using the Medallion Architecture (Bronze, Silver, and Gold layers). The solution extracts data from multiple source systems, transforms and cleans the data, builds a business-ready data warehouse, and supports analytical reporting using SQL.

The project follows industry best practices for ETL development, data modeling, and data warehousing.

---

## Architecture

The project follows the Medallion Architecture, which consists of three layers:

### Bronze Layer

- Loads raw data from CRM and ERP source systems.
- Stores source data without any transformations.
- Serves as the landing layer for all incoming data.

### Silver Layer

- Cleans and transforms raw data.
- Removes duplicate records.
- Handles NULL values.
- Standardizes data formats.
- Applies business rules and validations.

### Gold Layer

- Stores business-ready data.
- Implements a Star Schema.
- Contains fact and dimension tables optimized for reporting and analytics.

---

## ETL Process

The ETL pipeline consists of the following steps:

1. Extract data from CRM and ERP source files.
2. Load raw data into the Bronze layer.
3. Clean and transform data in the Silver layer.
4. Build fact and dimension tables in the Gold layer.
5. Execute analytical SQL queries for business reporting.

---

## Features

- End-to-End SQL Data Warehouse
- Medallion Architecture
- ETL Pipeline using Stored Procedures
- Data Cleansing and Transformation
- Star Schema Data Modeling
- Fact and Dimension Tables
- SQL-Based Business Analytics
- Reporting-Ready Data Model

---

## Technologies Used

- Microsoft SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- Stored Procedures
- Views
- Common Table Expressions (CTEs)
- Window Functions
- Git
- GitHub

---

## Project Structure

```
SQL-Data-Warehouse/
│
├── datasets/
│   ├── source_crm/
│   └── source_erp/
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── analytics/
│
├── docs/
│
└── README.md
```

---

## Data Model

The Gold layer follows a Star Schema.

### Dimension Tables

- dim_customer
- dim_product
- dim_date

### Fact Tables

- fact_sales

---

## Business Analysis

The data warehouse supports the following business analyses:

- Total Sales
- Monthly Sales Trends
- Top Customers
- Best Selling Products
- Sales by Country
- Customer Performance
- Product Performance
- Year-over-Year Sales Growth

---

## SQL Concepts Used

- Joins
- Aggregate Functions
- CASE Expressions
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LEAD()
- LAG()
- GROUP BY
- HAVING
- Views
- Stored Procedures

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Data Warehouse Design
- ETL Development
- Medallion Architecture
- Data Cleaning and Transformation
- Star Schema Modeling
- SQL Query Optimization
- Business Analytics
- Reporting and Data Modeling

---

## Future Enhancements

- Incremental Data Loading
- ETL Automation
- SQL Server Agent Scheduling
- Performance Optimization
- Indexing Strategy
- Power BI Dashboard Integration

---

## Author

**Pratik Khose**

Aspiring Data Engineer | Data Analyst | SQL Developer

**Skills**

- SQL Server
- T-SQL
- Microsoft Fabric
- Power BI
- ETL
- Data Warehousing

**GitHub**

https://github.com/pratikkhose27-hub
