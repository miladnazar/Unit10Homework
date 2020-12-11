# Unit 10—A Yen for the Future

![Yen Photo](Images/yen.jpg)

## Background

In this case I'm working for a financial institution who are interested to know the future prediction of the currency 'Yen'. I have used three models to evaluate this and make my predictions about Yen. ARMA, ARIMA, and Garch are the models I'm using to evaluate data and giving my predictions based on my findings from these models. I want to suggest that Yen prices will be dropping in the next 5 days. The volatility is also increasing so I would not suggest to buy Yen for now. 

1. Time Series Forecasting
2. Linear Regression Modeling


I followed all the below steps in order to carry out this task:
1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
2. Forecasting Returns using an ARMA Model.
3. Forecasting the Settle Price using an ARIMA Model.
4. Forecasting Volatility with GARCH.

Use the results of the time series analysis and modeling to answer the following questions:

1. Based on your time series analysis, would you buy the yen now? No I would not.
2. Is the risk of the yen expected to increase or decrease? It is going to increase. 
3. Based on the model evaluation, would you feel confident in using these models for trading? Yes I would.


#### Linear Regression Forecasting

After using Linear Regression analysis and modeling I would say that this model perform better in both In-Sample or Out-of Sample data. The smaller the RME and RMSE the better the closer the fit is to the data.
