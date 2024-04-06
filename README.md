# STOCK-MARKET-PREDICTION-APP
This is a simple web application built with Streamlit for predicting stock prices using Facebook Prophet. It allows users to select a stock from a predefined list and forecast its prices for a specified number of years.

**FEATURES:**
  - Select from a list of stocks including AAPL, GOOG, MSFT, GME, and AMZN.
  - Choose the number of years for prediction using a slider.
  - View raw stock data and forecasted data.
  - Visualize forecasted data and its components.

**USAGE:**
  - Select a dataset for prediction from the dropdown menu.
  - Adjust the slider to choose the number of years for prediction.
  - View the raw data and forecasted data.
  - Visualize forecasted data and its components using the provided charts.

**CONCEPT USED:**
Time series analysis is utilized as a fundamental concept for stock price prediction. Here's how time series analysis is applied:

*Data Collection:* The project fetches historical stock price data using the yfinance library. This data typically includes a timestamp (date) and the corresponding stock prices (open, close, high, low, volume) over a specific period.
Data Exploration: The fetched data is then explored to understand its structure, trends, and patterns. This step involves visualizing the raw time series data to identify any underlying patterns or seasonality.
*Data Preprocessing:* The data is preprocessed to ensure its quality and compatibility with the forecasting model. This may involve handling missing values, removing outliers, and converting the data into a suitable format for analysis.
*Modeling:* The Facebook Prophet library is used for time series forecasting. Prophet is designed specifically for forecasting time series data that displays patterns such as trends and seasonality. The historical stock price data is used to train the Prophet model.
*Forecasting:* Once the model is trained, it can be used to generate forecasts for future time periods. The project allows users to select the number of years they want to forecast and generates predictions accordingly.
*Visualization:* The forecasted data and its components (trend, seasonality) are visualized using Plotly charts. This enables users to understand the predicted trends and make informed decisions based on the forecasted stock prices.

**TECHNOLOGIES USED:**
  - Python
  - Streamlit
  - Prophet
  - Plotly
  - yfinance
