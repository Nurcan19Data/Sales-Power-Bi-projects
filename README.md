# Sales Dashboard - Power BI Analysis

This repository contains a Sales Dashboard created with Power BI, providing visual insights and key metrics to help with sales monitoring, performance analysis, and decision-making.

## Project Overview

The Sales Dashboard is designed to offer a clear analysis of sales-related data across two report pages, including:

* **Sales and Profit KPIs:** Total Sales, Total Profit and Order Quantity, with year-over-year (YoY %) comparison against the previous year.
* **Sales Trends:** Monthly sales trend and weekly sales to track performance over time.
* **Product Analysis:** Top 10 products, sales by brand and by product category.
* **Regional Analysis:** Sales distribution across states, shown on an interactive map.
* **Channel Analysis:** Sales and profit breakdown by sales channel.
* **Promotion Analysis:** Total sales by promotion name to compare promotion performance.

The dashboard allows users to filter and drill down into various metrics to better understand sales trends and what drives them.

## Dashboard Pages

1. **Sales Overview:** KPI cards, monthly and weekly trends, Top 10 products, brand and category breakdowns.
2. **Regional Analysis:** Sales by state (map), sales by promotion, sales and profit by channel.

## Features

* Interactive charts and graphs to visualize sales, profit and order quantity.
* Ability to filter data by date, year, product category or state using slicers.
* Year-over-year comparison for both sales and profit.
* Page navigation between the Sales Overview and Regional Analysis pages.

## Data Model

The report uses a star schema built around a sales fact table (`Sales_Data`), connected to dimension tables: `Sales_Product`, `Sales_Product_Sub_Cat`, `Sales_Channel`, `Sales_Promotion`, `Sales_State` and `Dates`. Calculations are stored in a separate `Measures_` table.

**Key measures:** Total Sales, Total Profit, Sales_LY, Profit_LY, Sales_YoY%, Profit_YoY%.

## Tools Used

* Power BI Desktop
* DAX

