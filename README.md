# Surprise Housing Price Predictions
Model to predict house prices for Surprise Housing company in a new region that can help the company in making the right investment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

- What is the background of your project?
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: 
1) Which variables are significant in predicting the price of a house, and
2) How well those variables describe the price of a house.


## Conclusions

i) Optimal value of ridge regression = 6
Optimal value of ridge regression = 0.0001

ii) R2 Score for Ridge:
Train - 0.934390 
Test - 0.896722 

iii) R2 Score for Lasso:
Train - 0.944886  
Test - 0.896294 

iv) Most important Predictor variable based on both the models is GrLivArea
Ridge model has been chosen due to the high number of predictor variables.

## Technologies Used
- Python - Ver 3.11.5

## Contact
Created by [@sireeshatumpati9] - feel free to contact me!
