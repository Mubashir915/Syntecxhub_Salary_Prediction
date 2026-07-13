# Syntecxhub Salary Prediction Week 1 Task

This repository contains the Week 1 assignment for the Machine Learning Internship at Syntecxhub. The goal of this project is to build a Multiple Linear Regression model to predict salaries based on experience, test scores, and interview scores.

## Project Overview
- **Problem Statement:** Predict employee salary based on their profile data.
- **Dataset Features:** `experience` (Years of experience)
  - `test_score` (Technical test performance)
  - `interview_score` (Interview evaluation performance)
- **Target Variable:** `salary`

## Technology Stack
- Python 3
- Jupyter Notebook
- Pandas & NumPy (Data Handling)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning Modeling)
- Pickle (Model Serialization)

## Model Evaluation Results
- **Algorithm Used:** Multiple Linear Regression
- **Evaluation Metrics:**
  - Root Mean Squared Error (RMSE) checked successfully.
  - $R^2$ Score evaluated and verified with train-test split.

## Files in the Repository
- `Salary_Prediction.ipynb`: Jupyter notebook containing the complete data pipeline, visualization, training, and evaluation code.
- `model.pkl`: The trained and serialized machine learning model ready for production/deployment.
