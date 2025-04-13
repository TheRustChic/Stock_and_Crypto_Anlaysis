
# Stock and Crypto Data Analysis Project

This repository contains data analysis and visualization of stock (Tesla and Apple) and cryptocurrency (Bitcoin and Ethereum) price data. The analysis focuses on key financial metrics such as daily returns, volatility, and moving averages, with visualizations to better understand market trends. 

## Project Overview

The project consists of the following components:

### 1. **Stock Analysis (Tesla & Apple)**

Using historical stock data, the analysis covers:
- **Tesla (TSLA)** and **Apple (AAPL)** stock data, including metrics such as:
  - Date
  - High
  - Low
  - Open
  - Close
  - Volume

The data was pulled using the Alpha Vantage API and processed in **Excel**, where the following key metrics were calculated:

- **Daily Returns**: Percentage change in stock price from day to day.
- **Volatility (Daily)**: Calculated as the standard deviation of daily returns, representing the price fluctuation.
- **Cumulative Return**: The total return over the entire period.
- **30-Day Simple Moving Average (SMA)**: The average closing price of the stock over the past 30 days.

### 2. **Crypto Analysis (Bitcoin & Ethereum)**

Historical cryptocurrency data for **Bitcoin (BTC)** and **Ethereum (ETH)** was imported, focusing on the following metrics:
- **Price**
- **Market Cap**
- **Total Volume**

Similar analysis was performed on the crypto data as with the stock data, calculating metrics like **Daily Returns**, **Volatility**, and others.

### 3. **Visualizations**

In addition to the Excel calculations, **Jupyter Notebook** was used to create visualizations:
- **Volatility Chart for Tesla**: A graph showing the stock's volatility over time.
- **Cumulative Return Chart for Tesla**: A line plot showing the growth of an investment in Tesla over the period.
- **30-Day SMA Chart for Tesla**: A visualization of the moving average over the last 30 days.

These charts are created using Python libraries such as **Matplotlib** and **Pandas** for analysis and visualization.

### 4. **Key Insights**

From the analysis, you will gain insights into:
- The volatility of Tesla's stock and how it changes over time.
- The cumulative return of Tesla and Apple stocks over the past year.
- Moving average trends for these stocks.
- Insights into the performance of Bitcoin and Ethereum, with a focus on price, market cap, and trading volume.

### 5. **How to Use the Files**

#### Excel:
- Open the Excel file to explore the data for **Tesla**, **Apple**, **Bitcoin**, and **Ethereum**. 
- Each tab in the file contains the raw data for the respective asset.
- The **Summary Dashboard** provides key metrics and insights into the stocks and cryptocurrencies.
  
#### Jupyter Notebook:
- The Jupyter notebook contains Python code used to analyze Tesla's stock data, focusing on volatility, cumulative returns, and moving averages.
- The visualizations generated in the notebook show the calculated volatility and cumulative returns.

### 6. **Tech Stack**

- **Python** (for analysis and visualization in Jupyter Notebook)
  - Libraries used: Pandas, Matplotlib
- **Excel** (for calculations and storage of stock and crypto data)
- **Alpha Vantage API** (for retrieving stock and crypto data)

---



