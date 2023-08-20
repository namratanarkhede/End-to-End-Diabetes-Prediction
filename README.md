# End-to-End Diabetes Prediction using Logistic Regression

This repository contains a data science project for End-to-End Diabetes Prediction using Logistic Regression with GridSearchCV. The goal of this project is to build a machine learning model that predicts the likelihood of a person having diabetes based on various input features. The project uses Python's Flask framework to create a simple web application that allows users to input relevant data and get predictions in real-time. The trained model is saved as a .pkl file for easy deployment and reuse.

## Project Overview
1. Domain: Data Science
2. Algorithm: Logistic Regression
3. Model Tuning: GridSearchCV
4. Web Framework: Flask

### The main steps of the project include:

1. **Data Collection:** Obtain a dataset containing relevant features and target labels related to diabetes.
2. **Data Preprocessing:** Clean, transform, and preprocess the data to make it suitable for training.
3. **Model Selection:** Choose Logistic Regression as the predictive model due to its simplicity and interpretability.
4. **Hyperparameter Tuning:** Utilize GridSearchCV to find the best combination of hyperparameters for the Logistic Regression model.
5. **Model Training:** Train the Logistic Regression model using the preprocessed data and the optimal hyperparameters.
6. **Model Evaluation:** Evaluate the trained model's performance using appropriate metrics and visualization techniques.
7. **Flask Web Application:** Build a web application using Flask that allows users to input their data and receive predictions from the trained model.
8. **Model Deployment:** Save the trained model as a .pkl file for easy deployment in production environments.
