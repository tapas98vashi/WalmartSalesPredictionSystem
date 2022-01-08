# WalmartSalesPredictionSystem
The objective is to predict the weekly sales of Walmart stores across different locations in the USA and Canada. To analyse how internal and external factors can affect the Weekly Sales in the future. To provide recommended actions based on the insights drawn, with prioritization placed on largest business impact.

This Walmart Sales Prediction dataset is taken from Kaggle Data Analytics Competetion. Walmart, an American retailer, provided the information for the database. 

It's made up from all the data from 45 Walmart locations, all of which have been based on their current sales. It has 421,517 samples which will be employed to build the original study algorithm on a regular basis.

This dataset has multiple csv files which is ultimately merged into one csv files. Following csv files were used:

1) Features.csv

2) Stores.csv

3) Train.csv

4) Test.csv


My approach to the problem statement:

Download Dataset
Import necessary libraries

Data Exploration
Identifying input variables and target variable

Data Cleaning
Identifying null values

Checking correlation of all input variables with target variables

Data Manipulation
Removing null values and also removing variables with low correlation found in other steps

Reviewing different models such as Decision Tree or Random Forests
I selected Random Forests for better results

Conclusion:

Fuel Price and temperature(extreme weather conditions) makes a positive impact on sales. Higher the fuel prices makes higher sales.

Similarly, CPI and Unemployment rate having a major negative impact on weekly sales. The higher CPI and employment rate results into less weekly sales.

Holiday also affects weekly sales slightly. But promotions and discount are the major factors which helps to increase sales.
