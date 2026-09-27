# 📊 Haldyn Heinz Sales Analysis Dashboard

An interactive business intelligence dashboard analyzing sales performance, profitability trends, regional distributions, and customer segments for Haldyn Heinz Fine Glass. Built to go beyond basic visuals by incorporating **multi-dimensional DAX aggregations**, **time-series growth tracking**, **geospatial sales mapping**, and **customer-level profitability analysis**.

> Built and tested on **Power BI Desktop**.

---

## 📌 Executive Summary

This project evaluates business performance over a four-year period (2014–2017) to provide business stakeholders with actionable insights into revenue growth, high-margin product lines, regional market dynamics, and customer purchasing behaviors.

### 📈 High-Level KPIs
* **Total Sales:** ₹2.30M
* **Total Profit:** ₹286.40K
* **Total Orders:** 5,009
* **Total Quantity Sold:** 38,000 units
* **Geographic Scope:** 531 cities

---

## 📌 Why this project

Most sales dashboards only display surface-level revenue numbers. This project is designed to answer real operational questions a sales director or supply chain analyst would ask:

- *Which product categories generate actual profit margin versus high revenue with low net returns?*
- *Which sub-categories are losing money, and how do we trace profitability down to individual customers and orders?*

---

## 🧱 Dashboard Architecture Overview

| Report Page | Purpose |
|---|---|
| Welcome Page | Landing view detailing joint venture background and report navigation |
| Sales Overview | High-level KPIs, category revenue split, and regional performance |
| Profit Analysis | Product-level profit drivers, sub-category waterfall charts, and time series trends |
| Time Series Analysis | Multi-year monthly and quarterly trend tracking with line dynamics |
| Region Wise Analysis | Geospatial sales distribution, heatmaps, and state/city volume breakdowns |
| Customer Analysis | Customer-level profitability, order history tables, and segment analysis |
| Detailed Customer Analysis | Granular order ID, quantity, discount, and individual transaction drill-downs |

---

## 📷 Dashboard Screenshots

### Welcome Page
![Welcome Page](images/Welcome%20Page.png)

### Sales Overview
![Sales Overview](images/Sales%20Overview.png)

### Profit Analysis
![Profit Analysis](images/Profit%20Analysis.png)

### Time Series Analysis
![Time Series Analysis](images/Time%20Series%20Analysis.png)

### Region-Wise Analysis
![Region Wise Analysis](images/Region%20Wise%20Analysis.png)

### Customer Analysis
![Customer Analysis](images/Customer%20Analysis.png)

### Detailed Customer Analysis
![Detailed Customer Analysis](images/Detailed%20Customer%20Analysis.png)

---

## ✨ Key Features & Dashboards

### 1. Sales & Regional Overview
* **Regional & Category Breakdown:** Visualizes sales across East, West, Central, and South regions partitioned by Furniture, Office Supplies, and Technology.
* **Profit Distribution:** Highlights category profit contributions (Technology leads at 50.79% / ₹145.45K).
* **Yearly Trends:** Tracks Year-over-Year sales growth from ₹484K in 2014 to ₹733K in 2017.

### 2. Profitability & Waterfall Analysis
* **Product-Level Profitability:** Identifies top profit-generating items (e.g., Canon imageCLASS copiers).
* **Sub-Category Breakdown:** A waterfall visual illustrating positive profit drivers (Copiers, Phones, Accessories) vs. loss-making sub-categories (Tables, Bookcases).
* **Time Series Trend:** Dynamic line plot monitoring monthly and seasonal profit fluctuations.

### 3. Geographical Mapping & Market Reach
* Map views showing sales distribution across US states and top cities (Seattle, Los Angeles, New York City, Chicago, Houston).
* State-level heatmap indicating revenue and volume concentration.

### 4. Customer Segment & Order Details
* **Segment Analysis:** Breakdowns across Consumer (₹1.16M sales), Corporate (₹0.71M sales), and Home Office (₹0.43M sales).
* **Customer Deep Dive:** Granular breakdown of sales, profits, order quantities, and discounts per individual customer.

---

## 🛠️ Tech Stack & Concepts

* **Tool:** Microsoft Power BI Desktop
* **Data Transformation:** Power Query (M Language) for ETL, data cleaning, and schema modeling
* **Calculations:** DAX (Data Analysis Expressions) for dynamic measures, aggregations, and Time Intelligence
* **Visualization:** Custom visuals, waterfall charts, geospatial mapping, dynamic tooltips, and slicers

---

## 💡 Key Business Insights

1. **Category Performance:** Technology generates over half of total net profits (50.79%), whereas Furniture exhibits high sales volume but tight profit margins.
2. **Customer Segmentation:** The **Consumer** segment represents the largest portion of overall business revenue (~50%).
3. **Sub-Category Focus:** **Copiers** and **Phones** drive the majority of profits, whereas **Tables** show negative profitability and require pricing or cost optimization.

---

## 🚀 Setup & Run (Power BI)

1. Download and install **Microsoft Power BI Desktop**.
2. Clone or download this repository:
   ```bash
   git clone https://github.com/jagadishhugar/Haldyn-Heinz-Sales-Analysis-Dashboard.git

## 👤 Author

**Jagadish Hugar**  
[![Portfolio](https://shields.io/badge/My_Portfolio-4285F4.svg?logo=mainwp&logoColor=white)](https://jagadishhugar.github.io/portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/jagadishhugar) 
[![GitHub](https://img.shields.io/badge/GitHub-8A2BE2.svg?logo=GitHub&logoColor=white)](https://github.com/jagadishhugar)
