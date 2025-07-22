# 🏷️ Nike Stock Return Predictor

A data-driven passion project analyzing Nike (NKE) stock price history to predict next-day returns using financial indicators and statistical features. This notebook covers data acquisition, visualization, feature engineering, and return forecasting—ideal for understanding stock behavior and gaining insight into market trends.

---

## 📌 Overview

This project aims to:
- Analyze Nike stock data from 2020 to 2024.
- Extract features such as daily returns, rolling volatility, and SMA.
- Explore trends based on time (month, day of week).
- Build a simple binary prediction model to forecast whether the stock will rise the next day.

---

## 📁 Dataset

- Source: Yahoo Finance via `yfinance` API
- Ticker: `NKE`
- Timeframe: January 2020 – January 2024
- Frequency: Daily stock prices

---

## 🔧 Tools & Technologies

- **Language:** Python
- **Notebook:** Jupyter
- **Libraries:** 
  - `pandas`, `numpy` – data manipulation
  - `matplotlib`, `seaborn` – visualizations
  - `scipy.stats.mstats` – winsorization for outlier treatment
  - `yfinance` – stock data scraping

---

## 🔍 Key Features & Techniques

- 📉 **Time Series Visualization**  
  Trend analysis using closing and opening prices, moving averages, and volatility.

- 📊 **Statistical Feature Engineering**  
  - Open-to-Close return
  - Day-to-day return
  - 20-day Simple Moving Average (SMA)
  - 20-day rolling volatility

- 📅 **Date-based Analysis**  
  Aggregation and return behavior grouped by:
  - Month
  - Day of the week

- 🧪 **Return Prediction Setup**  
  Created a binary label indicating whether the stock price will rise the next day using `shift(-1)` logic.

---

## 📈 Results & Insights

- Identified patterns in daily return volatility.
- Observed seasonal and weekday trends in returns.
- Built a dataset with clean features for future model training (classification).

---

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/nike-stock-predictor.git
   cd nike-stock-predictor
