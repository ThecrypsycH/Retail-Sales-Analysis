# Retail Sales Analysis — 2014

## Overview
Exploratory data analysis of a retail sales dataset containing 923,371 transactions 
across 100 store locations and 105,916 products.

## Key Findings
- **Total Revenue:** $45.18M | **Gross Margin:** $18.97M | **Margin %:** 41.98%
- **Seasonality:** Sales peak in August ($6.67M) and dip in January ($3.82M)
- **Star Product:** Item 17791 generates $98,697 — 2.5x more than the next best item
- **Top Location:** Location 13 leads with $1.37M in revenue
- **Markdown Impact:** Markdown sales are less than 10% of total — not discount-dependent
- **Scenario Parity:** Actual vs Plan variance is minimal ($22M vs $23.1M)

## Tech Stack
- Python 3.10
- Pandas, Matplotlib, Seaborn
- Jupyter Notebook
- Power BI
- Excel

## Dataset
- 923,371 rows | 10 columns | Single year (2014)
- Columns: MonthID, ItemID, LocationID, ScenarioID, ReportingPeriodID, 
  GrossMarginAmount, Regular/Markdown Sales (Dollars + Units)

## Project Structure
- `Retail_Sales_Analysis.ipynb` — full analysis notebook
- `Retail_Analysis_Project.xlsx` — raw dataset

## Dashboard
[View Interactive Power BI Dashboard] (https://app.fabric.microsoft.com/links/bK5vnopljF?ctid=56c1d497-700b-49cf-8f8d-3dd6b20d522f&pbi_source=linkShare)
