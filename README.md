# Stock-Trading-Backtest-using-SMA

This project presents a Python script that implements a simple moving average crossover trading strategy, backtests it with historical stock data, and performs trading on Alpaca API. 

## Overview
This Python script fetches historical stock price data for selected symbols from Yahoo Finance using the `yfinance` library. It calculates two different Simple Moving Averages (SMA) - short term and long term. When the short term moving average crosses above the long term moving average, it is considered a "buy" signal, and when it crosses below, it's a "sell" signal.

The trading signals are used to place actual trades using Alpaca API. Each signal prompts the script to buy or sell 100 shares of the specific stock, which can easily be adjusted according to individual requirements.

This is a basic implementation of an algorithmic trading strategy and serves as a good starting point for more complex trading algorithms. Please remember that this is a demonstration and not financial advice.

## Key Features
- Fetches historical stock price data from Yahoo Finance
- Calculates short term and long term SMAs to generate trading signals
- Places actual trades on Alpaca based on trading signals
- Backtests the strategy with historical data and provides a visual representation of the strategy performance

## Requirements
- Python 3.6+
- yfinance library: Install with `pip install yfinance`
- pandas library: Install with `pip install pandas`
- matplotlib library: Install with `pip install matplotlib`
- alpaca_trade_api library: Install with `pip install alpaca-trade-api`

## Getting Started
To use this algorithm, follow these steps:

1. Clone the repository: `git clone https://github.com/YourUsername/YourRepo.git`
2. Install the required libraries.
3. Customize the script to set your preferred stock symbols, date range, and strategy parameters.
4. Set up Alpaca API keys.
5. Run the script and review the trading operations performed and strategy performance.
