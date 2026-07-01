# Task 002 — Pandas Cleaning Practice

Date: 2026-07-01

## Goal

Practice using Python pandas to clean and summarize a small seafood sales dataset.

## Dataset

This task uses a mock Eat Well seafood sales dataset with columns such as:

- order_id
- order_date
- customer_type
- product
- category
- quantity_kg
- unit_price_hkd
- district
- payment_method

## Steps

1. Load the CSV file using pandas.
2. Inspect the dataset using `head()`, `info()`, `describe()`, `isna().sum()`, and `duplicated().sum()`.
3. Clean text columns such as product, district, and payment method.
4. Convert order dates to datetime format.
5. Create new columns:
   - month
   - sales_amount_hkd
6. Build summary tables by:
   - product
   - month
   - district
7. Export cleaned summary tables to CSV files.
8. Create a bar chart showing total sales by product.

## Outputs

- `outputs/product_sales_summary.csv`
- `outputs/monthly_sales_summary.csv`
- `outputs/district_sales_summary.csv`
- `outputs/total_sales_by_product.png`

## Key Learning

This task helped me practice basic data cleaning, feature engineering, groupby aggregation, and exporting analysis results using pandas.
