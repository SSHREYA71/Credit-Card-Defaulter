# Credit-Card-Defaulter
The aim of this project is to build a model to predict if the customer is a defaulter or not based on the difference in due date of the payment and the payment date or clear date, i.e. the date on which the payment is done.
# To get the desired result following steps where taken:<br/>

1. Getting data <br/>
2. Data Preprocessing<br/>
3. Visualising the data<br/>
4. Applying Models

# Getting Data:

The first step was to collect a dataset from internet.

# Data Preprocessing:

The most ellaborattive part of this project was the data preprocessing.This step includes removing null values, duplicate values and removing junk from the data along.
Libraries used i this process are : <br/>
(i) Numpy<br/>
(ii) Pandas<br/>
This step also included spliting numerical data from string and converting data type from float to datetime and vice versa.This is done to get the appropriate features for the model.

# Visualising the Data:

Data visualization is the graphical representation of information and data
The Library we used are: <br/>
(i) Seaborn <br/>
(ii) Matplotlib <br/>

# Applying Models:
In this step using Sklearn Library I imported the desired regression models.
Models used  are:<br/>

(i)  Lasso Regression <br/>
(ii) Ridge Regression <br/>
(iii)RandomForest Regression <br/>
(iv) Linear Regression <br/>

After checking the performance we conclude that Linear Regression fit the best. Hence we can use it for best result.


