# Stock Price Prediction using ARIMA

This project focuses on forecasting stock prices using **Time Series Analysis and ARIMA (AutoRegressive Integrated Moving Average)**.

The project analyzes historical stock price data and builds an ARIMA model to forecast future prices.

## Project Overview

The analysis includes time-series decomposition, ARIMA parameter optimization, model training, forecasting, and performance evaluation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## Project Workflow

1. Load historical stock price data
2. Explore the stock price dataset
3. Perform time-series decomposition
4. Analyze:
   - Trend
   - Seasonality
   - Residuals
5. Search for the best ARIMA `(p, d, q)` parameters
6. Select the model with the lowest AIC
7. Split the dataset into:
   - 80% Training data
   - 20% Testing data
8. Train the ARIMA model on the training data
9. Forecast stock prices for the test period
10. Evaluate the forecasting performance using:
    - Mean Squared Error (MSE)
    - Root Mean Squared Error (RMSE)
11. Visualize actual vs forecasted stock prices

## Model

The project uses the **ARIMA** model for time-series forecasting.

The `(p, d, q)` parameters are selected through a grid search by comparing the **Akaike Information Criterion (AIC)** of different ARIMA models.

## Evaluation

The model is evaluated by comparing the predicted stock prices with the actual prices from the test dataset.

Evaluation metrics:

- MSE
- RMSE

## Visualization

The project includes visualizations for:

- Time-series decomposition
- Historical stock prices
- Actual vs forecasted prices
- ARIMA forecast

## Conclusion

This project demonstrates the application of time-series analysis and ARIMA modeling for stock price forecasting. It provides an end-to-end workflow from historical price analysis and model selection to forecasting and performance evaluation.
