Pizza Sales Analytics Dashboard using SQL & Power BI
A comprehensive sales analysis project for a pizza delivery business. It covers total orders, revenue insights, pizza popularity, category-wise sales, and temporal patterns. 
Built using SQL and Power BI for end-to-end BI workflow—from querying raw data to delivering actionable visual dashboards.
# 🍕 Pizza Sales Analytics Dashboard

This repository contains an end-to-end Business Intelligence project that analyzes pizza sales data. Using **SQL** for data extraction and transformation, and **Power BI** for visualization, the project delivers business-critical insights to support strategic decisions.

---

## 🔧 Tools & Technologies:
- **SQL**: For querying, joining, aggregating data
- **Power BI**: For visualizing insights and building interactive dashboards

---

## 📂 Dataset Overview:
The dataset includes multiple tables:
- `orders`: Contains order timestamps and order IDs
- `order_details`: Line items with pizza types and quantities
- `pizzas`: Contains pricing and size of pizzas
- `pizza_types`: Contains pizza names and categories

---

## 🧠 Analysis Breakdown:

### 🟢 Basic Insights
- ✅ Total number of orders placed  
- ✅ Total revenue generated from pizza sales  
- ✅ Highest-priced pizza identified  
- ✅ Most common pizza size ordered  
- ✅ Top 5 most ordered pizza types with quantities  

### 🟡 Intermediate Insights
- 🔁 Total quantity of each **pizza category** ordered  
- 🕒 Hourly distribution of orders  
- 📊 Category-wise pizza sales distribution  
- 📅 Average number of pizzas ordered per day  
- 💸 Top 3 most ordered pizza types based on **revenue**

### 🔴 Advanced Insights
- 📉 Revenue contribution % by each pizza type  
- 📈 Cumulative revenue trend over time  
- 🔝 Top 3 revenue-generating pizzas **within each category**

---

## 📈 Dashboard Features (Power BI)
- KPI cards for total revenue, number of orders, average order size
- Revenue trends by day and hour
- Category and size filters
- Dynamic top 3 rankings and contribution pie charts
- Cumulative revenue timeline

---

## 📷 Dashboard Preview:
*(You can upload a screenshot and paste the link here)*

---

## 🗂 Files:
- `PizzaSalesDashboard.pbix`: Power BI file with all visuals and metrics
- `pizza_sales.sql`: SQL queries used in the analysis
- `pizza_sales_data/`: Contains original CSV files

---
