# Overview

This project presents an interactive Excel dashboard built to analyze McDonald's sales transactions. It combines menu and order data to identify sales trends, customer purchasing behavior, category performance, and peak ordering periods. The dashboard enables business users to monitor key performance metrics and make data-driven decisions.

# Objectives
Analyze overall sales and order performance.
Identify top-selling menu categories and items.
Compare weekday and weekend sales.
Evaluate customer ordering patterns across different time periods.
Track monthly and daily sales trends.
# Dashboard Features
KPI Cards: Total Sales, Total Orders, Average Order Value, and Quantity Sold.
Monthly Sales Trend Analysis.
Daily Order Trend Analysis.
Sales by Menu Category.
Top 5 Best-Selling Categories.
Top 5 Premium Menu Items.
Top 5 Budget-Friendly Items.
Order Activity by Time Period (Morning, Afternoon, Evening, Night).
Weekday vs. Weekend Sales Comparison.
Interactive slicers for Category, Day, and Month filtering.
# Data Preparation

Data was cleaned and transformed using Power Query (M):

Removed blank and unnecessary records.
Handled null values.
Standardized data types.
Formatted prices as currency.
Merged menu and order datasets using menu_item_id.
Created calculated fields:
Day Name
Workday Type
Time Period (Morning, Afternoon, Evening, Night)
 # Tools Used
Microsoft Excel
Power Query (M)
Pivot Tables & Pivot Charts
Slicers
Data Modeling
 # Key Insights
Burgers generated the highest sales among all categories.
Afternoon recorded the highest order activity.
Weekday sales significantly exceeded weekend sales.
Premium and budget-friendly menu items were identified based on price.
Sales trends were analyzed across daily, monthly, and category levels.
