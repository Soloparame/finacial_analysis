# 📊 Financial Analytics Challenge – Week 1 

This repository documents the work done during **Week 1** of the Financial Analytics Challenge, focusing on **sentiment analysis**, **technical indicators**, and **exploratory financial data analysis** for stock market insights.

---

## 🗂️ Tasks Overview

### ✅ Task 1: Exploratory Data Analysis and Sentiment Tagging

**Objective**:  
Analyze the structure of the financial news and stock price datasets, extract datetime values, and perform **sentiment analysis** on financial headlines.

**Key Steps**:
- Loaded and explored two datasets:
  - `raw_analyst_ratings.csv` (news)
  - `AAPL_historical_data.csv` (stock prices)
- Cleaned and aligned date formats.
- Used `TextBlob` to calculate **polarity scores** for each headline.
- Tagged headlines as:
  - **Positive**: Polarity > 0
  - **Negative**: Polarity < 0
  - **Neutral**: Polarity = 0
- Aggregated and visualized daily sentiment.

**Tools Used**:
- Python
- Pandas
- TextBlob
- Matplotlib / Seaborn

---

### ✅ Task 2: Technical Analysis of Stock Prices

**Objective**:  
Calculate and visualize common technical indicators using historical stock data to identify trends and momentum.

**Key Indicators**:
- **SMA (Simple Moving Average)** – 20 & 50-day
- **EMA (Exponential Moving Average)** – 12 & 26-day
- **RSI (Relative Strength Index)**
- **MACD (Moving Average Convergence Divergence)**
- **Volume Analysis**

**Key Insights**:
- Detected **golden crosses** (bullish signals) in SMA/EMA.
- RSI identified **overbought/oversold zones**.
- MACD crossovers aligned well with price movements.
- Volume spikes confirmed strong trends.

**Tools Used**:
- Python
- Pandas
- TA-Lib (or custom functions for indicators)
- Matplotlib / Seaborn

---

## 📁 Project Structure

