# Cost & Profitability Optimization Analysis — Retail Superstore

A data analysis project identifying cost and discount inefficiencies in retail sales data using SQL, Excel, and Power BI, with actionable recommendations to improve profit margins.

## Overview

This project analyzes order-level sales data to uncover where cost and discounting practices are eroding profitability — by category, sub-category, region, and customer segment — and translates the findings into specific, actionable recommendations.

## Key Findings

- **$2.3M** in total sales generated **$286K** in profit (**12.5%** profit margin), with an average discount rate of **15.6%**
- Discounts above **20%** consistently pushed profit negative across nearly all categories
- **Furniture** had the lowest profit of all three categories despite carrying the *highest* average discount rate
- **Tables** was the only sub-category running a net loss — the clearest single fix opportunity
- Consumer segment drives the largest share of sales (**50.6%**), followed by Corporate (**30.7%**) and Home Office (**18.7%**)

## Recommendations

1. Cap or restructure discounting on Furniture — particularly Tables — where margin is already thin
2. Review pricing/discount policy for any order exceeding 20% discount, given the consistent profit drop-off past that threshold
3. Prioritize cost-efficiency review on the lowest-performing regions and sub-categories identified in the SQL analysis

## Tools Used

- **Excel** — data cleaning, KPI calculation, pivot tables, initial visualizations
- **SQL** — profitability segmentation by category, region, segment, and discount level; loss-making product identification
- **Power BI** — interactive dashboard for sales, profit, and segment breakdowns

## Repository Contents

| File | Description |
|---|---|
| `superstore_analysis.xlsx` | Cleaned dataset, KPI calculations, pivot table charts |
| `queries.sql` | SQL queries for cost driver and profitability analysis |
| `dashboard_screenshots/` | Power BI dashboard views |

## Dashboard Preview

*(screenshots go here once uploaded)*

## Live Dashboard

*(Power BI public link — add once published)*
