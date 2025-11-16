# Super-Store-SQL-Data-Cleaning-and-Analysis-Project
A full end-to-end SQL project focused on data cleaning, type conversions, ranking analysis, and missing value imputation using data from a hypothetical Super Store.

This project demonstrates practical SQL skills used in real-world analytics roles.
## Project Overview
In this project, I worked with four datasets:
- orders
- returned_orders
- people
- products

The goal is to:
- Creating and structuring a database
- Fixing inconsistent data types
- Handling missing values using statistical logic
- Performing ranking & aggregation
- Joining multiple tables
- Producing analysis-ready datasets

## Dataset Overview
This project uses four related tables
### orders
Contains sales transaction details. Containing the following columns
- ``row_id``: Unique record ID
- ``order_id`` : Order identifier
- ``order_date`` : Date of order
- ``market``: Market of order
- ``region``: Customer region
- ``product_id``: Product identifier
- ``sales``: Total sales amount
- ``quantity``: Quantity sold (contains missing values)
- ``discount``: Discount applied
- ``profit``	: Line item profit
### returned_orders
Shows all returned items. Containing the following columns
- ``returned`` : Returned flag
- ``order_id`` : Order ID
- ``market`` : Market
### people
Salesperson information. Containing the following columns
- ``region`` : Region of salesperson
- ``person`` : Salesperson name
### products
Product catalog details. Containing the following columns
- ``product_id`` : Unique product ID
- ``category`` : Product category
- ``sub_category`` : Product sub-category
- ``product_name`` : Full product name


## 1. Database Setup
[attach sql file]
### Code Snippet
[attach database creation ss]

## Analysis #1 — Top 5 Products in Each Category
[attach sql file]
### Code Snippet
[attach database creation ss]
## Analysis #2 — Impute Missing Quantity Values
[attach sql file]
### Code Snippet
[attach database creation ss]
