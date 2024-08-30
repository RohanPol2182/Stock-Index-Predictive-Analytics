# Stock-Index-Predictive-Analytics

## Project overview:

This project consists of testing various machine learning algorithms to predict the prices of Nifty stock index (NSE). 

## Tools used: 

>Languages: Python

>Libraries: Pandas, Matplotlib, NumPy, scikitlearn, statsmodels, yfinance

>IDE: Jupyter Notebook

## Data Source: 

Historical Nifty price data was obtained from Yahoo Finance using the yfinance library.

## Information about the dataset:

The dataset contains historical Nifty stock prices, typically including the following columns:
Date: The date of the trading day.
Open: The opening price of the Nifty index on that day.
High: The highest price reached during the day.
Low: The lowest price reached during the day.
Close: The closing price of the Nifty index on that day.
Adj Close: The adjusted closing price, accounting for any stock splits or dividends.
Volume: The total number of shares traded during the day.

## Analysis:

>Data Cleaning and Preprocessing

Handled missing values and ensured data consistency.
Converted the 'Date' column to datetime format and set it as the index.
Calculated technical indicators such as Simple Moving Averages (SMA), Exponential Moving Averages (EMA), Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD).

>Exploratory Data Analysis (EDA)

Calculated and visualized descriptive statistics of the Nifty data.
Plotted the historical closing prices to observe trends and patterns.
Visualized the calculated technical indicators to gain further insights.
Modeling and Prediction

Split the data into training and testing sets.
Trained and evaluated a Linear Regression model to predict future Nifty closing prices.
Explored the use of Prophet, ARIMA (AutoRegressive Integrated Moving Average) models for forecasting.

>Evaluation

Calculated evaluation metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess the performance of the models.
Visualized actual vs. predicted values to understand the model's fit.

>Future Work

Experiment with other models: Explore and evaluate the performance of other time series models (SARIMA) and machine learning models (LSTM, Random Forest, XGBoost).
Hyperparameter tuning: Fine-tune the hyperparameters of the models to potentially improve their performance.
Incorporate additional features: Consider including other potentially relevant features such as macroeconomic indicators or sentiment analysis data.
Ensemble models: Combine the predictions of multiple models to potentially achieve better accuracy.
Deploy and monitor: Implement a system to make real-time predictions and monitor the model's performance over time, updating it as needed.

