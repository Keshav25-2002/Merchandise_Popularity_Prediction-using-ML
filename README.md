# Merchandise_Popularity_Prediction-using-ML

This is a machine learning project that predicts the popularity of merchandise based on various features. The goal of this project is to help businesses in the e-

commerce industry identify which products are likely to be popular among customers, so they can optimize their inventory management and marketing strategies.

Dataset

The dataset used in this project contains information on various merchandise products sold by a fictional e-commerce company. Each record in the dataset represents a 

single product and contains the following information:

Product ID

Product Category

Date of Manufacture

Manufacturer

Brand

Price

Discount

Rating

Reviews

Popularity

The last column, Popularity, is the target variable that we want to predict.

Methodology

This project uses a supervised learning approach to predict the popularity of merchandise. Specifically, we train several machine learning models on the given dataset 

and evaluate their performance using various metrics such as accuracy, precision, recall, and F1 score. We also use techniques such as cross-validation and 

hyperparameter tuning to optimize the models.

The models used in this project include:

Random Forest

XGBoost

Support Vector Machine

K-Nearest Neighbors

Technologies Used

This project was implemented using Python and various libraries including:

NumPy

Pandas

Scikit-learn

XGBoost

Results:

After evaluating the performance of various models, we found that the XGBoost model performed the best with an accuracy of 85%. This model was then used to predict the 

popularity of new merchandise products and achieved an accuracy of 83% on the test data.

Future Work

Some potential future improvements to this project include:


Gathering more data on merchandise products to improve the accuracy of the predictions

Using deep learning techniques such as neural networks to improve the performance of the models

Developing a web application that allows businesses to input data on their merchandise products and get predictions on their 
