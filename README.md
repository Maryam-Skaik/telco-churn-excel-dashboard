# 📞 Telco Customer Churn Analysis Dashboard (Excel Project)

![Excel](https://img.shields.io/badge/Made%20with-Microsoft%20Excel-217346?style=for-the-badge\&logo=microsoft-excel)
![Type](https://img.shields.io/badge/Data%20Analysis-Telecom%20Dashboard-blue?style=for-the-badge)
![Focus](https://img.shields.io/badge/Customer%20Churn-Analysis-red?style=for-the-badge)

---

## 📊 Project Overview

This project is a **fully interactive Excel-based data analysis dashboard** built using a real-world telecom customer dataset.

It simulates a real-world **Customer Care / Telecom Analytics workflow**, focusing on understanding customer behavior, subscription patterns, and churn risk.

The analysis is performed entirely in **Microsoft Excel**, including:

* Data cleaning
* Feature engineering
* Pivot table analysis
* KPI development
* Interactive dashboard design
* Slicer-based filtering

---

## 📁 Dataset Description

The dataset contains customer-level information from a telecommunications company, including demographics, subscribed services, billing details, and churn status.

### 🔑 Features:

* 🆔 Customer ID
* 👤 Gender
* 👵 Senior Citizen status
* 👨‍👩‍👧 Partner / Dependents
* ⏳ Tenure (months)
* 📞 Phone Service
* 🌐 Internet Service
* 🛡️ Online Security / Backup / Tech Support
* 📺 Streaming Services
* 📄 Contract Type
* 💳 Payment Method
* 💰 Monthly Charges
* 💵 Total Charges
* ❌ Churn Status (Yes / No)

---

## 🎯 Project Objectives

This analysis aims to understand customer behavior and answer key business questions:

* What is the overall customer churn rate?
* Which contract types reduce churn the most?
* Does internet service type affect customer retention?
* How do payment methods relate to customer behavior?
* Are high-paying customers more likely to churn?
* Which customer segments are most stable?

---

## 🧹 Data Processing Steps

### 1️⃣ Data Cleaning

* Handled missing values in `TotalCharges`
* Converted numerical columns to correct formats
* Standardized categorical values (Yes / No consistency)

---

### 2️⃣ Feature Engineering

New analytical features were created:

* 📅 Tenure Groups (New / Growing / Loyal / Long-term)
* 💰 Charge Categories (Low / Medium / High)
* 📊 Total Services Count per customer
* 📈 Customer Value estimation (MonthlyCharges × Tenure)

---

### 3️⃣ Data Preparation

* Converted dataset into Excel Table format
* Structured data for Pivot Table analysis
* Ensured consistency for dashboard filtering

---

## 📊 Dashboard Features

The final dashboard is built around **KPIs, Pivot Tables, Charts, and Slicers**.

<img width="970" height="670" alt="image" src="https://github.com/user-attachments/assets/ce060d66-5e5a-4a33-be68-f995c1ba7610" />


---

## 📌 Key KPIs

* 👥 Total Customers
* ❌ Churn Rate (%)
* 💰 Average Monthly Charges
* ⏳ Average Tenure (Months)

These KPIs provide a quick overview of business performance and customer stability.

---

## 📈 Visual Analysis (Charts)

The dashboard includes the following visual insights:

* 📊 Customer Distribution by Contract Type
* ❌ Churn Analysis by Contract
* 🌐 Internet Service Distribution
* 💰 Average Monthly Charges by Internet Service
* 💳 Payment Method Analysis
* 👤 Customer Distribution by Gender

---

## 🎛️ Interactive Filters (Slicers)

The dashboard includes interactive slicers for dynamic filtering:

* Contract Type
* Internet Service
* Gender
* Churn Status
* Payment Method

These allow real-time exploration of customer segments.

---

## 🔍 Key Insights

* 📄 Month-to-month contracts have the highest churn rate.
* 🌐 Fiber optic users tend to have higher monthly charges and higher churn risk.
* 💳 Electronic check users show higher churn compared to automatic payments.
* ⏳ Longer tenure customers are significantly more stable.
* 📄 Two-year contracts have the lowest churn rate and highest retention.

---

## 🛠️ Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Data Cleaning Functions
* IF / COUNTIF / AVERAGE formulas
* Conditional Formatting
* Slicers

---

## 📂 Project Structure

```

telco-churn-analysis/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── excel/
│   └── Telco_Churn_Dashboard.xlsx
│
├── screenshots/
│   └── dashboard.png
│
└── README.md

```

---

## 🚀 What I Learned

* Building a complete business-style dashboard using Excel only
* Understanding customer churn behavior in telecom datasets
* Designing KPIs for real-world business reporting
* Using pivot tables for fast analytical insights
* Creating interactive dashboards using slicers
* Translating raw data into business decisions

---

## 👤 Author

**Maryam Skaik**<br>
Computer Science Graduate | Data Science & ML Enthusiast
