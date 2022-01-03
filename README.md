# Project 2 - Ames Housing Data and Kaggle Challenge

### Problem Statement

What factor has the highest impact in predicting prices in the Ames, Iowa housing market?

### Background

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses in Ames, Iowa.

In this challenge, you will use the well known Ames housing data to create a regression model that predicts the price of houses in Ames, IA. You should feel free to use any and all features that are present in this dataset.

It is your job to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable.

### Datasets

* [`test.csv`](./data/test.csv): Test Portion of the Housing Market in Ames, Iowa Data Set 
* [`train.csv`](./data/train.csv): Train Portion of the Housing Market in Ames, Iowa Data Set 

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**sat_2017**|*list of pandas DataFrames*|SAT Scores from 2017|US nation-wide SAT Scores from 2017 with data on Math and EBRW scores.| 
|**sat_2018**|*list of pandas DataFrames*|SAT Scores from 2018|US nation-wide SAT Scores from 2018 with data on Math and EBRW scores.|
|**sat_2019**|*list of pandas DataFrames*|SAT Scores from 2019|US nation-wide SAT Scores from 2019 with data on Math and EBRW scores.|
|**east_states**|*tuple*|East States in Question|States included: New York, Maryland, and Massechusetts|
|**west_states**|*tuple*|West States in Question|States included: California, Oregon, and Washington|
|**east_2017_math**|*int*|2017 Average East Math Score|Average East Coast Math section score from the SATs in 2017|
|**west_2017_math**|*int*|2017 Average West Math Score|Average West Coast Math section score from the SATs in 2017|
|**east_2017_ebrw**|*int*|2017 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2017|
|**west_2017_ebrw**|*int*|2017 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2017|
|**east_2018_math**|*int*|2018 Average East Math Score|Average East Coast Math section score from the SATs in 2018|
|**west_2018_math**|*int*|2018 Average West Math Score|Average West Coast Math section score from the SATs in 2018|
|**east_2018_ebrw**|*int*|2018 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2018|
|**west_2018_ebrw**|*int*|2018 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2018|
|**east_2019_math**|*int*|2019 Average East Math Score|Average East Coast Math section score from the SATs in 2019|
|**west_2019_math**|*int*|2019 Average West Math Score|Average West Coast Math section score from the SATs in 2019|
|**east_2019_ebrw**|*int*|2019 Average East EBRW Score|Average East Coast EBRW section score from the SATs in 2019|
|**west_2019_ebrw**|*int*|2019 Average West EBRW Score|Average West Coast EBRW section score from the SATs in 2019|

### Analysis

Overall square footage of the inside of the properties found to be positively correlated (0.83) to the sale price and are statistically significant shown in the previous graphs.
Similar with overall build quality(0.8), they were also important to help determine housing prices.

### Conclusion

Stakeholders should look for properties that have “very excellent” overall quality as well as high square footage. Finding properties with these qualities tend to have higher sale prices. 
In regards to moving this project further, I would do more cleaning and exploratory analysis. Grouping more columns, getting rid of outliers,  and getting into neighbors more. Getting a neighbors figure showing the desired neighborhoods.
