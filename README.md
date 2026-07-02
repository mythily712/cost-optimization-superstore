# Retail Profitability & Discount Optimization Intelligence System

A data analysis project identifying cost and discount inefficiencies in retail sales data using SQL, Excel, and Power BI, with actionable recommendations to improve profit margins.

## Executive Summary

This project identifies key profitability leaks in a retail superstore by analyzing sales, cost, and discount structures. The analysis reveals that discounting strategy and product mix are the primary drivers of margin erosion. Strategic optimization of pricing thresholds and product portfolio can significantly improve overall business profitability.

## Overview

This project simulates a retail business performance audit aimed at identifying revenue leakage, discount inefficiencies, and low-margin product segments. The goal is to transform raw sales data into actionable business decisions that improve overall profitability and pricing strategy.

## Key Findings

- **$2.3M** in total sales generated **$286K** in profit (**12.5%** profit margin), with an average discount rate of **15.6%**
- Discounts above **20%** consistently lead to negative margin contribution, indicating a critical threshold for discount policy optimization.
- **Furniture** category shows structurally weak profitability due to **high discount** dependency and should be reviewed for pricing and cost restructuring.
- **Tables** sub-category is a persistent **loss-making** segment and should be considered for either pricing correction,    supplier renegotiation, or product discontinuation.
- Consumer segment drives the largest share of sales (**50.6%**), followed by Corporate (**30.7%**) and Home Office (**18.7%**)

## Business Impact Simulation 
Based on the analysis, implementing discount caps and restructuring loss-making sub-categories could potentially improve profit margins and reduce revenue leakage across underperforming segments.

## Recommendations

1. **Pricing Strategy Optimization**
  - Implement discount threshold policy (>20% flagged for approval)
  - Introduce dynamic discounting for low-margin categories
2. **Product Portfolio Optimization**
  - Review and potentially discontinue loss-making sub-category (Tables)
  - Reallocate focus to high-margin SKUs within Furniture category
3. **Regional Performance Strategy**
  - Investigate regional underperformance drivers (logistics vs demand mismatch)

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
