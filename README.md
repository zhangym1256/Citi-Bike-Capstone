# Citi Bike Capstone Project
Created by:
* Hanbo Shao: [GitHub](https://github.com/shimmer-croissant0707), [LinkedIn](linkedin.com/in/hanbo-shao)
* Xuyuan Zhang: [GitHub](https://github.com/AliceXuyuan), [LinkedIn](linkedin.com/in/xuyuan-zhang)
* Yunmei Zhang: [GitHub](https://github.com/zhangym1256), [LinkedIn](linkedin.com/in/yunmeizhang)


>Unlock a bike.
Unlock New York. 


This project aims to study the factors that have strong impact on Citi Bike ridership, and identify similarity and discrepancy between dock stations. Data used in this study include monthly trip data published by Citi Bike, NYC daily weather from NOAA, and dock capacity from Open Bus. The time span of this analysis covers from Jan 2017 to Dec 2019 from 5am - 10pm when most of activies occured. Due to the size of the original dataset, we took a subset of 5% from each month. Total data include 2.6 M observations and 57 features. Some visualizations are generated in Tableau. If you are interested in the visualizations, feel free to reach out to us via LikedIn.


[**Data_Prepping.ipynb**](https://github.com/shimmer-croissant0707/Citi-Bike-Capstone/blob/master/Data_Prepping.ipynb)

The main purpose of the notebook is to create custome features, merge and clean dataset for EDA. 

[**EDA.ipynb**](https://github.com/shimmer-croissant0707/Citi-Bike-Capstone/blob/master/EDA.ipynb)

This notebook contains exploratory data analysis. It covers analyses such as seasonality trend, weather's impact on bike ridership, and top stations by activity. It also includes K-mean clustering for dock stations. The top 200 stations are selected for machine learning task. 

[**Machine_Learning.ipynb**](https://github.com/shimmer-croissant0707/Citi-Bike-Capstone/blob/master/Machine_Learning.ipynb)

This notebook contains machine learning algorithms including Lasso, XGBoost regression, Gradient Boosting regression and Random Forest classifier. Regression models are used to predict hourly checkout count for the top 200 Citi Bike stations in NYC. Classifier model is used to predict high/low turnover for the top 200 stations. Feature selection is performed and feature importance is outputted.  

[**2nd_Round_EDA.ipynb**](https://github.com/shimmer-croissant0707/Citi-Bike-Capstone/blob/master/2nd_Round_EDA.ipynb)

Second round of EDA is performed using features ranked by the machine learning models.

[**Citi Bike Visualization.pdf**](https://github.com/shimmer-croissant0707/Citi-Bike-Capstone/blob/master/Citi%20Bike%20Visualization.pdf)

This file contains visualizations built in Tableau to show some dynamics of stations through 2017-2019 and during a day. 

**Capstone Presentation.pptx** 

This file contains the presentation slides as a summary of the overall project. 
