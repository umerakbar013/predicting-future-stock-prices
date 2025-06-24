# predicting-future-stock-prices
internship task @developersHub.co
Task Objective
Predict the next day's closing stock price using historical stock data. This short-term forecasting model helps understand how well machine learning can model financial time series data.

 Dataset Used
Historical stock data retrieved using the yfinance library from Yahoo Finance.

Example stock: AAPL (Apple Inc.)

Date range: 2022 to 2024

Features used: Open, High, Low, Volume

Target: Next Day's Close Price

MODEL USED:

Linear Regression (basic baseline)


Key Results and Findings
Model Performance (Linear Regression):

R² Score: ~0.95 (varies by stock/date)

Mean Squared Error was low, indicating a good fit on recent data.

Visual Comparison:

Actual vs. predicted prices show strong overlap in stable market conditions.

Model tends to underperform in highly volatile periods (as expected with linear models).

