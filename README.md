# cmsc408-sp2025-hw8

## Homework 8 - World Bank Indicator Analysis

This project involves using SQL to explore and analyze data from the World Bank’s WDI (World Development Indicators) database. The tasks covered a wide range of SQL skills, including data selection, aggregation, filtering, joins, grouping, using common table expressions (CTEs), and building more complex analytical queries.

The goal was to cleanly separate country-level data from non-country groupings (such as regions or aggregates), explore income group classifications, and analyze regional trends through different SQL operations.

---

## Tasks Overview

- Task 1-2: Basic data exploration (record counts, initial inspection of records).
- Task 3: Identified non-country records by checking where the Region field is NULL.
- Task 4-5: Created a clean version of the country table and counted the number of countries.
- Task 6-7: Investigated unique regions and country counts by region.
- Task 8-9: Filtered and retrieved country information based on region and specific countries.
- Task 10-11: Explored country abbreviation mismatches and income group distributions.
- Task 12-13: Identified missing income group classifications and corrected data anomalies.
- Task 14-17: Grouped and analyzed countries by region and income group, finding detailed regional patterns.
- Task 18-21: Built advanced tables showing missing region-income combinations and calculated percentages of country distribution across different income levels.

---

## Skills Demonstrated

- Writing clean and efficient SELECT and WHERE statements.
- Using GROUP BY, ORDER BY, and aggregation functions like COUNT() and ROUND().
- Implementing CASE statements for conditional aggregation.
- Using Common Table Expressions (CTEs) to simplify complex queries.
- Performing nested queries and subqueries for comparative analysis.
- Handling missing or NULL data appropriately.
- Building pivot-style tables with SQL for better data presentation.

---

## Challenges and Learning Takeaways

- Handling missing Region or Income Group fields required careful filtering.
- Building multi-step CTE queries improved understanding of how to break complex problems into manageable pieces.
- Learned the importance of validating assumptions against the data (e.g., checking that “non-countries” had NULL regions).
- Gained experience in writing SQL that not only retrieves data but also transforms it for deeper insights.

---

## How to Run

This project runs in a Jupyter Notebook or Quarto environment using Python helper functions:

- Helpers used: `create_database_engine`, `run_sql_and_return_df`, `run_sql_and_return_html`, `execute_ddl`
- Database connection: Credentials are loaded from a `.env` file.
- SQL Execution: Queries are passed as strings into helper functions to execute against the World Bank dataset.

You can view the full project and code at:  
[GitHub Repository](https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-RayanBTW/blob/319b4aab52b244f617e718302601623738165635/reports/report.qmd)