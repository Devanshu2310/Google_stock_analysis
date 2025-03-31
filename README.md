# Google_stock_analysis
# 📊 Google Stock Analysis using Python & yFinance  

## 🔍 Project Overview  
This project analyzes **Google's stock (GOOG)** using Python and `yfinance`. It calculates **SMA-50 & SMA-200**, identifies **Golden Cross & Death Cross trading signals**, and visualizes stock trends.

## 📈 Features  
✅ Fetches real-time **GOOG stock data** from Yahoo Finance  
✅ Calculates **SMA-50 (Short-Term) & SMA-200 (Long-Term)**  
✅ Detects **Golden Cross & Death Cross** (Buy & Sell signals)  
✅ Plots **closing prices & moving averages** with Matplotlib  
✅ Customizable for **any stock** by changing the ticker symbol  


📝 How It Works
📌 What are SMA-50 & SMA-200?
    Simple Moving Averages (SMA) help smooth out stock price fluctuations by averaging prices over a specific period.

⚡SMA-50 (Short-Term Average)

.Calculates the average closing price over the last 50 days.

.Reacts quickly to price changes, capturing short-term trends.

⚡SMA-200 (Long-Term Average)

.Averages the last 200 days of closing prices.

.Reacts slowly, showing the long-term trend.

📊 Golden Cross vs. Death Cross
🔼 Golden Cross (Bullish Signal)

.When SMA-50 crosses ABOVE SMA-200, it signals a possible uptrend (buy opportunity).

.Indicates that short-term momentum is stronger than the long-term trend.

🔽 Death Cross (Bearish Signal)

.When SMA-50 crosses BELOW SMA-200, it signals a potential downtrend (sell signal).

.Suggests that short-term momentum is weaker, and the stock may decline.


## 🛠️ Installation & Setup  
### 1️⃣ Install Dependencies  
```bash
pip install yfinance matplotlib pandas

