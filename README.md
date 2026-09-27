# 🚗 Car Sales Performance & Analytics Dashboard | Power BI

An interactive and comprehensive **Power BI Dashboard** created to analyze YTD car sales performance, revenue trends, body style preferences, regional dealer performance, and pricing metrics.

This project was built as a hands-on learning initiative to practice end-to-end data visualization, DAX calculations, interactive filtering, and dashboard UI design in Power BI.

---

## 📌 Project Overview

The objective of this project is to provide actionable business insights into car sales data. The dashboard enables stakeholders to track Key Performance Indicators (KPIs), identify top-performing vehicle categories, monitor sales trends over time, and evaluate regional dealer performance.

* **Project Duration:** 1 Week
* **Tool Used:** Microsoft Power BI Desktop
* **Special Thanks:** Guided by tutorial resources from the **Data Tutorials** YouTube channel.

---

## 📊 Key Features & KPI Metrics

* **YTD Total Sales:** **$371.2M** (+23.59% YoY Growth)
* **YTD Average Price:** **$28.0K** (-0.44% YoY Change)
* **YTD Cars Sold:** **13.3K** Units (+19.73% YoY Growth)
* **Weekly Sales Trend:** Line chart displaying weekly revenue fluctuations throughout the year.
* **Sales by Body Style:** Donut chart breakdown across SUVs, Hatchbacks, Sedans, Passengers, and Hardtops.
* **Sales by Color:** Donut chart showing customer color preferences (Pale White, Black, Red).
* **Geographic Analysis:** Interactive map chart showing sales distribution across US dealer regions (Austin, Greenville, Janesville, Middletown, Pasco, Scottsdale).
* **Company Performance Table:** Detailed breakdown of sales by manufacturer (Acura, Audi, BMW, Buick, Cadillac, Chevrolet, Chrysler, Dodge, Ford, Honda, etc.).
* **Dynamic Slicers:** Interactive filters for Body Style, Dealer Name, Company, Engine Type, and Date Range.

---

## 🛠️ Data Model & DAX Formulas

Key measures created using Data Analysis Expressions (DAX) include:
* **YTD Total Sales** = `SUM(Sales[Total_Sales])`
* **YTD Cars Sold** = `SUM(Sales[Units_Sold])`
* **YTD Average Price** = `DIVIDE([YTD Total Sales], [YTD Cars Sold])`
* **YoY Comparison Metrics** for Sales Growth and Average Price differences.

---

## 💡 Key Insights Uncovered

1. **Top Body Style:** SUVs and Hatchbacks generated the highest sales revenue ($99.9M and $82.8M respectively).
2. **Color Demand:** Pale White and Black are the top preferred colors among buyers.
3. **Regional Performance:** Key hubs like Middletown, Janesville, and Austin drive a major portion of dealership revenue.

---
<img width="1422" height="796" alt="Cars Overview Dashboard" src="https://github.com/user-attachments/assets/3c645a85-6a91-4172-9287-d8cae03c7251" />
