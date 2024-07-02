# Machine_Learning
# Stock Price Prediction Project
 Overview
This project aims to predict stock prices using historical data and advanced machine learning techniques. The project utilizes K-Nearest Neighbors (KNN) for both regression and classification, Gradient Descent for linear regression, and XGBoost for enhanced prediction accuracy
Table of Contents
Introduction
Data Collection and Preparation
Model Implementation
KNN Implementation
Gradient Descent for Linear Regression
XGBoost Implementation
Hyperparameter Tuning
Evaluation
Conclusion
Introduction
The objective of this project is to predict stock prices using machine learning models. I implemented KNN for both regression and classification, Gradient Descent, and XGBoost models to achieve this goal.

Data Collection and Preparation
Importing Libraries
I began by importing the necessary libraries for data manipulation, visualization, and model building.

Loading the Data
I utilized real-time stock price data from Quandl, preparing it by selecting the relevant features and the target variable.

Splitting the Data
I split the data into training and testing sets to evaluate my models effectively.

Feature Scaling
Feature scaling was applied to ensure that the features were on the same scale, which is crucial for certain algorithms.

Model Implementation
KNN Implementation
I implemented the K-Nearest Neighbors algorithm to predict stock prices. For regression, KNN predicts the stock price based on the average of the closest data points. For classification, KNN predicts the stock trend (e.g., up or down) based on the majority class of the nearest neighbors.

Gradient Descent for Linear Regression
I implemented gradient descent to train a linear regression model, adjusting the weights iteratively to minimize the prediction error.

XGBoost Implementation
I also implemented the XGBoost model, known for its efficiency and performance, to enhance prediction accuracy.

Hyperparameter Tuning
To improve model performance, I tuned the hyperparameters using GridSearchCV, which helped me find the optimal parameters for my models.

Evaluation
I evaluated my models using the mean squared error (MSE) metric. After hyperparameter tuning, the XGBoost model showed significant improvement and provided the best performance among all the models tested.

Conclusion
This project successfully demonstrates the use of KNN for both regression and classification, Gradient Descent, and XGBoost for stock price prediction. The models were evaluated using mean squared error, with XGBoost showing improved performance after hyperparameter tuning.

Check out the full project on my GitHub Repository.

Feel free to reach out if you have any questions or suggestions!
