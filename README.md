# A Yen for the Future
The purpose of this homework is to use time-series tools that we have learned to predict future movements in the value of the Japanese yen versus the U.S. dollar.


## `Time-Series Forecasting:`
Use the results of the time series analysis and modeling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now?

> Based on the results of the time series analysis I would buy the yen now since our ARIMA model predicts a rise in yen settle Prices. I do not feel confident in this decison at all, but based on the analysis I think I will buy simply to avoid buying when the price plummets.
 
2. Is the risk of the yen expected to increase or decrease?

> The risk of the yen is expected to increase. The Volatility Forecasting with Garch forecasts a linear increase in volatility. This means as time passes the yen settle price is expected to be more unpredictable.

3. Based on the model evaluation, would you feel confident in using these models for trading?

> I do not feel comfortable in using these models for trading. The p-values for the ARMA and ARIMA models are much higher than 0.05, which means that the models are not a good fit for the data.

## `Linear Regression Forecasting:`

Use the results of the linear regression analysis and modeling to answer the following question:

* Does this model perform better or worse on out-of-sample data compared to in-sample data?

> The model performed better on the out-of-sample data since the RMSE we found here is about 0.4155 which is smaller than the in-sample data RSME of 0.598.