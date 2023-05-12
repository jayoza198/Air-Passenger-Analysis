# Time Series Analysis using Darts Library

This repository contains code for performing time series analysis using the "darts" library in Python. The code demonstrates steps such as exploratory data analysis (EDA), model training, and forecasting. The example dataset used in this code is the "AirPassengers" dataset, which represents the number of airline passengers over time.

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- pandas
- matplotlib
- darts

You can install the libraries using the following command:


``` pip install pandas matplotlib darts ```


Code Explanation

The code performs the following steps:

1. Importing the required libraries and modules.
2. Loading and visualizing the AirPassengers dataset.
3. Performing exploratory data analysis (EDA) to compute basic statistics and visualize the time series.
4. Splitting the data into a training set and a validation set.
5. Training the Exponential Smoothing model, performing a forecast, and evaluating the forecast using Mean Absolute Percentage Error (MAPE).
6. Training the Prophet model, performing a forecast, and evaluating the forecast using MAPE.
7. Training the ARIMA model, performing a forecast, and evaluating the forecast using MAPE.
8. Visualizing the forecasts and actual values for each model.
