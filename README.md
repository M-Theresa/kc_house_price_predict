## Project Overview
Created a machine learning model that **estimates house sale prices for King County based on features like location, square footage, number of floors etc.**<br/>

## How will this project help?
This project **helps house sellers/buyers who live in King County determine how much a house is worth**

## Resources Used
Packages: **pandas, numpy, sklearn, matplotlib, seaborn.**<br/>
Dataset: house price sold between May 2014 and May 2015 in King County

## Exploratory Data Analysis (EDA) and Data Cleaning
* Replaced NaN values with the mean value
* Removed unwanted columns
* Calculated correlation coefficient and ploted masked heat map
* Ploted box plots for categorical variables

## Model Building and Evaluation
* Linear Regression: R^2 score is 0.69
* 2nd Degree Polynomial with normalization: R^2 score is 0.84
* Ridge Regression with alpha = 0 and no normalization: R^2 score is 0.83
