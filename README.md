
This Capstone Project was part of Post Graduate Diploma in Data Science.

Rossmann is a European drug distributor which operates over 3,000 drug stores across seven European countries. Since a lot of drugs come with a short shelf life, that is, they do not have a long expiry date, it becomes imperative for Rossmann to accurately forecast sales at their individual stores. Currently, the forecasting is taken care of by the store managers who are tasked with forecasting daily sales for the next six weeks.  

As expected, store sales are influenced by many factors, including promotional campaigns, competition, state holidays, seasonality, and locality.

 
With thousands of individual managers predicting sales based on their unique circumstances and intuitions, the accuracy of the forecasts is quite varied. To overcome this problem, the company has hired you as a data scientist to work on the forecasting problem. As part of your job role, you are tasked with building a forecasting model to forecast the daily sales for the next six weeks. To help you with the same, you have been provided with historical sales data for 1,115 Rossmann stores.

While attempting to forecast sales, it is advisable to keep the following question were kept in mind.

Is the sales data non-stationary? If so, how do you find it and correct it?

Is the data cointegrated? Which variables are cointegrated and how do you find them?

What is the impact of the number of customers on sales?

What is the impact of promo and promo2 variables on sales? How do you measure it?

Forecast sales for the next 6 weeks? Report the accuracy of the model using MAPE.

 

While solving this problem, the following steps were considered as reference:
 

Find outliers at the 99th percentile and remove them.

Standardize the sales and number of customers variables before modelling.

Determine if the data is stationary

If stationary then apply Vector Autoregression Model.

If non-stationary then specify the model in differences

Make sales, promo2 and any other variables you think of as dependent variables.

Check for cointegration using the Johansen test. 

Predict sales for the next 6 weeks.
