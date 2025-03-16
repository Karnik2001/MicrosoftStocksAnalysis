 # Time Series Analysis of Microsoft Stock Prices

## Overview

This project analyzes the historical stock prices of Microsoft using time series techniques. The objective is to explore stock price trends, test for stationarity, and build predictive models using AR and ARIMA techniques.

## Features

Data Preprocessing: Cleans and formats stock price data.

Exploratory Data Analysis (EDA): Visualizes trends and seasonal patterns.

Stationarity Testing: Uses the Augmented Dickey-Fuller (ADF) test.

Time Series Decomposition: Identifies trend, seasonal, and residual components.

Predictive Modeling: Implements AutoRegressive (AR) and Auto ARIMA models.

Performance Evaluation: Assesses models using Mean Squared Error (MSE).

## Dataset

The dataset consists of historical Microsoft stock prices.

Columns used: Date (converted to datetime format) and adjusted stock prices.

## Requirements

Python 3.x

NumPy

Pandas

Matplotlib & Seaborn

Statsmodels

Scikit-learn

pmdarima


## Results

Time series decomposition revealed trends and seasonal patterns.

The ADF test determined whether the data was stationary.

AR and ARIMA models provided future stock price predictions.

Model performance was evaluated using MSE.
