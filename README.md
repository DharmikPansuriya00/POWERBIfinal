# 📊 Power BI Expert Dashboard  
### *End-to-End Data Modeling, DAX & Business Intelligence Solution*

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Advanced-blue)
![Domain](https://img.shields.io/badge/Domain-Business%20Intelligence-purple)

---

## 🧠 Project Overview

This **Power BI Expert Dashboard** is a **production-ready Business Intelligence solution** designed to demonstrate **advanced Power BI skills** including:

✔ Data Modeling (Star Schema)  
✔ Advanced DAX Calculations  
✔ Time Intelligence  
✔ Performance Optimization  
✔ Interactive & Insight-Driven Dashboards  

The project converts **raw business data** into **actionable insights** using industry-standard BI practices.

---

## 🎯 Business Objectives

- Analyze overall **business performance**
- Track **sales, profit, and growth trends**
- Identify **top & bottom performing segments**
- Enable **data-driven decision making**
- Provide a **scalable reporting model**

---

## 🗂 Dataset & Data Model

### 🔹 Data Sources
- Fact & Dimension tables (Sales, Customers, Products, Date, Region)
- Structured using **best-practice normalization**

### 🔹 Data Modeling Approach
- ⭐ **Star Schema**
- One-to-Many relationships
- Proper cardinality & filter flow
- Dedicated **Date Table** for time intelligence

📌 *Model optimized for performance and DAX accuracy.*

---

## 🧩 Data Model Diagram

![Data Model](screenshots/data_model.png)

---

## 📐 Key Metrics (DAX Measures)

Some of the **expert-level DAX measures** implemented:

```DAX
Total Sales = SUM(Sales[Revenue])

Total Profit = 
SUM(Sales[Revenue]) - SUM(Sales[Cost])

Profit Margin % =
DIVIDE([Total Profit], [Total Sales], 0)

YTD Sales =
TOTALYTD([Total Sales], 'Date'[Date])

YoY Growth % =
DIVIDE(
    [Total Sales] - [Sales Last Year],
    [Sales Last Year]
)
