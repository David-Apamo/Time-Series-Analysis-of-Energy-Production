# Time-Series-Analysis-of-Energy-Production
This repository contains files for time series analysis of global energy production data. The analysis focuses on electricity production from 1985 to 2018. Using Holt Winter's Exponential Smoothing and ARIMA modeling techniques, decomposition, and trend analysis, this project explores patterns in energy consumption and forecasts future trends.

## Contents
* Data Preprocessing: Cleaning and preparing time series data for analysis.
* Visualization: Plotting trends, seasonality, and forecasted values to illustrate insights.
* Modeling: Building Holt Winter's Exponential Smoothing and Seasonal ARIMA models for forecasting, and performing model diagnostics to check if model assumptions hold.
* Forecasting: Predicting future energy production based on historical trends.
## Results
Best performing model is Seasonal ARIMA model: Yt^=0.5207Yt−1−0.4695Yt−12−0.9235et−1−0.2354et−12−0.4608et−24+E, with a validation RMSE value of 3.5. This implies that the predictions made by the SARIMA model would be off by 3.5 (plus or minus).

## Tools and Libraries
RStudio Software. (tidyverse, ggfortify, tseries, forecast)

# Contributions
Contributions to enhance the functionality and reliability of the models are welcome. Please fork the repository, make your changes, and submit a pull request. For significant changes, please open an issue first to discuss your proposed modifications.
