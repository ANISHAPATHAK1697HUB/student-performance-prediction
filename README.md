# Student Performance Prediction System

## Project Overview

The Student Performance Prediction System is a data science and machine learning project developed to analyse students' academic performance and predict their final scores using relevant academic and lifestyle indicators.

The project uses Exploratory Data Analysis (EDA) and Linear Regression to identify patterns in student data and estimate academic performance.

## Objectives

- Analyse student academic data.
- Identify patterns influencing academic performance.
- Explore factors such as study hours, attendance, assignment completion, sleep hours and previous scores.
- Develop a machine learning model to predict students' final scores.
- Evaluate the model using standard regression metrics.
- Generate insights that may help identify students who could benefit from additional academic support.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Dataset Description

The project uses a dataset containing 500 student records with the following attributes:

- Student ID
- Study Hours
- Attendance
- Assignments Completed
- Sleep Hours
- Previous Score
- Final Score

## Methodology

1. Dataset collection and loading.
2. Data inspection and exploration.
3. Exploratory Data Analysis and visualization.
4. Correlation analysis.
5. Feature selection.
6. Training and testing data splitting.
7. Linear Regression model development.
8. Student performance prediction.
9. Model evaluation and visualization.

## Model Evaluation

The Linear Regression model was evaluated using the following metrics:

| Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 3.62 |
| Mean Squared Error (MSE) | 20.71 |
| Root Mean Squared Error (RMSE) | 4.55 |
| R² Score | 0.7440 |

The model explains approximately 74.4% of the variation in final student scores on the test dataset.

## Project Status

Core implementation and model evaluation have been completed using Python and Google Colab. The dataset and Jupyter Notebook are maintained in the GitHub repository.

## Responsible Use

The system is intended as an educational decision-support prototype. Predictions should not replace teacher judgement or be used as the sole basis for academic decisions.

