# 📊 E-commerce Analytics Dashboard | Power BI Project

## 📝 Overview

This project showcases an interactive Power BI dashboard created using e-commerce sales data. The dashboard highlights key business metrics, customer behavior, sales performance, and regional trends.

The goal was to simulate a real-world e-commerce scenario and leverage Power BI to create insightful and dynamic visualizations. The entire report is powered by an Excel dataset that includes details about orders, products, categories, customers, sales amounts, and locations.

---

## 🔍 Dashboard Insights

- 📦 **Total Orders**
- 💰 **Total Sales & Profit**
- 📈 **Monthly and Daily Trends**
- 🛒 **Sales by Category and Sub-Category**
- 🌍 **Sales by Country and City**
- 👤 **Top Customers**
- 🧮 **Average Order Value & Profit Margins**

---

## 📂 Files Included

- `ecommerce-dashboard.pbix` → Power BI file with full report  
- `ecommerce-sales.xlsx` → Raw Excel dataset  
- `/visuals/` → Dashboard screenshots  

---

## 🧠 Skills Applied

- Data import and transformation in Power BI  
- Data modeling using relationships and hierarchies  
- Creating DAX measures and calculated columns  
- Designing interactive visuals with slicers and filters  
- Clean and intuitive dashboard design  

---

## 📸 Dashboard Screenshots
![Dashboard Preview](https://github.com/user-attachments/assets/a29602ac-b69a-4c1c-8465-330d578274d2)

![Dashboard Screenshot](https://github.com/user-attachments/assets/579d07f6-9aa6-4f8b-adc2-478585d64c0a)



---

## ⚙️ Tools & Features

- **Tool:** Microsoft Power BI  
- **Data Sources:** Excel (.xlsx), CSV files  
- **Features Used:**  
  - Slicers and filters  
  - Dynamic DAX measures  
  - Interactive charts and KPIs  
  - Responsive layout for business storytelling  

---

## 📈 Key DAX Measures

```DAX
Total Sales = SUM(Sales[SalesAmount])
Total Orders = COUNT(Sales[OrderID])
Average Order Value = DIVIDE([Total Sales], [Total Orders])
Profit Margin = DIVIDE([Total Profit], [Total Sales])
## Use Case

This project is ideal for showcasing:

- Relational database design  
- SQL query building  
- Analytical thinking in a hotel management context
