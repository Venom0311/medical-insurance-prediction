A Medical Insurance Cost Predictor is a machine learning or statistical model designed to estimate the cost of medical insurance premiums for individuals or groups. This tool is used by insurance companies, healthcare providers, and individuals to understand potential healthcare costs and make informed decisions.

PROCESS:
Import libraries for data handling, model building, and evaluation.
Load the dataset containing medical details.
Encode categorical features (e.g., smoker, region) using one-hot encoding.
Split the data into features (X) and target variable (y).
Divide the dataset into training and testing subsets.
Train a LinearRegression model.
Use the model to predict on unseen data.
Evaluate performance using Mean Squared Error (MSE).
