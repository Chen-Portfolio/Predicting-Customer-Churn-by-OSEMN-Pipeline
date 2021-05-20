# Predicting-Customer-Churn-by-OSEMN-Pipeline
## Table of Content
  - [Project Overview](#projectoverview)
  - [Data Description](#datadescription)
  - [Technical Overview](#technicaloverview)
  - [Results](#results)
  
***

<a id='projectoverview'></a>
## Project Overview

In this project, 10000 customers' demographic as well as bank account realted information from a bank have been analyzed in order to establish a model to predict if a new customer will churn or not. This project aims to help the marketing department of a company to come up with marketing strategy and measures to keep the customers which have potential to churn. 


This project is mainly divided into five steps based on the data science pipeline "OSEMN":

1. `Obtaining the Data` in this part, the dataset was imported from a csv file.

2. `Srubbing the Data` in this part, missing values were examined and impurted, column names were renamed for better understanding, data types were changed for applying the model, as well as some unnecessary columns were dropped. 

3. `Exploring the Data` in this part, descriptive statistics were examined for numerical type of the data. Then, in order to examine the correlationship among featues, a heatmap was plotted. Moreover, various visualization were plotted for univariate and bivariate data. 

4. `Applying Ligistic Regression Model` in this part, encoding the categorical variables were implemented first; then by using Tree based selection method, the top 5 features in the order of importance were selected to be fitted in the logistic regression model. Last, the model was evaluated by accuracy. 

5. `Interpreting the Data` in this part, based on all the above analysis, the insights were provided. 

<a id='datadescription'></a>
## Data Description

The dataset contains more than 10000 customers demographic and bank account information consited of 10000 rows. For each customer, it contains CustomerId, gender, age, estimated salary, tenure, balance, credit rate, and churn or not, etc. 


<a id='technicaloverview'></a>
## Technical Overview

The main technical skills included in this project are: 

* Dealing wiht Missing Data
* Exploratory Data Analysis
* Tree Based Feature Selection
* Logistic Regression Model
* Evaluate the Model by Accuracy

<a id='results'></a>
## Results

The results have been clearly documented in the Jupyter Notebook. Please refer to [Predicting_Customer_Churn_Workbook.ipynb](Predicting_Customer_Churn_Workbook.ipynb). 
