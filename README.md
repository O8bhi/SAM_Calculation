# 📈 SMA Calculation

This project calculates the **Simple Moving Average (SMA) 50** and **SMA 200** for 10 Indian stocks using live market data from **Yahoo Finance (yfinance)** and visualizes them along with the closing price.

It is mainly used for **technical analysis** to identify:
- Trend direction  
- Support and resistance levels  
- Buy/Sell signals based on moving average crossover  

---

## 🚀 Features

- Fetches real-time and historical stock data using **yfinance**
- Calculates:
  - SMA 50 (Short-term trend)
  - SMA 200 (Long-term trend)
- Plots:
  - Closing Price
  - SMA 50
  - SMA 200
- Works for multiple Indian stocks in one run
- Easy to modify for more stocks or different time periods

---

## 🏦 Stocks Used

The project analyzes 10 Indian stocks.
- TCS – Tata Consultancy Services
- RELIANCE – Reliance Industries
- HDFCBANK – HDFC Bank
- INFY – Infosys
- ICICIBANK – ICICI Bank
- SBIN – State Bank of India
- ITC – ITC Limited
- HINDUNILVR – Hindustan Unilever
- LT – Larsen & Toubro


## 🛠️ Technologies Used

- Python  
- yfinance  
- pandas  
- matplotlib  

---

## 📊 Output Example

Each stock will have a graph showing:
- Stock Closing Price  
- SMA 50  
- SMA 200  

This helps in visual identification of:
- Golden Cross (SMA 50 crosses above SMA 200 → Bullish)
- Death Cross (SMA 50 crosses below SMA 200 → Bearish)

---
