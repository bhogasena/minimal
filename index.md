# Machine Learning & Artificial Intelligence Portfolio
---
## Exploratory Data Analysis

### 1. Loan Defauters Driving Factors Analysis

The following notebook contains a typical exploratory data Analsyis steps starting from Data Cleaning, Standardise values, filter data, derive new variables, Univariate, Segmented Univariate, Bivariate Analysis and rendering of different plots using matplotlib, plotly and seaborn.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/bhogasena/Loan_Default_Analysis)

<center><img src="assets/img/EDA.jpg"/></center>

## Multiple Linear Regression

---
### 2. Bike Sharing Prediction using Simple Linear Regression
--- 

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

Compnay wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

The company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands.

This note book consists of complete end to end steps to solve the business problem by following the CRISP-DM framework starting from business understanding, data understanding, data visualization, data cleaning,  building linear regression model manually to select the features based on statistics (P-values and Variance Inflation Factor (VIF), Analyze the residuals, evaluate the model. 

Notebook also consists of automated feature selection model, for which I started with Hyper parameter tuning using Grid search view cross validation in order to find out the optimal number of features followed by Recursive Feature Elimination (RFE) to select the top significant features and then build and evaluate the model. 
I ended of having almost same statistics for both manually selected features and RFE (Recursive Feature Elimination) model.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/bhogasena/BikeSharingDemad)

<center><img src="assets/img/Bikes.jpg"/></center>

---


### 3. Advanced Regression model using Ridge and Lasso Regularisation for House Prices Prediction

--- 
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

*   Which variables are significant in predicting the price of a house, and
*   How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

Notebook consists of end to end steps to solve the business problem by following the CRISP-DM framework starting from business understanding, data understanding, data visualization, data cleaning, Build a regression model using Ridge and Lasso regularisation to find the optimal alpha parameters and then finally build a models with optimal alpha values using Ridge and Lasso. Lasso model got R2-Score better than Ridge model, and also as Lasso model shrinks some of the coefficients to zero which eliminates some of the features and so it would be the best choice to choose for this business problem.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/bhogasena/House-Price-Prediction)

<center><img src="assets/img/house_price.jpg"/></center>

