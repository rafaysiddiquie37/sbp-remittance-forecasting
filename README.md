# 📊 SBP Remittance Forecasting Model

Predicting Pakistan's workers' remittance inflows using machine learning and macroeconomic indicators from the State Bank of Pakistan (SBP).

---

## 🏆 Results

| Metric | Score |
|--------|-------|
| R² Score | **0.9860** |
| Mean Squared Error | 1,808.95 |

---

## 📌 Project Overview

Workers' remittances are one of Pakistan's largest sources of foreign exchange. This project builds a **Random Forest Regression** model to forecast remittance inflows based on macroeconomic variables such as gold prices, USD exchange rate, crude oil, S&P 500, and population data.

---

## 🛠️ Techniques Used

- **Log Transformation** — applied to the target variable to handle skewed distribution
- **Label Encoding** — to convert categorical country/series data into numeric features
- **Feature Engineering** — extracted Year, Month, and Quarter from date column
- **Feature Importance Analysis** — identified key drivers of remittance inflows

---

## 📂 Dataset

- **Source:** State Bank of Pakistan (SBP)
- **Records:** 21,861 rows
- **Features:** Gold price, USD rate parity, Silver, Crude Oil, S&P 500, USD Interest Rate, Total Population, Date features, Series/Country code

---

## 🔑 Key Findings

- **Series Code (country of origin)** is by far the most important feature at **75.8% importance**
- **Total Population** and **Gold Price** are the next most influential factors
- Log-transforming the target variable was critical — without it R² was only 0.01

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn (RandomForestRegressor)
- Matplotlib
- Google Colab

---

## 🚀 How to Run

1. Clone this repository
2. Upload `SBP Remittance dataset.csv` to your Colab environment
3. Open `SBP_Remittance_Forecasting.ipynb` in Google Colab
4. Click **Runtime → Run all**

---

## 👤 Author

**Muhammad Rafay Siddiquie**  
MS Business Analytics — Karachi School of Business and Leadership (KSBL)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/rafay-siddiquie-604305254/)
