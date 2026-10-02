# E-Commerce-Sales-Dashboard
Power BI dashboard analyzing e-commerce sales data
# E-Commerce Sales Dashboard

## Project Overview
Built an interactive Power BI dashboard to analyze e-commerce sales data.

## Tools Used
- Power BI Desktop
- Power Query
- DAX

## Data Model
- Star Schema with Orders (Fact) + Customers, Products, Dates (Dimensions)
- 3 Active Relationships

## DAX Measures
- Total Sales = SUM(Orders[Amount])
- Total Profit = SUM(Orders[Profit])
- Total Quantity = SUM(Orders[Quantity])
- Total Orders = COUNT(Orders[OrderID])

## Visuals
- 4 KPI Cards (Sales, Profit, Quantity, Orders)
- Bar Chart: Sales by Category
- Pie Chart: Sales by State
- Line Chart: Sales by Month
- Table: Top Customers
- Slicer: Category Filter

## Key Insights
- [Add 2-3 insights you found]

## Files
- E-Commerce_Sales_Dashboard.pbix
- ecommerce_dashboard.png

## How to Use
1. Open the .pbix file in Power BI Desktop
2. Click on any slicer to filter
3. Explore the charts
<img width="938" height="522" alt="image" src="https://github.com/user-attachments/assets/68dfc46f-f89c-435e-9a42-0153b2b2e629" />
