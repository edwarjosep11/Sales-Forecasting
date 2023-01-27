# Project Overview

This project aims to use time series forecasting to predict the sales of Corporación Favorita, a large Ecuadorian-based grocery retailer. The project utilizes a training dataset that includes dates, store, and item information, promotions, and unit sales to build a model that can accurately predict sales of different "families" of products.

 
## 1. Data

The data provided includes the details of 54 stores and 33 product families, with time series starting from 2013-01-01 and ending in 2017-08-31. There are 6 different types of data: train, test, store, transactions, holidays and events, and daily oil price. The data is available at Kaggle competitions. 

## 2. Impact

If successful, this project can decrease food waste related to overstocking and improve customer satisfaction for retail businesses. The results of this project can also help retailers have the right products available at the right time.

## 3. How to Use

Please follow the instructions in the Jupyter notebook to run the model and see the results.

## 4. Dependencies

The project requires the following libraries to be installed:

  - numpy
  - pandas
  - matplotlib
  - seaborn
  - sklearn
  - os
  - xgboost
  - statsmodels
  - ipywidgets
  - learn-tools

Additionally, the project makes use of the following modules:

  - LinearRegression
  - Path
  - warnings
  - DeterministicProcess
  - CalendarFourier
  - plot_pacf
  - LabelEncoder
  - XGBRegressor
  - ElasticNet
  - Lasso
  - Ridge
  - KNeighborsRegressor
  - MultiOutputRegressor

## 4. Additional Notes
Additional packages used for data visualization, models and other functions
Some of the most attractive libraries used in the project are xgboost, statsmodels and ipywidgets as they play a key role in improving the performance of the model and providing interactive visualization tools.

## 5. References
 - https://www.kaggle.com/code/ryanholbrook/forecasting-with-machine-learning
 - https://www.kaggle.com/code/howoojang/first-kaggle-notebook-following-ts-tutorial/notebook
 - https://www.kaggle.com/code/maricinnamon/store-sales-time-series-forecast-visualization/notebook#4.-Time-Series-as-Features
 - https://www.kaggle.com/code/kashishrastogi/store-sales-analysis-time-serie?scriptVersionId=81112640

