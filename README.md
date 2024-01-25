
# Black Friday Sales Prediction ML Project

## Problem Statement
A retail company, "ABC Private Limited," aims to understand customer purchase behavior, specifically focusing on the purchase amount against various products across different categories. The company has provided a purchase summary of various customers for selected high-volume products from the last month. The dataset includes customer demographics (age, gender, marital status, city type, stay in the current city), product details (product_id and product category), and total purchase_amount from the last month. The objective is to build a predictive model that can forecast the purchase amount for customers across different products, enabling the company to create personalized offers.

## Cleaning and Analyzing
The dataset requires cleaning and analysis, addressing issues such as:

1) Null values in product category 2 (31% of rows) and product category 3 (70% of rows).
2) Removal of product category 3 and filling the mean in NAs in product category 2.
3) Elimination of duplicates.

## Univariate Analysis
1) Males tend to make more purchases than females.
2) The age group 26-35 accounts for the majority of purchases.
3) Most purchases are made by individuals with occupation no. 4, followed by no. 0.
4) City B sees the highest number of purchases.
5) Individuals with a maximum stay of 1 year in their current city make the most purchases.
6) People with marital status 0 make more purchases than those with status 1.
7) The most popular product categories are 5, 1, and 8 for category 1, and 9 for category 2.
8) Most purchases fall within the amount range of 5,000 to 10,000.

## Bivariate and Multivariate Analysis
1) The total maximum purchase amount is highest for individuals with occupation no. 4, followed by no. 0 and 7.
2) Males contribute to the highest total maximum purchase amount.
3) The age group 26-35 dominates the total maximum purchase amount.
4) City B shows the highest total maximum purchase amount.
5) Individuals with a stay of 1 year in the current city have the highest total maximum purchase amount.
6) Marital status 0 correlates with a higher total maximum purchase amount.
7) Product Category 1 has the highest total maximum purchase amount.

## ML Models Used
Various machine learning models were employed, including:

1) Linear Regression
2) Random Forest Regressor
3) Gradient Boosting Regressor
4) XGBoost Regressor


Among these, the XGBoost Regressor outperformed the others, indicating its potential for predicting future selling purchases more accurately. There is also room for further improvement in the model's performance.






