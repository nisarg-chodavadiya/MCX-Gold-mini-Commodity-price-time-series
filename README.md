# MCX Gold mini commodity price time series
Extensive EDA on historical price and time series forecasting by facebook prophet with seasonality and forecast to next 180 days.
 
# Dataset
I got this data on https://in.investing.com/commodities/gold-mini-historical-data 
It was original data I got.</br>
![DataFrame gold](https://user-images.githubusercontent.com/75474944/117965811-cfc4eb80-b340-11eb-871c-3941291801db.PNG)</br>
 
# Preprocessing
In this preprocessing I changed the data type of all features and I removed “,” from numbers of price and sort by date.</br>
![Final data frame gold](https://user-images.githubusercontent.com/75474944/117965821-d2274580-b340-11eb-9034-8330d479b96d.PNG)</br>
I am putting this dataset to kaggle with only single raw with daily price: https://www.kaggle.com/nisargchodavadiya/daily-gold-price-20152021-time-series
 
# EDA
Visualizing prices and changes to make sense to trends superficially before time series forecasting.
One of is:
![Gold Price](https://user-images.githubusercontent.com/75474944/117966153-39dd9080-b341-11eb-81d4-f25cf1c13833.png)
![high low %](https://user-images.githubusercontent.com/75474944/117965582-8ffe0400-b340-11eb-8c86-8f5003bbaf66.png)
 
#  Time Series Forecasting in Facebook Prophet
Time series forecasting of price and predict next 180 days.
![Forecast](https://user-images.githubusercontent.com/75474944/117965627-a015e380-b340-11eb-8df3-d463447605b7.png)
 
# Seasonality
Trends of gold prices.</br>
![Trends gold price](https://user-images.githubusercontent.com/75474944/117965725-b885fe00-b340-11eb-98ec-757bca6f9e1f.png)
 
---
