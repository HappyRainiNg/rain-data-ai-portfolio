# Task 002 — Pandas Cleaning Practice

Date: 2026-07-01

## Goal

This task is a simple pandas data cleaning practice using mock seafood sales data for Eat Well.

The goal is to build a small portfolio artifact that shows how to:

- read a CSV file
- inspect missing values
- clean text columns
- convert dates
- calculate sales amount
- create summary tables
- export cleaned summary results

## Dataset

The sample dataset is stored in:

`data/eatwell_sales_sample.csv`

Main columns:

- order_id
- order_date
- customer_type
- product
- category
- quantity_kg
- unit_price_hkd
- district
- payment_method

## Cleaning Steps

The notebook will clean:

- product names
- district names
- payment method format
- order date format

It will also create:

- month
- sales_amount_hkd

## Outputs

The main output file is:

`outputs/product_sales_summary.csv`

Additional possible outputs:

- monthly_sales_summary.csv
- district_sales_summary.csv
- total_sales_by_product.png

## What I Practiced

In this task, I practiced using pandas for basic data cleaning, grouping, aggregation, and exporting results.
