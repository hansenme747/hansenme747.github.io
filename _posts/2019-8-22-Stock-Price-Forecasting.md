---
layout: post
title: ExxonMobil Stock Price Forecast and Tableau What-if Dashboard

---

# Goal

The goal of this project was to model the stock prices of ExxonMobil. Forecast was created on 3/1/19.
* The model was generated using ARIMA and time series forecasting modules in Alteryx and fed into a linear regression model
* The output of the linear regession was then exported to tableau for a what-if analysis
* Below is the screenshot of the dashboard, where the modeled stock prices is transposed onto the actual stock prices
* A limited number of predictor parameters from the linear regression model (future month, crude oil, gas, CPI) are made availbe to change dynamically. The dashboard will update the predicted stock price based on the changed parameters. 



![](/images/xom_forecast.png)
