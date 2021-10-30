# Time Series Analysis

## Background
Using different time-series tools (Hodrick-Prescott Filter, ARMA model, GARCH model, linear regression, etc.), the projects seeks to predict future values of exchanges between Japanese Yen and Canadian dollar.

 
## Time Series Analysis
First by loading the historical data between Yen and CAD, I tried to determine if there is any trends or predictable patterns, Using the Hodrick-Prescott Filter to divide the price into trend and noise then forecasting the returns with Arima model then later with the Garch model.
Conclustions are drawn after each method and towards the end.

## Regression Analysis
Using the Scikit-Learn linear regression model I tried to predict the price of Yen over an estimated period.
The out-of-sample RMSE is lower than the in-sample RMSE, it should be lower for training data. It fits better for the out-of sample than in-sample.
