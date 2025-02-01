# Talabat SQL Project

This project is designed to analyze and extract valuable insights from Talabat's order data using SQL queries. The goal of this project is to identify key patterns related to vendors, delivery times, successful orders, and other important metrics that can be useful for decision-making.

## Project Overview

The project involves running SQL queries on a dataset to extract information and identify trends, including:
- Vendor performance
- Average delivery times
- Successful order rates
- Other data-driven insights

## Contents

- **talabat-SQL.ipynb**: Jupyter notebook containing the SQL queries and the steps to perform the analysis.
- **Data**: The dataset includes tables such as `fct_order` and `dim_vendor` that are used to extract the insights.

## Key Queries

1. **Average Delivery Times**:
   - Analyzes vendors based on their average delivery time, helping to identify vendors with the fastest delivery.

2. **Successful Orders**:
   - Filters vendors with more than 90% successful orders.

3. **Short Delivery Times**:
   - Identifies vendors whose orders have the shortest average delivery times.

4. **Vendors with High Success Rates**:
   - Identifies vendors with the highest success rates of delivering orders without issues.

## Requirements

Make sure you have the following installed to run the SQL analysis:

- Python 3.x
- MySQL or compatible database with the necessary data tables.
- `pandas` library for handling the SQL query results.

You can install the necessary Python libraries with:

```bash
pip install pandas mysql-connector
