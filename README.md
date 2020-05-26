# House Price Prediction using Machine Learning
Here, we are going through a machine learning project which can successfully predict the price of a house, given 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa.

The Colab link: https://colab.research.google.com/drive/10f1QbjAqL7win2BAakY2IRCb-0zZ_4X4

## Approcahes

1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Result

## 1. Problem Definition
How well can we predict the price of a house, given it's characteristics and other important properties.

## 2. Data
The data is downloaded from Kaggle "House Prices: Advanced Regression Techniques" competition.
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

There are 2 important datasets.

* Train.csv is the training set which consists of 1460 data entries and their sale prices
* Test.csv is the test dataset where the ideal model will be tested upon, and has 1459 entries

## 3. Evaluation
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price.

Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.

## 4. Features
Kaggle provides a data dictionary detailing all features of the dataset. See repo data_description.txt

## 5. Result
The model used is RandomForestRegressor with tuned hyperparameters.
The final output (predictions.csv) contains all sales id from test.csv and the predicted price.

Cheers!
