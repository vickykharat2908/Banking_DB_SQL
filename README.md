# Banking Management System – SQL Project

## Project Overview
The Banking Management System is a SQL-based project developed using MySQL. It manages banking-related data, including customers, accounts, transactions, branches, and loans. The project demonstrates how SQL can be used to store, organize, retrieve, and analyze banking information.

## Objectives
- Create and manage a banking database using MySQL.
- Store customer, account, transaction, branch, and loan details.
- Retrieve information using SQL queries and filtering conditions.
- Analyze account balances, transactions, and loan amounts.
- Practice joins, subqueries, aggregate functions, and window functions.
- Create views to simplify access to frequently used data.

## Technologies Used
- **Database:** MySQL
- **Language:** SQL
- **Tool:** MySQL Workbench or any compatible MySQL environment

## Database Tables

The project includes the following main tables:

1. **Customers** – Stores customer names, email addresses, phone numbers, and dates of birth.
2. **Accounts** – Stores account IDs, account types, balances, and customer references.
3. **Transactions** – Stores transaction dates, amounts, transaction types, and related accounts.
4. **Branches** – Stores branch names, addresses, and phone numbers.
5. **Loans** – Stores loan amounts, interest rates, start dates, end dates, and customer references.

## SQL Concepts Covered

### 1. Database and Table Management
- CREATE DATABASE and CREATE TABLE
- ALTER TABLE and DROP TABLE
- Adding primary keys and foreign keys
- UNIQUE, NOT NULL, and CHECK constraints

### 2. Data Manipulation
- INSERT, UPDATE, and SELECT
- Retrieving records from tables
- Modifying customer details and account information

### 3. Filtering and Sorting
- WHERE, BETWEEN, IN, and LIKE
- IS NULL and IS NOT NULL
- ORDER BY, DISTINCT, LIMIT, and OFFSET

### 4. Aggregate Functions
- SUM()
- AVG()
- MAX()
- MIN()
- COUNT()

### 5. Grouping and Conditional Logic
- GROUP BY and HAVING
- CASE statements
- IF() and IFNULL()

### 6. Joins and Subqueries
- INNER JOIN
- LEFT JOIN
- Subqueries using AVG() and MAX()
- Comparing account balances and transaction amounts with calculated values

### 7. Window Functions
- RANK()
- DENSE_RANK()
- ROW_NUMBER()
- SUM() OVER()
- AVG() OVER()
- LAG() and LEAD()

### 8. Other SQL Features
- String functions such as UPPER(), LOWER(), LENGTH(), and CONCAT()
- Mathematical functions such as ROUND(), CEIL(), FLOOR(), and ABS()
- Date functions such as CURDATE(), NOW(), YEAR(), MONTH(), and DATEDIFF()
- Creating and updating SQL views

## Key Operations Performed
- Retrieved customer and account information.
- Filtered savings and current accounts based on their balances.
- Calculated total and average account balances.
- Identified accounts with high balances.
- Analyzed deposits and withdrawals.
- Compared transaction amounts with the average transaction value.
- Ranked accounts and loans based on balances and loan amounts.
- Combined account and transaction data using joins.
- Created a view to display high-balance accounts and their transaction details.

## Learning Outcomes
Through this project, I practiced designing a relational database, maintaining relationships between tables, writing SQL queries, analyzing banking data, and using advanced SQL features to retrieve meaningful information.

##Author

**Vicky Kharat**
