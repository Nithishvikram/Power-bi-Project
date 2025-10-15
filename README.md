End-to-End Retail Analytics Dashboard

🔍 Project Overview

The Customer Sales Data Dashboard is an interactive Power BI report designed to analyze and visualize key business metrics such as Sales, Profit, Quantity, and Customer Performance across multiple dimensions.
This project aims to provide actionable insights for sales optimization and strategic decision-making.

--Developed an interactive Power BI Dashboard
--Integrated sales and customer data for comprehensive business insights.
--Built dynamic visuals for:
    Sales by Region, Product, and Customer Segment
    Profit and Discount Analysis
    Year-over-Year and Month-over-Month Growth Trends
    Top Performing Products & Customers
--Included KPIs (Revenue, Quantity Sold, Profit Margin).
--Implemented slicers and drill-throughs for detailed interactive analysis.

🧠 Key Features Implemented

Data Modeling & Relationships

Established Star Schema with Fact Table (Sales) linked to Dimension Tables (Products, Customers, Regions, and Dates).
Defined clear 1-to-Many relationships to enable accurate aggregation and filtering.

Data Transformation (Power Query)

Cleaned and standardized data using Power Query Editor.
Applied transformations like removing nulls, splitting columns, changing data types, and merging datasets.
Created custom columns for profit margin and cost analysis.

DAX (Data Analysis Expressions)

Created calculated measures for:
Total Sales = SUM(Sales[SalesAmount])
Total Profit = SUM(Sales[Profit])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
YoY Sales Growth = ( [Current Year Sales] - [Previous Year Sales] ) / [Previous Year Sales]
Average Discount = AVERAGE(Sales[Discount])

Interactive Visuals & Dashboards

Designed multi-page dashboards covering:
Sales Overview: Total Sales, Profit, Quantity, and Discount KPIs
Customer Analysis: Top & bottom performing customers
Product Insights: Category-wise and subcategory performance
Regional Analysis: Sales by Country, Region, and City
Used slicers for dynamic filtering (Region, Year, Product Category, Segment).
Integrated tooltips and drill-through pages for deeper insights.

Advanced Visuals & Design

Implemented cards, maps, bar charts, line charts, and donut visuals.
Used conditional formatting to highlight profit/loss trends.
Added custom themes and consistent color palettes for professional presentation.
Used Bookmarks & Buttons to enable page navigation and visual switching (e.g., between Sales and Profit views).

Performance Optimization

Reduced report load time using aggregations and optimized DAX queries.
Disabled auto date/time hierarchies for cleaner models.
Removed redundant columns to reduce file size.

🛠️ Tools & Techniques Used

--Microsoft Power BI Desktop
--Power Query (Data Cleaning & Transformation)
--DAX Formulas (Measure Creation & Calculations)
--Data Modeling (Star Schema)
--Interactive Visual Design
--Drill-through, Slicers, and Tooltips

🧠 Key Outcomes

--Enhanced understanding of user engagement and sales performance metrics.
--Demonstrated strong proficiency in Excel Analytics and Power BI Visualization.
--Delivered data-driven insights that can support strategic decision-making.
