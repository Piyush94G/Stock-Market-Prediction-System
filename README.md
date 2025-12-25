# 📈 Stock Market Prediction System (Professional Trading Platform)

A **professional-grade stock market analysis and prediction platform** built using **Python and Streamlit**, designed to democratize access to institutional-level trading tools.  
The system integrates **technical analysis, sentiment analysis, quantitative risk metrics, and market-wide insights** into a single unified dashboard.

This project was developed as part of the **B.Tech (Computer Science Engineering)** curriculum at **BML Munjal University**.

---

## 📌 Project Overview

Retail investors often lack access to premium platforms like **Bloomberg Terminal** or **TradingView Pro** due to high costs.  
This project bridges that gap by delivering **70–80% of professional trading platform capabilities at zero cost**, using open-source technologies.

### Key Capabilities:
- 20+ technical indicators
- Automated Buy/Sell/Hold signals
- NLP-based news sentiment analysis
- Institutional-grade risk metrics
- Multi-stock and sector-level comparison
- Interactive TradingView-style charts

---

## 🎯 Objectives

- Provide institutional-grade technical analysis tools
- Automate trading signal generation using multi-factor logic
- Integrate AI-powered sentiment analysis using NLP
- Quantify portfolio risk using professional financial metrics
- Build an intuitive, interactive web dashboard
- Enable informed, data-driven trading decisions

---

## 🧠 Core Features

### 🔍 Technical Analysis
- SMA (20, 50, 200)
- EMA (12, 26)
- RSI, MACD, Stochastic Oscillator
- Bollinger Bands, ATR
- VWAP, OBV
- Volume & price-action indicators

### ⚡ Automated Trading Signals
Evaluates **21 market conditions** across:
- Trend
- Momentum
- Volatility
- Volume
- Market structure

Generates:
- Strongly Bullish
- Bullish
- Neutral
- Bearish
- Strongly Bearish signals

---

### 📰 Sentiment Analysis (NLP)
- Fetches latest financial news per stock
- Uses **VADER Sentiment Analyzer**
- Computes:
  - Average sentiment
  - Sentiment volatility
  - Confidence-based Buy/Sell/Hold recommendations

---

### 📊 Risk Management (QuantStats)
Institutional-grade metrics:
- Sharpe Ratio
- Sortino Ratio
- Maximum Drawdown
- Value at Risk (VaR)
- Annualized Volatility
- Calmar Ratio
- Win Rate

---

### 📉 Stock & Market Comparison
- Multi-stock normalized performance comparison
- Relative strength analysis
- Sector heatmaps
- Market index overview (S&P 500, NASDAQ, Dow Jones, VIX, Russell 2000)

---

## 🗂️ Dataset Used

- **Historical stock price data** (OHLC, Volume)
- **Real-time news articles**
- **Sentiment scores**
- **Market & sector data**

**Data Sources:**
- Yahoo Finance (`yfinance`)
- Financial news APIs

---

## 🛠️ Technologies Used

- **Python**
- **Streamlit**
- **Pandas, NumPy**
- **pandas-ta**
- **Scikit-learn**
- **VADER Sentiment Analysis**
- **Plotly**
- **QuantStats**

---

## 🖥️ Application Modules

- Chart Analysis
- Trading Signals
- Technical Indicators
- Sentiment Analysis
- Risk Analysis
- Performance Metrics
- Market Overview
- Stock Comparison
- Screener

---

## 📊 Results & Insights

- Hybrid analysis (technical + sentiment + risk) provides more reliable signals

- Market dashboards reflect real-time macro trends

- Stock comparison reveals momentum leaders and low-risk assets

- Sector heatmaps highlight capital rotation

- Sentiment analysis helps detect early catalysts

---
## 🚀 How to Run the Project

```bash
# Clone the repository
git clone https://github.com/your-username/stock-market-prediction-system.git

# Navigate to the project directory
cd stock-market-prediction-system

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
