# Starbucks Stock Analysis

This project provides a detailed analysis of the Starbucks Corporation (SBUX) stock performance using Python. It leverages historical stock data, technical indicators, and visualizations to analyze price movements, volatility, and trends.

## Project Overview

The purpose of this analysis is to gain insights into the historical performance of Starbucks stock and provide visualizations to better understand market trends. Various technical indicators are calculated, and multiple charts are included to represent the findings.

## Features

- **Moving Averages (MA):** 
  - 50-day and 200-day moving averages to identify long-term and short-term trends.
  
- **Volatility:** 
  - Daily returns and the volatility of the stock are visualized to assess fluctuations over time.
  
- **Trading Volume:**
  - A representation of trading activity with volume plotted over time.

- **Bollinger Bands:**
  - A technical indicator that shows a price range within which the stock typically moves. The Bollinger Bands include a 20-day moving average, with bands two standard deviations above and below the average.

- **Price History Visualization:**
  - A line chart to illustrate the stock's price history.

## Data Used

The data used in this project was retrieved from [Yahoo Finance](https://finance.yahoo.com/quote/SBUX/history?p=SBUX) and includes the following columns:

- **Date**
- **Open**
- **High**
- **Low**
- **Close**
- **Adj Close**
- **Volume**

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Starbucks-Stock-Analysis.git
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Starbucks_Stock_Analysis.ipynb
   ```

## Libraries Used

- `pandas` for data manipulation and analysis
- `matplotlib` for plotting and visualizations
- `numpy` for numerical operations
- `yfinance` to retrieve stock data

## Visualizations

The analysis includes the following visualizations:

- **Moving Averages:** Displays short-term and long-term trends with 50-day and 200-day moving averages.
- **Daily Returns:** Plots daily returns to visualize volatility.
- **Volume Chart:** Shows the trading volume over time.
- **Bollinger Bands:** Plots price, upper and lower bands to evaluate potential price breakouts.
- **Cumulative Return:** Displays cumulative stock performance over time.

## Future Work

- Add more technical indicators such as the Relative Strength Index (RSI) and MACD.
- Integrate machine learning to predict future stock prices based on historical data.
- Automate stock data retrieval and analysis with scheduled updates.
