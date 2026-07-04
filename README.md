# 🍔 McDonald's Sales Analysis Dashboard (Excel)

## 📌 Overview

This project showcases an interactive **Microsoft Excel dashboard** designed to analyze McDonald's sales transactions. By combining menu and order data, the dashboard provides valuable insights into sales performance, customer purchasing behavior, product popularity, and ordering trends. It enables business users to monitor key performance indicators (KPIs) and make informed, data-driven decisions.

## 🎯 Objectives

- Analyze overall sales and order performance.
- Identify top-selling menu categories and items.
- Compare weekday and weekend sales performance.
- Evaluate customer ordering patterns across different time periods.
- Monitor daily and monthly sales trends.

## 📊 Dashboard Features

### KPI Cards
- Total Sales
- Total Orders
- Average Order Value (AOV)
- Total Quantity Sold

### Sales Analysis
- Monthly Sales Trend
- Daily Order Trend
- Sales by Menu Category

### Product Performance
- Top 5 Best-Selling Categories
- Top 5 Premium Menu Items
- Top 5 Budget-Friendly Menu Items

### Customer Behavior
- Order Activity by Time Period (Morning, Afternoon, Evening, Night)
- Weekday vs. Weekend Sales Comparison

### Interactive Filters
- Category
- Month
- Day

## 🧹 Data Preparation

The dataset was cleaned and transformed using **Power Query (M)** by:

- Removing blank and unnecessary records.
- Handling null values.
- Standardizing data types.
- Formatting prices as currency.
- Merging menu and order datasets using **menu_item_id**.
- Creating calculated fields, including:
  - Day Name
  - Workday Type (Weekday/Weekend)
  - Time Period (Morning, Afternoon, Evening, Night)

## Dashboard preview
<img width="848" height="357" alt="image" src="https://github.com/user-attachments/assets/5182e83e-c170-4b98-9b3a-88252775e73c" />

## 🛠 Tools & Technologies

- Microsoft Excel
- Power Query (M)
- Pivot Tables
- Pivot Charts
- Slicers
- Data Modeling

## 📈 Key Insights

- 🍔 **Burgers** generated the highest sales among all menu categories.
- 🌤️ **Afternoon** recorded the highest order activity.
- 📅 **Weekday sales** consistently outperformed weekend sales.
- 💰 Premium and budget-friendly menu items were identified based on pricing.
- 📊 Sales performance was successfully analyzed across daily, monthly, and category-level dimensions.

## 🚀 Project Outcome

This dashboard transforms raw transactional data into meaningful business insights through interactive visualizations and dynamic filtering. It serves as an effective business intelligence solution for tracking sales performance, understanding customer behavior, and supporting strategic decision-making.
