Predicting YouTube Video Views

Overview

This project aims to predict the number of views a YouTube video will receive using various machine learning regression models. It explores feature engineering, data cleaning, exploratory data analysis (EDA), and model evaluation to determine the best-performing regression algorithm.

Features

Data Cleaning & Feature Engineering: Handles missing values and refines dataset features.

Exploratory Data Analysis (EDA): Visualizes and analyzes key trends in the dataset.

Machine Learning Models: Implements multiple regression models, including:

Self-made Linear Regression

Decision Tree Regressor

Random Forest Regressor

AdaBoost Regressor

Gradient Boosting Regressor

Model Evaluation: Uses metrics such as R-squared, Mean Squared Error, and Mean Absolute Error to compare model performance.

Country-Specific Analysis: Runs the best-performing model on YouTube video data from the USA and Canada.

Installation

To run this project, install the required dependencies:

pip install pandas numpy scikit-learn seaborn matplotlib statsmodels

Usage

Load the dataset (e.g., INvideos.csv).

Perform data preprocessing and exploratory analysis.

Train and evaluate different regression models.

Identify the best-performing model for predicting YouTube video views.

Extend the analysis to country-specific datasets (e.g., USA, Canada).

Results

The best-performing model for predicting video views was Random Forest Regressor.

The model was further fine-tuned and tested across different country datasets.

Acknowledgments

This project was developed as part of an academic exploration into predictive modeling and machine learning applications.

License

This project is open-source and available for use under the MIT License.

