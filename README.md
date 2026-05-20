# zepto-data-analysis

## Description
This project focuses on analyzing Zepto product and inventory data using PostgreSQL. The analysis includes data exploration, cleaning, and business insights generation using SQL queries.

The project demonstrates practical SQL skills such as:
- Table creation
- Data cleaning
- Aggregate functions
- CASE statements
- Filtering and sorting
- Business analysis queries

---

## Tools & Technologies Used
- PostgreSQL
- SQL
- pgAdmin

---

## Database Schema

### Table: zepto

| Column Name | Data Type |
|---|---|
| sku_id | SERIAL PRIMARY KEY |
| category | VARCHAR(120) |
| name | VARCHAR(150) |
| mrp | NUMERIC(8,2) |
| discountPercent | NUMERIC(5,2) |
| availableQuantity | INTEGER |
| discountedSellingPrice | NUMERIC(8,2) |
| weightInGms | INTEGER |
| outOfStock | BOOLEAN |
| quantity | INTEGER |

---

## Project Workflow

### 1. Data Exploration
Performed initial exploration using SQL queries:
- Total row count
- Sample records
- Null value checks
- Distinct product categories
- Stock availability analysis
- Duplicate product identification

### 2. Data Cleaning
Performed cleaning operations such as:
- Removing products with zero price
- Converting paise values into rupees
- Validating cleaned data

### 3. Data Analysis
Performed business analysis using SQL queries.

---

## Business Questions Solved

### Q1. Top 10 Best Value Products
Identified products with the highest discount percentages.

### Q2. High MRP Products That Are Out of Stock
Analyzed expensive products currently unavailable.

### Q3. Estimated Revenue by Category
Calculated estimated revenue using product quantity and selling price.

### Q4. Premium Products with Low Discounts
Found products with high MRP but low discount percentages.

### Q5. Categories with Highest Average Discounts
Identified categories offering the best discounts on average.

### Q6. Best Value Products by Price Per Gram
Calculated price per gram for products above 100g.

### Q7. Product Weight Classification
Grouped products into:
- Low
- Medium
- Bulk

using CASE statements.

### Q8. Total Inventory Weight Per Category
Calculated overall inventory weight for each category.

---

## Key SQL Concepts Used
- SELECT statements
- WHERE clause
- GROUP BY
- ORDER BY
- HAVING clause
- Aggregate Functions
- CASE statements
- Data Cleaning Queries
- UPDATE and DELETE operations

---

## Project Learnings
- Improved SQL querying skills
- Learned data cleaning techniques
- Performed real-world business analysis
- Practiced aggregate and conditional queries
- Worked with inventory and pricing datasets

---

## Conclusion
This project demonstrates how SQL can be used to clean, explore, and analyze retail inventory data to generate valuable business insights.

---

## Author
Aman Sharma
```
