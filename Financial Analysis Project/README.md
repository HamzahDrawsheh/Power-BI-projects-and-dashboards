# 📊 Sales Analysis Dashboard (Power BI)

## Sales Analysis:
<p align="center">
  <img src="https://github.com/HamzahDrawsheh/Power-BI-projects-and-dashboards/blob/main/Financial%20Analysis%20Project/Sales.png" width="1500", height="1000">
</p>

## Profit Analysis: 
<p align="center">
  <img src="https://github.com/HamzahDrawsheh/Power-BI-projects-and-dashboards/blob/main/Financial%20Analysis%20Project/Profit.png" width="1500", height="1000">
</p>

## State Details Analysis:
<p align="center">
  <img src="https://github.com/HamzahDrawsheh/Power-BI-projects-and-dashboards/blob/main/Financial%20Analysis%20Project/State_details.png" width="1500", height="1000">
</p>


## 📌 Project Overview
This project focuses on analyzing sales data using **Power BI** to extract meaningful insights that support business decision-making.  
The dashboard is designed with a **clear analytical structure** and consists of **three main pages**:
- Sales Overview
- Profit Analysis
- State-Level Details

The dataset follows a **star schema** model, making it suitable for BI and analytical reporting.

---

## 🗂️ Dataset Description
The dataset contains both **fact** and **dimension** tables, commonly used in data warehousing and business intelligence.

### 🔹 Fact Table
**FactSale**
- Sales Amount  
- Profit  
- Quantity  
- Order Date  
- Customer Key  
- Product Key  
- Employee Key  
- Territory / Location Keys  

This table represents the **core transactional data** used for all calculations and KPIs.

---

### 🔹 Dimension Tables
- **DimDate**  
  Contains date-related attributes (year, month, quarter, etc.) to enable time-based analysis.

- **DimCustomer**  
  Includes customer demographic and classification data.

- **DimCity**  
  Provides geographical details such as city, state, country, and sales territory.

- **DimEmployee**  
  Information about sales employees and their related attributes.

- **DimStockItem**  
  Product-level details including categories and product information.

---

## 🧩 Data Model
The dataset is structured using a **Star Schema**, where:
- `FactSale` acts as the central table.
- Dimension tables are connected via primary and foreign keys.

This structure improves:
- Query performance  
- Data clarity  
- Analytical flexibility in Power BI  

---

## 📈 Dashboard Pages Explanation

### 1️⃣ Sales Overview
This page provides a high-level view of sales performance:
- Total Sales
- Sales Trends over Time
- Sales by Product and Category
- Key KPIs for quick business insights

📌 **Purpose:**  
Help stakeholders quickly understand overall sales performance and trends.

---

### 2️⃣ Profit Analysis
Focused on profitability across different dimensions:
- Total Profit
- Profit Margin
- Profit by Product
- Profit by Territory / Region

📌 **Purpose:**  
Identify the most and least profitable products and regions to support pricing and strategy decisions.

---

### 3️⃣ State Details
Geographical analysis at the state level:
- Sales and Profit by State
- Regional comparisons
- Performance distribution across locations

📌 **Purpose:**  
Enable location-based decision-making and market performance evaluation.

---

## 🎯 Business Value & Use Cases
This dashboard can help:
- Monitor sales and profit performance
- Identify high-performing products and regions
- Detect underperforming states or territories
- Support strategic planning and forecasting
- Improve data-driven decision-making

 

If you find this project useful, feel free to ⭐ the repository!

