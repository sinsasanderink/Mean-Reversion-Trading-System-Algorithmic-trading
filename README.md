# Mean-Reversion-Trading-System-Algorithmic-trading
A Python-based algorithmic trading system that identifies and capitalizes on mean reversion opportunities in equities using z-score, RSI, and fundamental filtering. Includes automated data collection, signal generation, position sizing, and rule-based entry/exit logic.


# 🧠 Building a Professional Mean Reversion Trading System

A full-stack algorithmic trading system in Python that identifies **mean reversion** opportunities in the stock market using a blend of **statistical analysis**, **technical indicators**, **fundamental filtering**, and **machine learning**.

## 📈 Strategy Overview

Mean reversion assumes that high-quality stocks tend to revert to their historical average prices after extreme moves. Our system buys stocks that are statistically oversold but fundamentally strong.

- **Technical Alpha**: z-scores, RSI, moving averages
- **Fundamental Filters**: EPS, P/E ratio, ROE, debt ratios
- **ML Integration**: Predictive modeling of reversion likelihood
- **Execution**: Live trading via [Alpaca API](https://alpaca.markets/)

## 🛠️ Features

- 🔗 **API Integration**: Seamless data access and trade execution via Alpaca
- 🔍 **Signal Generation**: Multi-layer logic using z-score + RSI filters
- 🧪 **Backtesting**: Full walk-forward testing and stats (Sharpe, drawdown, win rate)
- 📊 **Ranked Signals**: Live ranked opportunities with signal strength scores
- 🔎 **Fundamental Screening**: Simulated data w/ pluggable real APIs
- 📰 **News + Earnings Filtering**: Avoid bad-news or upcoming earnings traps
- 🤖 **ML Quality Filtering**: Predictive model classifies reversion probabilities

## ⚙️ Tech Stack

- **Python 3.11**
- `alpaca-py`, `pandas`, `scikit-learn`, `matplotlib`, `numpy`
- Supports local or Google Colab execution

## 🧪 Current Status

✅ Core pipeline (signal generation, ranking, Alpaca API setup)  
🔄 In-progress: fundamental filters, automated trade management, ML models, portfolio logic  
🧠 Micro-cap edge detection (e.g. LGHL reversion signal w/ -2.35 z-score + RSI 19)


