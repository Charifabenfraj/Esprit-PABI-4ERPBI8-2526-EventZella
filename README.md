# 📊 EventZella – Business Intelligence & Analytics Dashboard

## 🧩 Project Overview

EventZella is a data-driven platform designed to manage event services, reservations, and customer interactions.
This project focuses on building a **Data Warehouse**, defining **Key Performance Indicators (KPIs)**, and creating an **interactive Power BI dashboard** to support strategic decision-making.

---

## 🎯 Objectives

* Analyze platform performance using data
* Support decision-makers with actionable insights
* Monitor operational, financial, marketing, and service KPIs
* Integrate Machine Learning for predictive analytics

---

## 👥 Decision Makers

* **Platform Administrator** → monitors system performance
* **Marketing Manager** → tracks acquisition & conversion
* **Quality Manager** → ensures customer satisfaction
* **Business Manager** → analyzes revenue & profitability

---

## 🗄️ Data Warehouse Architecture

The project is based on a **star schema** with:

### 🔹 Dimensions

* `dim_date`
* `dim_service`
* `dim_provider`
* `dim_beneficiary`
* `dim_event`
* `dim_category_subcategory`
* `dim_reservation`
* `dim_marketing`
* `dim_visitors`

### 🔹 Fact Tables

* `fact_reservation`
* `fact_marketing`
* `fact_view`
* `fact_benchmark_market`

This structure ensures:

* Data consistency
* Efficient querying
* Scalable analytics

---

## 📈 Key Performance Indicators (KPIs)

### ⚙️ Operational KPIs

* Pending Reservation Rate
* Revenue at Risk
* Peak Booking Hours
* No Evaluation Rate
* Weekend Booking Share

### ⭐ Quality KPIs

* Positive Rating Rate
* Negative Rating Rate
* Complaints per Customer
* Open Complaint Rate
* Weighted Quality Index

### 💰 Business KPIs

* ARPB (Average Revenue per Beneficiary)
* Median Revenue per Booking
* Revenue Concentration
* Over-Budget Rate
* Budget Utilization

### 🛠️ Product / Service KPIs

* Discount Rate
* Price Gap
* Upsell Rate
* Service Diversity
* Category Depth

---

## 📊 Power BI Dashboard

### Pages Structure

1. **Operational Dashboard**
2. **Quality Dashboard**
3. **Business Dashboard**
4. **Product & Service Dashboard**

### Features

* KPI Cards with conditional formatting
* Gauges with thresholds
* Line & Bar charts for trends
* Tooltips and drill-through analysis
* Interactive filters (date, category, provider)

---

## 🎨 Design & UX

* Color coding:

  * 🟢 Good performance
  * 🔴 Critical
* Icons and indicators (▲ ▼ ●) for trends
* Sidebar navigation with interactive icons

---

## 🤖 Machine Learning Use Cases

* Cancellation Prediction
* Revenue Forecasting
* Customer Segmentation
* Complaint Detection
* Recommendation System
* Churn Prediction

---

## 🛠️ Technologies Used

* **SQL (MySQL)** → Data Warehouse
* **Power BI** → Data Visualization
* **Python (ML models)** → Predictive analytics
* **GitHub** → Version control

---






