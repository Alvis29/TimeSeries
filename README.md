# Problem Statement : Forecast 1 year of data.
the purpose of this project is to build a Time Series model on a given dataset to forecast 1 year of data for each variable.


## Goals of the Project:

1. Get the dataset .
2. Clean the dataset with python and pandas framework.
3. Deal with the missing values if any present in the dataset.
4. Visualize the dataset with decompositon plot .
5. Get insights from the dataset after EDA.
6. With the help of EDA insights make dataset ready for the model building.
7. Split the dataset into Train and Test data. and prepare train and test data for machine learning model.
8. Try prefered time series models on a train set and evaluate the model with the help of Sklearn framework.
9. Choose the best working models with respect to this dataset.
10. Forecast 1 year of dataq for each variable.

## Materials and methods: 
The data that we are going to use for this project is already given in the repository. or you can download the dataset from https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data

#### About this Dataset: 

The Dataset is fully dedicated for the developers who want to train the model on Weather Forecasting for Indian climate. This dataset provides data from 1st January 2013 to 24th April 2017 in the city of Delhi, India. The 4 parameters here are
meantemp, humidity, wind_speed, meanpressure.


## Task
In this project, we will choose the best time series model and forecast 1 year of data for each variable.


1. EDA

    1.check any duplicates in date column
    2.check any null values in date column
    3.convert 'date' column from object to datetime and set it as index
    4.sort the data in ascending dates
    5.plot the decomposition graph of Each y variable and check for trend and seasonality in the data.
    6.with the help of decomposition plot we will chose prefered timeseries models
   
3. MODEL BUILDING

  with the help of statsmodels library we will try to build a time series model such that it forecast values for each variable .

  machine learning model we tried for the dataset :

    1. Holt-Winter model
    2. SARIMAX model


## USED LIBRARIES:
1. NUMPY
2. PANDAS
3. MATPLOTLIB
4. SEABORN
5. SKLEARN
6. statsmodels
7. 7.pmdarima
