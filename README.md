# Dynamic Forecasting with Kalman Filter

## Overview
This repository contains a Python implementation of dynamic forecasting for stock prices using the Kalman Filter. The project aims to provide an interactive and user-friendly tool for predicting stock prices over a specified period.

## Features
- **User Interaction:** Users can input the stock ticker symbol of their choice.
- **Data Loading:** Fetches historical stock price data for the last six months.
- **Kalman Filter Application:** Applies the Kalman filter with adjustable parameters for observation and process variance.
- **Result Visualization:** Generates a line graph comparing true stock prices with Kalman-filtered prices.

## Prerequisites
- Python 3.x
- Required libraries: pandas, numpy, matplotlib, yfinance

## Usage
1. Clone the repository: `git clone https://github.com/your-username/dynamic-forecasting.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the main program: `python main.py`
4. Enter the stock ticker symbol when prompted.

## Project Structure
- `main.py`: Main program coordinating user input, data loading, Kalman filter application, and result visualization.
- `kalman_filter.py`: Implementation of the Kalman filter algorithm.
- `plot_results.py`: Function to visualize and compare true and Kalman-filtered stock prices.
- `load_stock_data.py`: Function to load historical stock price data using yfinance.

## Results
After conducting six observations on different stock tickers, the Kalman Filter demonstrates an average MAE of 2.0567 and an average RMSE of 2.6852. The algorithm outperforms a Simple Moving Average model but is slightly less robust than ARIMA.

## Conclusion
In conclusion, the project provides a versatile tool for dynamic forecasting with the Kalman Filter. The algorithm shows efficiency in predicting stock prices over a six-month period, making it suitable for long-term investments.

