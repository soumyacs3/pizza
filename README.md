# 🍕 Pizza Sales Analysis

### 📊 Data Analytics Project using Python (Pandas, NumPy, Matplotlib, Seaborn)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-green)

---

## 📘 Project Overview

The **Pizza Sales Analysis** project aims to analyze sales data from a pizza restaurant to uncover key business insights such as top-selling pizzas, revenue trends, and customer preferences.  
This analysis provides **data-driven recommendations** for inventory planning, marketing strategy, and overall business optimization.

---

## 🧠 Objectives

- Identify **total revenue, orders, and pizzas sold**
- Analyze **daily and weekly sales patterns**
- Determine the **top-selling pizzas and categories**
- Evaluate **pizza size performance**
- Visualize key trends using **Matplotlib** and **Seaborn**

---

## 🧰 Technology Stack

| Component | Technology / Library | Purpose |
|------------|----------------------|----------|
| **Programming Language** | Python | Data analysis and processing |
| **Libraries** | Pandas, NumPy | Data manipulation and cleaning |
| **Visualization** | Matplotlib, Seaborn | Data visualization and trend analysis |
| **Environment** | Jupyter Notebook | Interactive development environment |

---

## ⚙️ Data Preparation

1. **Load Data:**  
   - Import the `pizza_sales.csv` dataset into a Pandas DataFrame.  
2. **Clean Data:**  
   - Handle missing values and format date columns.  
   - Extract day names, months, and ensure data consistency.  
3. **Feature Engineering:**  
   - Derive useful fields like `day_of_week`, `month`, and `pizza_category`.

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Description | Formula |
|------|--------------|----------|
| **Total Revenue** | Total sales amount | `sum(total_price)` |
| **Total Orders** | Unique count of orders | `nunique(order_id)` |
| **Total Pizzas Sold** | Total quantity sold | `sum(quantity)` |
| **Average Order Value (AOV)** | Revenue per order | `total_revenue / total_orders` |
| **Average Pizzas per Order** | Pizzas per order | `total_pizzas_sold / total_orders` |

---

## 📊 Results Snapshot

| Metric | Value |
|--------|--------|
| **Total Revenue** | **\$817,860.05** |
| **Total Orders** | **21,350** |
| **Total Pizzas Sold** | **49,574** |
| **Average Order Value (AOV)** | **\$38.31** |
| **Average Pizzas per Order** | **2.32** |
| **Top 3 Pizzas** | The Thai Chicken Pizza, The Barbecue Chicken Pizza, The California Chicken Pizza |
| **Top Category** | Classic |
| **Most Popular Size** | Large |

---

## 📉 Visualizations

The notebook includes:
- **Revenue by Day of Week**  
- **Top 10 Pizzas by Revenue**  
- **Category vs. Revenue Bar Chart**  
- **Pizza Size Contribution Pie Chart**  
- **Ingredient Frequency Analysis**

*(Optional)* — add rendered images in `/images` and reference them like:
