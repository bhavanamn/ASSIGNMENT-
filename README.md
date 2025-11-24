Trader Performance vs Market Sentiment Analysis
📌 Overview

This project analyzes how Bitcoin market sentiment (Fear–Greed Index) influences trader performance using historical Hyperliquid trading data.
The goal is to clean the data, build performance metrics, merge sentiment, and generate insights supported by visualizations.
📂 Datasets
1. Fear–Greed Index

timestamp, value, classification, date
Used to understand daily market sentiment.

2. Hyperliquid Trader Data

Account, Timestamp IST, Closed PnL, Side, Coin, Fee, etc.
Used to compute trader behaviour and profitability.
🧠 Objectives

Compute daily trader performance (P&L, win rate, volatility)

Build equity curves & drawdowns

Compare performance on Fear vs Greed days


Visualize trends through charts
🧪 Steps Performed
1. Data Cleaning

Parsed timestamps

Converted PnL to numeric

Extracted daily date from time

2. Performance Metrics

Daily PnL per account

Win/loss counts & win rate

Average PnL & standard deviation

Sharpe-like ratio

Max drawdown

Monthly PnL summary

3. Visualizations

Plots generated:

📈 Equity curve

📉 Drawdown curve

📊 Monthly PnL bar chart

🥧 Win/Loss pie chart

(All saved as PNG files.)

4. Sentiment Merge

Matched trades with daily sentiment

Compared PnL, win rate, and drawdown across Fear, Neutral, Greed days.
▶️ Run Instructions

Install requirements:

pip install pandas numpy matplotlib
🎯 Deliverables Included

Cleaned datasets

Performance metrics tables

Visual charts (PNG)

Sentiment vs PnL analysis



