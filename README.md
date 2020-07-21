# Daily total female births in California, 1959 - Time Series Analysis.
## Context
A time series dataset depicting the total number of female births recording in California, USA during the year of 1959.Predicting Female birth rate in California
## Objective

* In this challenge, we will complete the Time Series analysis and predict Female birth in California using ARIMA model

## Methodology

* First attempt at implenting the learning of prediction using Time Series analysis.
* Downloaded the data and checked if the data is sationary, which it wasnt. It had a upaward trend.
* Simple prediction using shift() was used a s abaseline model.
* ARIMA Model was used for analysis
* plot_acf and plot_pacf was used to calculate pand q value respectively.
* A function evaluate_arima_model() was used to hyper tune the values of p,d and q
