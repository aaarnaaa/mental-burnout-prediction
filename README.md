# mental-burnout-prediction
ML project predicting employee burnout using Python.

## Overview
This project uses **Machine Learning** to predict the risk of mental burnout among employees based on factors like work hours, sleep, stress level, and job satisfaction. It provides **logical predictions (YES/NO)** along with probability scores, helping organizations identify at-risk employees.

## Dataset
The dataset is from [Kaggle: Mental Health & Burnout in the Workplace](https://www.kaggle.com/datasets) and contains features such as:
- `work_hours_per_week`
- `sleep_hours_per_day`
- `stress_level`
- `job_satisfaction`
- `BurnoutRisk` (target variable)

## Tech Stack
- Python
- Pandas
- Scikit-Learn
- SMOTE (for class balancing)
- Logistic Regression
- Matplotlib / Seaborn for visualizations

## Features
- Predicts burnout risk for individual cases.
- Generates **Pie Chart** for overall dataset distribution.
- Generates **Bar Chart** for sample test cases.

