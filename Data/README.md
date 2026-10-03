# Data

This folder contains the structured datasets used in the Mobile Phone Sales & Customer Analytics Power BI project.

## Dataset Structure

### Dimension Tables

* `dim_date.csv` — date and calendar attributes
* `dim_brands.csv` — mobile brand reference data
* `dim_cities.csv` — city reference data
* `dim_payment_methods.csv` — payment method reference data
* `dim_mobile_models.csv` — mobile model reference data

### Fact Tables

* `fact_mobile_sales.csv` — transaction-level mobile sales data
* `fact_sales_daily.csv` — daily aggregated sales data

## Purpose

The files are organized into dimension and fact tables to support Power BI data modeling, KPI calculation, dashboard development, and descriptive business analysis.

## Data Coverage

The transaction data contains 3,835 records covering October 9, 2021 through October 8, 2024.

## Important Note

The data supports descriptive sales analysis. It does not contain sufficient information to determine profitability, margins, marketing ROI, inventory impact, or causal drivers of sales performance.

