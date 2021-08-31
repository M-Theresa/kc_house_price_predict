## Project Overview
• Created a machine learning model that **estimates house sale prices for King County based on features like location, square footage, number of floors etc.**<br/>

## How will this project help?
• This project **helps data scientist/analyst to negotiate their income for an existing or a new job**

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn.**<br/>
• Dataset by **Ken Jee**: https://github.com/PlayingNumbers/ds_salary_proj

## Exploratory Data Analysis (EDA) and Data Cleaning
• **Removed unwanted columns**: 'Unnamed: 0'<br/>
• **Plotted bargraphs and countplots** for numerical and categorical features respectively for EDA<br/>
• **Numerical Features** (Rating, Founded): **Replaced NaN or -1 values with mean or meadian based on their distribution**<br/>
![rating](readme-resources/rating.png) ![rating1](readme-resources/rating1.png)<br/>
• **Categorical Features: Replaced NaN or -1 values with 'Other'/'Unknown' category**<br/>
• **Removed unwanted alphabet/special characters from Salary feature**<br/>
• **Converted the Salary column into one scale** i.e from (per hour, per annum, employer provided salary) to (per annum)
