# Mobile Phone Sales & Customer Analytics — Power BI

## Project Overview

An interactive Power BI dashboard analyzing mobile phone sales transactions across brands, models, cities, payment methods, customer ratings, and time.

This project demonstrates an end-to-end business analytics workflow: structuring transaction-level data, building an analytical data model, defining business KPIs, creating an interactive dashboard, and translating descriptive results into business insights.

## Business Objective

Turn transaction-level mobile sales data into a management-friendly view of:

* Revenue and sales volume
* Product and brand performance
* Geographic concentration
* Payment behavior
* Customer rating distribution
* Time-based sales patterns

## Key KPIs

| **KPI**                       |      **Result** |
| ----------------------------- | --------------: |
| Total Sales                   | $769,204,987.97 |
| Total Units Sold              |          19,150 |
| Transactions                  |           3,835 |
| Average Price per Unit        |      $40,114.04 |
| Average Sales per Transaction |     $200,574.96 |

## Dashboard Views

The Power BI dashboard includes:

* KPI summary
* Sales by city
* Units sold by month and day
* Customer ratings
* Payment method mix
* Sales by mobile model
* Sales by day name
* Brand-level performance
* Interactive filters for mobile model, payment method, brand, day name, and date/month context

## Data

The source workbook contains 3,835 transaction records covering October 9, 2021 through October 8, 2024.

The portfolio package restructures the source into a simple analytical model consisting of:

* [`dim_date.csv`](Data/dim_date.csv)
* [`dim_brands.csv`](Data/dim_brands.csv)
* [`dim_cities.csv`](Data/dim_cities.csv)
* [`dim_payment_methods.csv`](Data/dim_payment_methods.csv)
* [`dim_mobile_models.csv`](Data/dim_mobile_models.csv)
* [`fact_mobile_sales.csv`](Data/fact_mobile_sales.csv)
* [`fact_sales_daily.csv`](Data/fact_sales_daily.csv)

[**View all project data files →**](Data/)

## Core Calculation

**Total Sales = Units Sold × Price Per Unit**

The project uses this calculation as the primary sales measure for the descriptive analysis.

## Analytical Findings

The analysis identified several notable patterns in the supplied transaction data:

* **Apple** has the highest calculated sales among the five brands.
* **iPhone SE** is the highest-sales mobile model in the supplied data.
* **Delhi** is the highest-sales city.
* **UPI** represents the largest payment method by calculated sales in the supplied records.
* **Rating 5** is the largest customer-rating group.
* The dataset contains partial coverage for 2021 and 2024, so full-year comparisons should be interpreted carefully.

These findings describe patterns in the available transaction data; they should not be interpreted as causal explanations for performance.

## Tools & Skills

* Power BI
* Excel
* Data modeling
* KPI design
* Descriptive analytics
* Business reporting
* Data visualization
* Business insight generation

## Project Files

* [`Dashboard.pdf`](Dashboard.pdf) — exported Power BI dashboard
* [`Project_Details.docx`](Project_Details.docx) — project overview and documentation
* [`Project_Report.pdf`](Project_Report.pdf) — detailed analytical report
* [`metrics_list.xlsx`](metrics_list.xlsx) — metric definitions and business meaning
* [`Data/`](Data/) — portfolio-ready dimension and fact CSV files
* [`meta_data_mobile_sales.txt`](meta_data_mobile_sales.txt) — data dictionary and modeling notes
* [source_dataset.xlsx](source_dataset.xlsx) — original source dataset used for the analysis

## Important Limitation

This is a **descriptive transaction analysis**.

The dataset does not provide cost, margin, promotion, inventory, marketing-spend, or causal-driver fields. Therefore, the project does **not** claim profitability, ROI, customer lifetime value, or causal explanations for observed sales patterns.

The findings should be interpreted as descriptive evidence from the supplied transaction records rather than as proof of why performance occurred.
