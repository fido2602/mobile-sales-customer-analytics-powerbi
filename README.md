# Mobile Phone Sales & Customer Analytics — Power BI

## Project Overview
An interactive Power BI dashboard analyzing mobile phone sales transactions across brands, models, cities, payment methods, customer ratings, and time.

## Business Objective
Turn transaction-level mobile sales data into a management-friendly view of revenue, volume, product performance, geographic concentration, payment behavior, customer ratings, and time patterns.

## Key KPIs
| KPI | Result |
|---|---:|
| Total Sales | $769,204,987.97 |
| Total Units Sold | 19,150 |
| Transactions | 3,835 |
| Average Price per Unit | $40,114.04 |
| Average Sales per Transaction | $200,574.96 |

## Dashboard Views
- KPI summary
- Sales by city
- Units sold by month/day
- Customer ratings
- Payment method mix
- Sales by mobile model
- Sales by day name
- Brand-level performance
- Interactive filters for mobile model, payment method, brand, day name, and date/month context

## Data
The source workbook contains 3,835 transaction records covering 2021-10-09 through 2024-10-08.

The portfolio package restructures the source into a simple analytical model:
- `dim_date.csv`
- `dim_brands.csv`
- `dim_cities.csv`
- `dim_payment_methods.csv`
- `dim_mobile_models.csv`
- `fact_mobile_sales.csv`
- `fact_sales_daily.csv`

## Core Calculation
`Total Sales = Units Sold × Price Per Unit`

## Analytical Findings
- Apple has the highest calculated sales among the five brands.
- iPhone SE is the highest-sales mobile model in the supplied data.
- Delhi is the highest-sales city.
- UPI is the largest payment method by calculated sales in the supplied records.
- Rating 5 is the largest customer-rating group.
- The dataset contains partial 2021 and 2024 coverage, so full-year comparisons should be made carefully.

## Tools
- Power BI
- Excel
- Data modeling
- KPI design
- Descriptive analytics
- Business reporting

## Files
- `Dashboard.pdf` — dashboard export/image presentation
- `Project_Details.docx` — project overview and documentation
- `Project_Report.pdf` — detailed analytical report
- `metrics_list.xlsx` — metric definitions and business meaning
- dimension and fact CSVs — portfolio-ready analytical data
- `meta_data_mobile_sales.txt` — data dictionary and modeling notes

## Important Limitation
This is descriptive transaction analysis. The dataset does not provide cost, margin, promotion, inventory, marketing-spend, or causal-driver fields, so the project should not claim profitability or causal conclusions.
