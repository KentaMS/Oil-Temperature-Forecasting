# Oil-Temperature-Forecasting
Project carried out during the first graduate year (2024) at Paris Cité University.

This Time Series Classification project was first submitted on Kaggle to evaluate the results of the program using the Mean Absolute Error (MAE) metric.

We were provided two different ETTh1 datasets for the two parts of the project.

## Part A (https://www.kaggle.com/competitions/time-series-classification-part-1/overview)
The **ETTh1_without_missing.csv** dataset was provided for this part.

"The first step aims to train a predictor to accurately predict the next 100 values, resulting in a simple univariate forecasting problem. For this purpose, you’ll need to preprocess the data and cut the dataset into a set of subsequences of the form (input, target) for training.

The training data consists of one univariate time series with 1 feature. The objective is to forecast the feature ‘OT’. ‘OT’ refers to the temperature of the oil in the transformer, which is crucial for cooling and operational efficiency.

There are no missing values in the dataset."

## Part B (https://www.kaggle.com/competitions/time-series-classification-part-2new/overview)
The **exchange_rate_with_missing.csv** dataset was provided for this part.

"The second step aims to provide a predictor to accurately forecast the next 100 values of a daily exchange rate. For this purpose, you still need to preprocess the data, cut the dataset and also to handle the missing values.

The training data consists of one multivariate time series with 8 features. The objective is to forecast the ‘6’th feature. The features between 0 and 6 represent different currencies or different countries' exchange rates relative to a base currency. ‘OT’ in this context does not stand for "Oil Temperature" as in the ETTh1 dataset, it represents an additional variable or feature not directly related to the exchange rates, such as an external factor influencing exchange rates.

You can use multiple features during training if you think they are useful.

The dataset contains 25% of missing values."
