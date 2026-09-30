# Beco-Analysis
# BECO Data Analyst Executive -Sales Analytics Case Study

## Project Overview

This project was completed as part of the BECO Data Analyst Executive assessment.

The objective was to analyze sales data, identify business trends, evaluate product and SKU performance, build analytical dashboards, and generate sales forecasts to support data-driven business decisions.

## Business Objectives

The analysis focuses on:

* Understanding overall sales performance
* Identifying top-performing products and SKUs
* Analyzing sales trends over time
* Evaluating Gross Profit (GP) and profitability
* Identifying underperforming products
* Building an interactive Power BI dashboard
* Creating SQL-based analytical queries
* Developing a Python-based sales forecasting model
* Providing actionable business insights

## Tools & Technologies

* SQL / Snowflake
* Python
* Pandas
* NumPy
* Matplotlib
* Power BI
* DAX
* Microsoft Excel
* GitHub

## Project Structure

```text
BECO-Data-Analyst-Submission/
│
├── data/
│   ├── sales_data_cleaned.csv
│   └── sku_master.csv
│
├── excel/
│   └── BECO_Sales_Analysis.xlsx
│
├── sql/
│   └── beco_sales_analysis.sql
│
├── python/
│   ├── sales_forecasting.py
│   └── forecast_chart.png
│
├── powerbi/
│   ├── BECO_Sales_Dashboard.pbix
│   └── dashboard_screenshots/
│
├── analysis/
│   └── business_insights.pdf
│
└── requirements.txt
```

## Data Analysis

The sales data was cleaned and validated before analysis.

Key activities included:

* Data type validation
* Missing-value checks
* Duplicate checks
* SKU validation
* Sales and quantity validation
* Product-level aggregation
* Monthly sales analysis
* Gross Profit analysis
* Margin analysis

## SQL Analysis

SQL was used to perform analytical queries including:

* Total sales
* Sales by SKU
* Sales by product/category
* Monthly sales trends
* Gross Profit analysis
* Product contribution
* Ranking of products
* Identification of high- and low-performing SKUs

The SQL scripts are available in:

`sql/beco_sales_analysis.sql`

## Python Analysis

Python and Pandas were used for:

* Data preparation
* Data validation
* Aggregation
* Time-series analysis
* Sales forecasting
* Visualization

The forecasting implementation is available in:

`python/sales_forecasting.py`

## Power BI Dashboard

The Power BI dashboard provides an interactive view of sales performance.

### Dashboard sections

* Executive Sales Overview
* Product/SKU Analysis
* Sales Trend
* Gross Profit and Margin
* Forecast Analysis

Dashboard screenshots are available in:

`powerbi/dashboard_screenshots/`

## Key Business Insights

The analysis was used to identify:

1. Products contributing significantly to total sales.
2. Products with relatively low sales contribution.
3. Monthly sales trends and changes over time.
4. Differences between revenue and profitability performance.
5. Potential products requiring further business investigation.
6. Forecasted sales trends that can support planning and inventory decisions.

## Forecasting

Historical sales data was aggregated at the monthly level and used to generate a forward-looking sales forecast.

The forecast can support:

* Demand planning
* Inventory planning
* Sales target setting
* Business capacity planning

## Business Recommendations

Based on the analysis, management can use the dashboard and forecast to:

* Monitor high-performing SKUs
* Investigate low-performing products
* Track GP and margin alongside revenue
* Review monthly sales trends
* Improve inventory planning
* Use forecasted demand for future planning

## Deliverables

| Deliverable            | Location    |
| ---------------------- | ----------- |
| Excel Analysis         | `excel/`    |
| SQL Queries            | `sql/`      |
| Python Forecasting     | `python/`   |
| Power BI Dashboard     | `powerbi/`  |
| Forecast Visualization | `python/`   |
| Business Insights      | `analysis/` |

## Author

**Sakshi Walke**

Business Analyst | Data Analyst

Skills: SQL | Power BI | Python | Excel | Data Analysis | Business Analysis

BECO-Data-Analyst-Submission/
│
├── README.md
│
├── data/
│   ├── sales_data_cleaned.csv
│   └── sku_master.csv
│
├── excel/
│   └── BECO_Sales_Analysis.xlsx
│
├── sql/
│   └── beco_sales_analysis.sql
│
├── python/
│   ├── sales_forecasting.py
│   └── forecast_chart.png
│
├── powerbi/
│   ├── BECO_Sales_Dashboard.pbix
│   └── dashboard_screenshots/
│       ├── overview.png
│       ├── product_analysis.png
│       └── regional_analysis.png
│
├── analysis/
│   └── business_insights.pdf
│
└── requirements.txt
