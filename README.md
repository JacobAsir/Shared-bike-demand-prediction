I have made this Shared bike demand Prediction Model using Linear Regression which is a supervised learning algorithm.

📌 Introduction:
Linear regression is used when we want to make predictions for continuous variables (in our case it's cnt). The dependent variable (or target column) is predicted based on how the value of the independent variable is changing according to the value of the dependent variable.

📌 Objective:
A machine learning model is to be proposed to predict a shared bike demand based on data related to this.

📌 Data:
This data has 730 rows and 16 columns that are instant, dteday, season,	yr,	mnth,	holiday, weekday, workingday,	weathersit,	temp,	atemp, hum,	windspeed, casual, registered,	cnt 

📌 Steps followed are:

📍 Applied data preprocessing and preparation techniques in order to obtain clean data which includes following steps:

1. Importing and understanding of data
2. Missing value check
3. Correlation Check
4. Data Reduction
5. Data Cleaning/Wrangling
6. Feature Engineering
7. Univariate Analysis
8. Bivariate Analysis

📍 Built machine learning model to be able to predict shared bike demand based on the features using Linear regression

1. Splitting data into training and testing data
2. Building and training the model
3. Making predictions from the model
4. Testing the performance of the model -> There are three main performance metrics used for regression machine learning models:
a. R square/Adjusted R square
b. Mean absolute percenatge error (MAPE)
c. Root mean square error (RMSE)

📌 Model Evaluation:
Linear regression performed well giving a testing accuracy of almost 85% along with R square values around 0.81.
