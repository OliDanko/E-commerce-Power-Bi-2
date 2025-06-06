# 📊 E-commerce Analytics Dashboard | Power BI Project

## 📝 Overview

This project presents an interactive Power BI dashboard based on e-commerce sales data. The dashboard highlights key business metrics, customer behavior, sales performance, and regional trends.

The goal of this project was to simulate a real-world e-commerce dataset and use Power BI to create meaningful and dynamic visualizations. The entire report was built using Excel as the data source, and the dataset includes details about orders, products, categories, customers, sales amounts, and locations.

---

## 🔍 Dashboard Insights

- 📦 **Total Orders**
- 💰 **Total Sales & Profit**
- 📈 **Monthly and Daily Trends**
- 🛒 **Sales by Category and Sub-Category**
- 🌍 **Sales by Country and City**
- 👤 **Top Customers**
- 🧮 **Average Order Value and Profit Margins**

---

## 📂 Files Included

- `ecommerce-dashboard.pbix` → Power BI file with complete report  
- `ecommerce-sales.xlsx` → Raw Excel data  
- `/visuals/` → Screenshots of dashboard visuals  

---

## 🧠 Skills Applied

- Data import and cleaning in Power BI  
- Data modeling with relationships  
- DAX measures and calculated columns  
- Interactive visuals with slicers and filters  
- Dashboard layout and design for user-friendly navigation  

---

## 📸 Dashboard Screenshots

### 💡 KPI Overview  
![KPI Overview](visuals/kpi-overview.png)

### 📍 Sales by Region  
![Sales Map](visuals/sales-map.png)

### 📆 Monthly Trends  
![Monthly Sales](visuals/monthly-trends.png)

---

## ⚙️ Tools Used

- **Microsoft Power BI**
- **Microsoft Excel**
- **DAX**

---

## 📈 Key DAX Measures Used

```DAX
Total Sales = SUM(Sales[SalesAmount])
Average Order Value = [Total Sales] / [Total Orders]
Profit Margin = DIVIDE([Total Profit], [Total Sales])

