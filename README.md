# 📊 Retail Sales Analysis Dashboard

![Retail Sales Dashboard](Retail_Dashboard.png)

## Overview
This project analyzes retail sales data to uncover insights on revenue, profit, and performance trends across product categories, customer segments, regions, and time periods. Data cleaning and exploratory analysis were done in **Microsoft Excel**, and an interactive dashboard was built in **Power BI**.

## Objective
To identify key sales and profit drivers across categories, segments, and regions, and to track sales performance over time in order to support data-driven business decisions.

## Dashboard Highlights
- **4 KPI cards:** Total Sales (13M), Total Profit (1.47M), Total Quantity (178K), Profit Margin (11.62%)
- **Sales Trend Over Time:** monthly sales line chart showing seasonal patterns
- **Sales by Category:** donut chart for Technology, Furniture, and Office Supplies
- **Sales by Segment:** donut chart for Consumer, Corporate, and Home Office
- **Sales by Region:** horizontal bar chart comparing regional performance
- **Region Slicer:** interactive filter to explore any region

## Tools & Skills Used
- **Microsoft Excel:** Data cleaning, Pivot Tables, formulas, chart creation
- **Power BI:** Data modeling, DAX measures (Profit Margin), interactive visuals, slicers, custom layout and design

## Dataset
Global Superstore Sales dataset with over 51,000 records covering orders, products, sales, profit, quantity, and shipping across multiple regions.

## Key Steps
1. Cleaned and formatted raw sales data in Excel (removed duplicates, fixed date formats)
2. Built Pivot Tables to summarize sales and profit by category, region, and time
3. Imported the data into Power BI and removed blank rows in Power Query
4. Created a DAX measure for Profit Margin
5. Designed an interactive, multi-visual dashboard with a custom layout

## Key Insights
- Total sales of 13M generated a profit of 1.47M, a profit margin of 11.62%
- Technology is the top category, contributing about 37.5% of total sales
- The Consumer segment drives about 51.5% of sales, more than Corporate and Home Office combined
- Central is the top-performing region with roughly 2.8M in sales, well ahead of South and North
- Sales rise toward the end of the year, showing a clear seasonal peak

## Files in this Repository
- `superstore_working.xlsx`: Cleaned dataset with pivot tables and Excel analysis
- `Retail_Sales_Analysis_Dashboard.pbix`: Power BI dashboard file
- `Retail_Dashboard.png`: Dashboard screenshot
