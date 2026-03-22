## Project Overview
This project demonstrates a simple end-to-end ETL pipeline built in Databricks using PySpark.

The pipeline follows a medallion architecture:
- Bronze: Raw data ingestion
- Silver: Data cleaning and transformation
- Gold: Aggregated data for analysis

## Pipeline Steps
1. Extract: Load CSV data into a raw table
2. Transform: Clean data (remove nulls, cast types)
3. Load: Create aggregated dataset for analysis

## Analysis
The final dataset shows the relationship between:
- Hours studied
- Exam score

A visualization was created to illustrate how study time impacts performance.

## Tech Stack
- Databricks
- PySpark
- SQL

## Key Insight
There is a clear positive trend between study hours and exam scores.
