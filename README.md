# Week 2 Assignment: Introduction to SQL

This repository contains the SQL solutions for the Week 2 assignment using the `sales` database.

## Before you begin

The `sales` database must already be imported into MySQL. If you do not have it, download the database files from the [Week 2 Database Assignment Google Drive folder](https://drive.google.com/drive/folders/1kp9_Zf7qWKZm7UGtPWJaCanuLVZYrpcl?usp=sharing) and follow the provided import video.

Confirm the database exists and select it:

```sql
SHOW DATABASES;
USE sales;
```

## Assignment solutions

All five answers are in [`week2_assignment.sql`](week2_assignment.sql).

1. Retrieve payment check number, payment date, and amount.
2. Find orders with status `In Process`, newest order date first.
3. Find employees with job title `Sales Rep`, ordered by employee number descending.
4. Retrieve all records and columns from `offices`.
5. Retrieve the five products with the lowest `buyPrice`, showing product name and quantity in stock.

## How to run

1. Open MySQL Workbench or another MySQL client.
2. Connect to your MySQL server.
3. Open `week2_assignment.sql`.
4. Run the statements after confirming the `sales` database is imported.

The queries use the standard MySQL sales sample database schema.
