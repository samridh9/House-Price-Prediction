# House Price Prediction

This project aims to predict house prices using various machine learning techniques. The model is trained on a dataset with multiple features related to house properties and evaluated based on metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

Table of Contents

Introduction

Usage

Model Training and Evaluation

Results

Introduction

This project utilizes machine learning to predict house prices based on various features such as square footage, number of bathrooms, number of balconies, and more. The model is trained using the Gradient Boosting Regressor algorithm and optimized using grid search.

Usage

Training the Model - 
Train the model and perform hyperparameter tuning using GridSearchCV. The best model is saved to a compressed pickle file.

Loading and Using the Model - 
Load the trained model from the pickle file and use it to make predictions. Evaluate the model's performance using metrics such as MSE, RMSE, and R² Score.

Model Training and Evaluation

The model is trained using the Gradient Boosting Regressor with a grid search for hyperparameter tuning. The evaluation metrics used include Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

Results

Mean Squared Error (MSE): 2,303,427,302.97

Root Mean Squared Error (RMSE): 47,994.03

R² Score: 0.828

These results indicate that the model explains approximately 82.8% of the variance in house prices and has an average prediction error of about 47,994 units.
