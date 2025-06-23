# 🍕 Domino’s Predictive Purchase Order System

![Inventory Optimization](https://img.shields.io/badge/Inventory-Optimization-green)
![Time Series Forecasting](https://img.shields.io/badge/Forecasting-ARIMA%20%7C%20SARIMA-blue)
![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📘 Project Overview

Domino’s faces a critical operational challenge:  
> ❌ **Overstocking** leads to ingredient waste  
> ❌ **Understocking** leads to lost sales  

This project implements a **predictive analytics system** that forecasts pizza demand and automatically generates **optimized purchase orders**, ensuring better stock levels and reducing waste.

---

## 🎯 Key Goals

- 🔮 Accurately **forecast pizza sales** using historical data  
- 📦 Generate a smart **purchase order system**  
- 🛒 Avoid stockouts & reduce excess inventory  
- 💰 Cut costs and boost operational efficiency  

---

## 🧠 Approach & Methodology

### 🗂️ 1. Data Preparation
- Imported sales and ingredient usage datasets  
- Cleaned and standardized missing or inconsistent values  

### 🔧 2. Merging & Feature Engineering
- Merged data on date & store-level granularity  
- Created features like:
  - Day of week
  - Month
  - Holidays
  - Promotions

### 📊 3. Exploratory Data Analysis (EDA)
- Analyzed seasonal patterns & sales cycles  
- Visualized ingredient usage, peak days, demand trends

### 📈 4. Model Selection
- Implemented:
  - **ARIMA**
  - **SARIMA**

🧪 **Comparison using MAPE (Mean Absolute Percentage Error):**
| Model   | MAPE   | Result              |
|---------|--------|---------------------|
| ARIMA   | 5.83%  | ✅ Best performance |
| SARIMA  | 6.15%  | ❌ Higher error     |

✅ **ARIMA** selected due to lower forecast error

### 💾 5. Model Saving & Deployment
- Trained models stored using `Pickle` for reusability  
- Ready for integration with real-time inventory systems

---

## 🚀 Final Outcome

- 🔥 **Optimized purchase order system built**  
- 🧠 **Forecast accuracy (MAPE): 5.83%**  
- 📉 Reduced ingredient waste & over-purchasing  
- 🛒 Prevented stock shortages during peak hours  
- 💡 Boosted inventory planning, efficiency & customer satisfaction

---

## 🛠 Tech Stack

- 🐍 Python  
- 📦 Pandas, NumPy, Matplotlib  
- ⏳ Statsmodels (ARIMA/SARIMA)  
- 📦 Pickle (Model Storage)  
- 📊 Seaborn for visualization

---
