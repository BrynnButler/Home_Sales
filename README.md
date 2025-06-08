# Home_Sales
module 22

# Overview

This project was completed as part of the Module 22 Challenge for the University of Minnesota Data Visualization and Analytics Bootcamp. The goal was to use **Apache Spark** and **SparkSQL** to analyze a real estate dataset and determine key metrics related to home sales.

# Dataset

The dataset `home_sales_revised.csv` was provided via a public AWS S3 URL and contains sales data on over 25,000 home transactions including:
- Sale dates
- Bedrooms & bathrooms
- Square footage
- Sale price
- View ratings
- Construction year

# Tasks Completed

1. Loaded the dataset into a Spark DataFrame.
2. Created a temporary SQL table `home_sales`.
3. Executed SQL queries to analyze:
   - Average prices by year, bedroom count, and features
   - Home prices grouped by view rating
4. Measured query performance before and after caching.
5. Saved data to Parquet format, partitioned by `date_built`.
6. Re-ran queries using Parquet data to compare performance.
7. Cached and uncached tables to demonstrate memory optimization.
8. Verified all results using `.show()` and runtime tracking.
