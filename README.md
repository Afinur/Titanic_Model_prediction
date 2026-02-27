Titanic Survival Prediction 🚢

This project uses Machine Learning to predict the survival of passengers from the Titanic disaster based on features like age, gender, and passenger class.

📋 Project Overview

The workflow of this project includes:

Data Cleaning

Handled missing values for features like Age and Fare using mean imputation.

Feature Engineering

Converted categorical variables (Sex, Embarked) into numerical format using encoding techniques.

Model Training

Implemented multiple machine learning algorithms to compare their performance.

🛠 Technologies Used

Python

Pandas & NumPy – Data manipulation

Scikit-learn – Preprocessing and ML models

XGBoost – Gradient boosting

📊 Models and Performance

The following models were trained and evaluated on the dataset. Accuracy results are as follows:

Model	Accuracy
Logistic Regression	0.804
Decision Tree	0.782
Random Forest	0.810
K-Nearest Neighbors (KNN)	0.810
XGBoost	0.821

Note: In this project, XGBoost performed the best with an accuracy of 82.1%.
