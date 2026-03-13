# Trader Performance vs Market Sentiment Analysis

## Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed)** and **trader behavior and performance** using historical trading data from Hyperliquid.

The objective is to identify patterns in trader activity and determine how market sentiment influences profitability, trading frequency, and position sizes.

---

## Datasets

### 1. Bitcoin Market Sentiment Dataset
Includes:
- Date
- Fear & Greed Index Value
- Market Sentiment Classification (Fear, Greed, Extreme Greed, etc.)

### 2. Hyperliquid Historical Trader Data
Includes:
- Account
- Coin
- Execution Price
- Trade Size (Tokens & USD)
- Side (Buy/Sell)
- Timestamp
- Closed PnL
- Fees
- Transaction details

---

## Project Workflow

1. **Data Loading**
   - Import both datasets using Pandas.

2. **Data Cleaning**
   - Check missing values and duplicates.
   - Convert timestamps to datetime format.

3. **Data Preparation**
   - Align datasets by date.
   - Merge trader data with sentiment data.

4. **Feature Engineering**
   - Daily PnL
   - Win/Loss indicator
   - Trade frequency
   - Position size analysis

5. **Exploratory Data Analysis**
   - PnL vs Market Sentiment
   - Trade Size vs Sentiment
   - Win Rate vs Sentiment
   - Trader segmentation

---

## Key Insights

- Traders tend to execute **larger trades during Greed or Extreme Greed market conditions**.
- **Profitability and win rates often decrease during Fear periods**, indicating uncertain market behavior.
- Traders with **larger starting positions experience higher PnL volatility**.

---

## Strategy Recommendations

1. During **Fear sentiment periods**, traders should reduce position size or leverage to manage risk.
2. During **Greed periods**, higher market activity may benefit frequent traders, but risk management remains important.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Author

**Pranav Ugale**

B.Tech – Artificial Intelligence & Data Science  
D.Y. Patil College of Engineering, Pune