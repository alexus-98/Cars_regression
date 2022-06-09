# Cars_regression

#### This is a part of final project for the Machine Learning 2 course at University of Warsaw that focuses on a regression problem. The whole project was prepared jointly with my colleague - Marian Nehrebecki. I was responsible for the regression part and Marian for the classification problem, that was prepared in R Studio.

In this part of the project we want to show different machine learning approaches in a regression problem. The main goal is to build a model which will predict a price of a car, based on the given set of features. The dataset was downloaded from Kaggle and contains information about more than 38 thousand cars that was scraped from the Belarusian listing website in December 2019.

The project can be divided into 2 main parts. In the first part we cover Exploratory Data Analysis and Data Preprocessing. We present graphically and numerically how every single variable is related to the price of a car and we draw preliminary conclusions about the effects of certain features. Additionally, we perform one-hot encoding and delete observations with missing data.

In the second part, after the data is prepared appropriately, we build three different types of models: Linear Regression, Regression Tree and XGBoost. We perform cross-validation, present some insights from the model learning process (for Regression Tree model) and build models with different set of parameters. At the end of each section we present how the model performed on the testing sample by measuring the size of the errors (with the Mean Absolute Error).
