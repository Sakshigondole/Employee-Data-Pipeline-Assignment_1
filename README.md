# Employee Data Pipeline (Spark + PostgreSQL)

## Overview
This project demonstrates a data engineering pipeline using Apache Spark and PostgreSQL.

## Steps Performed
- Data ingestion from CSV
- Data cleaning:
  - Removed duplicates
  - Validated email format
  - Filtered future hire dates
- Data transformation
- Data loading into PostgreSQL

## Technologies Used
- PySpark
- PostgreSQL
- Jupyter Notebook

## How to Run
1. Install dependencies:
   pip install pyspark

2. Start Spark session

3. Run pipeline.ipynb

## Output
Final cleaned data is stored in PostgreSQL table:
employees_clean

## Sample Query
SELECT COUNT(*) FROM employees_clean;
