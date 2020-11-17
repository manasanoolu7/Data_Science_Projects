# Car Prize Analysis

## Problem Definition  

Car Price Analysis is most demanded project under machine learning to predict the cost based on many factors like engine type, used/new, year etc.
In this data, we will see how other features depend on price by analysing through feature engineering and models. 

## Objectives

1. Data Understanding
2. Feature Engineering
3. Feature Selection
4. Model Selection
5. Prediction of the model

## Dataset

<b> CarAssignment.csv file contains following features:<b>
  
<i>car_ID,symboling,wheelbase, aspiration, fueltype, CarName, carbody, carlength, doornumber, carwidth, carheight, curbweight, enginesize, boreratio, stroke, compressionratio, horsepower, peakrpm, citympg, highwaympg,price<i>
  
## Observations

1. There are 26 features in total, but I have found that few features are not important based on the correlation with the price feature. This enabled for feature selection which are actually influencing the price for prediction.

2. There are categorical features which are not considered for traning because model needs numeric data. So, features like doornumber which are in text format ('two',four') is converted to numeric values. 

3. I have considered features of type int and float.Now, the total number features are 16 (after feature engineering).

4. Finally, Linear Regression is applied on final dataset to find the accuracy.

