# 📈 SMA Crossover Stock Analysis

A simple Python script that checks **Simple Moving Average (SMA) crossovers** for any given stock symbol — helps identify potential **uptrends (Golden Cross)** or **downtrends (Death Cross)** using 50-day and 200-day SMAs.

> Built with 🐍 **Python**, 📊 **Pandas**, and 💹 **yFinance** — ideal for retail investors, finance enthusiasts, and data science learners.

## 🚀 Features

- Fetches **1 year** of historical stock data.
- Calculates **50-day** and **200-day** Simple Moving Averages (SMA).
- Identifies:
  - ✅ **Golden Cross** (50-day SMA > 200-day SMA → Possible uptrend)
  - ❌ **Death Cross** (50-day SMA < 200-day SMA → Possible downtrend)
- Supports **Indian stocks** (like `INFY.NS`) and **International stocks** (like `AAPL`).

## 🛠️ Tech Stack

- Python 3.x
- yFinance
- Pandas

## 📥 Installation

1. **Clone the repository**
```bash
git clone https://github.com/ak18akashrajr/sma-crossover-stock-analysis.git
cd sma-crossover-stock-analysis
