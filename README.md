📄 Power BI Project Report – Blinkit Grocery Sales Dashboard
1. Project Title
Blinkit Grocery Sales Analysis Using Power BI

2. Objective
To perform a comprehensive sales analysis for Blinkit grocery data, covering sales performance, customer behavior, and outlet-specific metrics to help decision-making through interactive visualizations in Power BI.

3. Tools Used
Power BI Desktop

DAX (Data Analysis Expressions)

Power Query Editor

4. Project Steps Followed
According to the project flow shown in your screenshot:

Requirement Gathering – Understood business need and KPIs

Data Walkthrough – Reviewed available data columns and formats

Data Connection – Imported Excel dataset

Data Cleaning – Removed nulls, changed datatypes, standardized text

Data Modeling – Created relationships between tables using keys

Data Processing – Created a Date table and cleaned joins

DAX Calculations – Built calculated columns and custom measures

Dashboard Layouting – Designed layout for filters, KPIs, visuals

Chart Development – Added various visual types based on need

Dashboard Development – Combined all visuals in a single interactive page

Insights Generation – Derived patterns and trends from data

5. Business Requirements Addressed
✅ KPI Metrics Required:
Total Sales – Total revenue from all sales

Average Sales – Revenue per transaction

Number of Items – Total units sold

Average Rating – Customer satisfaction score

✅ Chart Requirements & Objectives:
S.No	Chart Title	Objective	Chart Type
1	Total Sales by Fat Content	Analyze impact of fat content	Donut Chart
2	Total Sales by Item Type	Identify top item types	Bar Chart
3	Fat Content by Outlet	Compare fat content across outlets	Stacked Column
4	Total Sales by Outlet Establishment	Analyze performance by outlet age/type	Line Chart
5	Sales by Outlet Size	Relation between outlet size & sales	Donut/Pie Chart
6	Sales by Outlet Location	Geo distribution of sales	Funnel Map
7	All KPIs by Outlet Type	Overall metrics by outlet type	Matrix Table

6. DAX Measures Used
Measure Name	Description
Total Sales	SUM of all sales amount
Average Sales	Total Sales ÷ Total Orders
No of Items	COUNT of product items
Average Rating	AVERAGE of customer rating column

7. Visualizations Included
KPI Cards (Top): Total Sales, Avg Sales, Items, Rating

Slicers (Left Panel): Outlet Location, Size, Item Type

Donut Chart: Fat content breakdown

Bar Chart: Sales by Item Type

Line Chart: Sales trend by establishment year

Funnel Map: Outlet location sales

Matrix Table: All metrics by outlet type (last chart)

8. Key Insights
🥇 Supermarket Type1 had the highest sales of $279.66K

🍴 Fruits and Veggies sold the most across item types

🟡 Low Fat items dominated in both quantity and sales

🏙️ Tier 3 Locations had higher total sales than Tier 1 and 2

🏢 Medium Outlet Sizes performed better than others

📈 Sales peaked around 2018 in outlet establishment timeline

9. Conclusion
The Power BI dashboard delivers a complete view of Blinkit's grocery sales based on multiple dimensions like fat content, item type, outlet type, and location. It enables decision-makers to identify strong areas, underperforming segments, and take action to improve future outcomes.

