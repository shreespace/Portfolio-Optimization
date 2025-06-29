# 📈 Portfolio Optimization using Markowitz Model (Modern Portfolio Theory)

This project leverages **Modern Portfolio Theory (MPT)** — proposed by Nobel laureate **Harry Markowitz** — to simulate and identify **optimal stock portfolios** based on historical data, maximizing returns while minimizing risk.

---

## 🚀 Overview

This notebook performs:
- 📊 **Data Extraction** using Yahoo Finance (`yfinance`)
- 🧮 **Log Return & Risk Calculation**
- 🧪 **100,000 Monte Carlo Simulations**
- 🟢 Portfolio selection for:
  - ✅ **Maximum Sharpe Ratio**
  - 📉 **Minimum Risk**
  - 📈 **Maximum Return**
- 🌈 **Visualization of Risk vs Return** space for all portfolios

---

## 📌 Tools & Libraries Used

- `Python 3.10+`
- `NumPy`, `Pandas` — numerical computing and data handling
- `Matplotlib`, `Seaborn` — for visualizations
- `yfinance` — to fetch historical stock prices

---

## 📅 Time Period Analyzed

> **From:** `1st October 2022`  
> **To:** `1st October 2023`  
> **Trading Days Considered:** ~260

---

## 📦 Stocks Analyzed

| Ticker         | Company Name         |
|----------------|----------------------|
| RELIANCE.NS    | Reliance Industries  |
| TCS.NS         | Tata Consultancy     |
| HINDUNILVR.NS  | Hindustan Unilever   |
| HDFCBANK.NS    | HDFC Bank            |
| ITC.NS         | ITC Limited          |
| LT.NS          | Larsen & Toubro      |
| INFY.NS        | Infosys              |

---

## 🧠 Methodology

### 1. **Daily Log Returns Calculation**
Normalized returns using:
```math
\text{Log Return} = \ln \left( \frac{P_t}{P_{t-1}} \right)
