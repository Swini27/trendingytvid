# Predicting YouTube Video Views

## Overview

This project aims to :-
- bridge the gap between theory and practical knowledge by self implementing *sklearn.linear_model*
- predict the number of views a YouTube video will receive using various machine learning regression models. 
It explores feature engineering, data cleaning, exploratory data analysis (EDA), and model evaluation to determine the best-performing regression algorithm.

## Features

- Data Cleaning & Feature Engineering: Handles missing values and refines dataset features.

- Exploratory Data Analysis (EDA): Visualizes and analyzes key trends in the dataset.

- Machine Learning Models: Implements multiple regression models, including:
    
    - Self-made Linear Regression
    
    - Decision Tree Regressor
    
    - Random Forest Regressor
    
    - AdaBoost Regressor
    
    - Gradient Boosting Regressor

- Model Evaluation: Uses metrics such as R-squared, Mean Squared Error, and Mean Absolute Error to compare model performance.

- Country-Specific Analysis: Runs the best-performing model on YouTube video data from the USA and Canada.

## Installation

To run this project, install the required dependencies:
```bash
pip install pandas numpy scikit-learn seaborn matplotlib statsmodels
```

## Usage

1. Load the dataset ([here](https://www.kaggle.com/datasets/datasnaek/youtube-new)).

2. Perform **data preprocessing** and **exploratory analysis**.

3. Train and evaluate different regression models and compare their performance with the *self_made_linear_model*.

4. Identify the **best-performing** model for predicting YouTube video views.

5. Extend the analysis to country-specific datasets (e.g., USA, Canada).

## Results

The *self_made_linear_model* was at par with the *sklearn.linear_model*

The best-performing model for predicting video views was Random Forest Regressor.

The model was further fine-tuned and tested across different country datasets.

## Acknowledgments

- This project was developed as part of an academic initiative to explore predictive modeling and machine learning applications.
- The primary objective was to bridge theoretical knowledge with practical implementation.
- The development of self_made_linear_model provided valuable insights into regression techniques and model optimization, enhancing the overall understanding of machine learning principles

## License

This project is open-source and available for use under the MIT License.


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.


## Authors

- [@Swini27](https://www.github.com/Swini27)

