# Store Sales - Time Series Forecasting

In this project, we present machine learning techniques to predict store sales in the "Store Sales - Time Series Forecasting" competition [1] on Kaggle. We were asked to forecast 15 days (2017-08-16 to 2017-08-31) of store sales for Corporación Favorita , a large Ecuadorian-based grocery retailer. The provided data consisted of the past sales for 33 families of items from 54 stores over the period of 2013-01-01 to 2017-08-15. Additionally, we were given information on past oil prices, holidays, and store locations to potentially aid our forecast. 
We began by determining a baseline score with a basic linear regression model. With this score in mind, we experimented with decision tree-based models. After unimpressive results , we further explored the provided datasets to identify potential trends, seasonal patterns, and features that were relevant to the forecast. Finally, we trained various models on our enriched feature set and settled on the one that gave us our best score: a version of an ExtraTreesRegressor.

This project was done towards coursework of CSCI 567: Machine Learning, taught by Prof. Vatsal Sharan, during Fall 2022, at University of Southern California.

Team Members:
- Sai Anuroop Kesanapalli
- Prashanth Ravichandar
- Gaurav Aidasani
- Kyle Manke

[1] Alexis Cook et al. Store sales - time series forecasting, 2021. URL https://kaggle.com/competitions/store-sales-time-series-forecasting.
