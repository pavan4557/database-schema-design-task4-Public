# database-schema-design-task4-Public
# SQL Developer Internship : Task 4 – Aggregate Functions & Grouping
## 📌 Objective

The objective of this task is to practice using aggregate functions and grouping to summarize and analyze data.
You will learn how to categorize, calculate totals, averages, and filter summarized data.

## 🛠 Tools Used

DB Browser for SQLite

SQLiteStudio

MySQL Workbench

### 📂 Deliverables

SQL Script (aggregate_grouping.sql) containing:

SUM, COUNT, AVG, MAX, MIN functions

GROUP BY categorization

HAVING clause filtering

COUNT DISTINCT, ROUND() examples

README file explaining the task, concepts, and outputs

## 📖 Hints / Mini Guide

Apply aggregate functions on numeric columns: SUM, COUNT, AVG, MAX, MIN.

Use GROUP BY to categorize data by one or more columns.

Filter groups using HAVING (different from WHERE which filters rows before grouping).
## 📖 Interview Questions & Answers

- What is GROUP BY?

Used to group rows that have the same values in specified columns for aggregation.

- Difference between WHERE and HAVING?

WHERE filters rows before grouping, HAVING filters after grouping.

- How does COUNT(*) differ from COUNT(column)?

COUNT(*) counts all rows, COUNT(column) counts only non-NULL values.

- Can you group by multiple columns?

Yes, you can group by more than one column to create sub-groups.

- What is ROUND() used for?

To round numeric values to a specified number of decimal places.

- How do you find the highest salary by department?

SELECT department, MAX(salary) FROM Employee GROUP BY department;

- What is the default behavior of GROUP BY?

It groups identical values in specified columns into a single group.

- Explain AVG and SUM.

AVG() calculates the average of numeric values.

SUM() calculates the total sum of numeric values.

- How to count distinct values?

Use COUNT(DISTINCT column_name).

- What is an aggregate function?

A function that performs a calculation on a set of values and returns a single value (e.g., SUM, AVG, COUNT, MAX, MIN).

## 📑 Key Concepts Covered

Aggregation (SUM, AVG, COUNT, MAX, MIN)

Grouping (GROUP BY)

Filtering grouped data (HAVING)

Counting distinct values

Rounding numeric results


## 📌 Data Source 

[SQL Code](https://github.com/pavan4557/database-schema-design-task4-Public/blob/main/sql%20code.sql)

