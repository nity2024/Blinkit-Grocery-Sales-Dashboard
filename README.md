# 🛒 Blinkit Grocery Sales Dashboard (Power BI Project)

This project is a real-time Power BI dashboard built using Blinkit grocery sales data. The aim is to analyze total sales, customer satisfaction, and inventory distribution across various dimensions such as outlet type, location, fat content, item type, and more.

---

## 📌 Project Objectives

- Analyze sales performance across outlet types and sizes
- Understand the impact of product fat content on sales
- Track KPIs like Total Sales, Average Sales, Number of Items, and Average Ratings
- Help stakeholders make data-driven decisions

---

## 📁 Dataset Description

The dataset includes multiple Excel sheets containing:

- `Sales` – Order amount, item type, fat content, outlet type
- `Outlet Info` – Outlet size, location, type, establishment year
- `Ratings` – Customer average ratings

---

## 🧠 KPIs Created

- **Total Sales** 💰  
- **Average Sales** 💵  
- **Number of Items** 📦  
- **Average Rating** ⭐  

---

## 📊 Charts and Visualizations

| Chart Title | Description | Chart Type |
|-------------|-------------|------------|
| Sales by Fat Content | Sales comparison by Low/Regular fat | Donut Chart |
| Sales by Item Type | Top-performing product types | Bar Chart |
| Fat Content by Outlet | How outlet types affect fat content sales | Stacked Column |
| Sales by Establishment Year | Trend by outlet age | Line Chart |
| Sales by Outlet Size | Comparison across Small/Medium/Large outlets | Pie Chart |
| Sales by Location | Tier-wise geographic sales distribution | Funnel Map |
| All Metrics by Outlet Type | Summary metrics across outlets | Matrix Card |

---

## 🧮 DAX Measures Used

```DAX
Total Sales = SUM(Sales[Amount])
Average Sales = AVERAGE(Sales[Amount])
No of Items = COUNT(Sales[Item ID])
Average Rating = AVERAGE(Ratings[Rating])
