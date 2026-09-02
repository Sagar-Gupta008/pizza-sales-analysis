# 🍕 Pizza Sales Analysis | SQL & Power BI

## 📌 Project Overview

This project analyzes pizza sales data to uncover key business insights related to revenue, order patterns, product performance, pizza categories, sizes, and customer purchasing trends.

The project combines **SQL Server** for business analysis with **Power BI** for interactive data visualization. SQL was used to calculate KPIs and answer business questions, while Power BI was used to transform the analytical results into an interactive two-page sales dashboard.

---

## 🎯 Business Objective

The objective of this project is to analyze transactional pizza sales data and identify patterns that can support better sales and product decisions.

The analysis focuses on questions such as:

- What are the overall revenue and order performance?
- Which days and months generate the highest order volumes?
- Which pizza categories contribute the most to sales?
- Which pizza sizes generate the largest share of revenue?
- Which pizzas are the strongest performers by revenue, quantity, and orders?
- Which pizzas consistently underperform?
- What purchasing patterns can be identified from the sales data?

---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Revenue** | **817.86K** |
| **Average Order Value** | **38.31** |
| **Total Pizzas Sold** | **49,574** |
| **Total Orders** | **21,350** |
| **Average Pizzas per Order** | **2.32** |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **SQL Server** | Data querying and business analysis |
| **SSMS** | Writing and executing SQL queries |
| **Power BI** | Interactive dashboard development |
| **Power Query** | Data preparation and transformation |
| **DAX** | KPI calculations and dashboard measures |

---

## 🔄 Analysis Workflow

```text
Pizza Sales Dataset
        ↓
Data Preparation
        ↓
SQL Server Analysis
        ↓
KPI Calculation
        ↓
Sales & Product Analysis
        ↓
Power BI Dashboard
        ↓
Business Insights
```
---
## 🧠 SQL Business Analysis

SQL Server was used to calculate business KPIs and analyze sales performance across time, pizza categories, sizes, and individual products.

### 🔹 KPI Analysis

- Total Revenue
- Average Order Value
- Total Pizzas Sold
- Total Orders
- Average Pizzas per Order

### 🔹 Sales Trend Analysis

- Analyzed daily order trends to identify the busiest days
- Analyzed monthly order trends to identify peak and low-demand periods
- Compared order activity across different days and months

### 🔹 Product & Category Analysis

- Calculated percentage contribution of each pizza category to total sales
- Calculated percentage contribution of each pizza size to total sales
- Analyzed total pizzas sold across categories

### 🔹 Best & Worst Seller Analysis

Pizzas were ranked based on three key performance measures:

- Revenue generated
- Total quantity sold
- Total number of orders

Both the **Top 5** and **Bottom 5** pizzas were analyzed to identify high-performing and underperforming products.

### 🧩 SQL Concepts Demonstrated

`SUM()` • `COUNT()` • `DISTINCT` • `GROUP BY` • `ORDER BY` • `TOP` • `DATENAME()` • `ROUND()` • Aggregations • Subqueries
---

## 💡 Key Business Insights

### 📅 Order Trends

- Order activity was highest toward the end of the week, with **Friday recording the highest order volume**.
- The dashboard identifies **Friday and Saturday evenings** as particularly busy periods.
- **July recorded the highest monthly order volume with 1,935 orders**.
- January was also among the strongest months with **1,845 orders**.

### 🍕 Category Performance

- The **Classic** category generated the largest share of sales at approximately **26.91%**.
- Supreme contributed approximately **25.46%**, followed by Chicken at **23.96%** and Veggie at **23.68%**.
- Classic also recorded the highest pizza quantity sold, with **14,888 pizzas**.

### 📏 Pizza Size Performance

- **Large pizzas dominated sales contribution at approximately 45.89%**.
- Medium pizzas contributed approximately **30.49%**.
- Small pizzas accounted for approximately **21.77%**.
- XL and XXL pizzas represented only a small proportion of overall sales.

### 🏆 Best Sellers

- **The Thai Chicken Pizza** generated the highest revenue.
- **The Classic Deluxe Pizza** recorded the highest quantity sold.
- The Classic Deluxe Pizza also generated the highest number of orders.

### 📉 Worst Seller

- **The Brie Carre Pizza** was the weakest-performing product across all three major measures:
  - Revenue
  - Quantity sold
  - Total orders

This suggests that the product consistently underperformed compared with the rest of the pizza portfolio.
