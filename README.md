![DSSP](https://github.com/M-Theresa/kc_house_price_predict/blob/21ce27d888fe8486fe360f499381e10a881869a0/housing.jpeg)
## Project Overview
Created a machine learning model that estimates house sale prices for King County based on features like location, square footage, number of floors etc.<br/>

## How will this project help?
This project helps house sellers/buyers who live in King County determine how much a house is worth

## Resources Used
Packages: **pandas, numpy, sklearn, matplotlib, seaborn.**<br/>
Dataset: house price sold between May 2014 and May 2015 in King County

## Data Cleaning
* Removed `bedrooms` and `bathrooms` column with `NaN` values from the dataset, as the number of bedroom and bathrooms would impact the price and unable to obtain the missing value
* Removed features that don't affect the price
* Based on price distribution plot, removed outliers

## Explanatory Data Analysis
* plot distribution plot and box plot for categorical and discrete variables, and how they correlate to price
* plot distribution plot and scatter plot for continuous variables, and how they correlate to price
* Calculated correlation coefficient and ploted masked heat map
![heatmap](https://github.com/M-Theresa/kc_house_price_predict/blob/76832c6e84e5db8ea7b949314c736b186f4eea0e/correlation_heat_map_2.png)

## Model Building and Evaluation
* Linear Regression: R^2 score is 0.69
* 2nd Degree Polynomial with normalization: R^2 score is 0.84
* Ridge Regression with alpha = 0 and no normalization: R^2 score is 0.83
* Plotted distribution plot of actual value vs different models and determined 2nd Degree Polynomial produces best estimate
![distribution Plot](https://github.com/M-Theresa/kc_house_price_predict/blob/76832c6e84e5db8ea7b949314c736b186f4eea0e/distribution_plot.png)
