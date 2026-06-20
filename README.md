# Tata Steel Sublance Oxygen Consumption Prediction using XGBoost

## Business Problem

In steelmaking operations, accurate prediction of oxygen consumption is critical for maintaining process stability, improving productivity, and ensuring product quality.

Traditional approaches often struggle to capture complex relationships between process variables. This project explores machine learning techniques to predict oxygen consumption using historical steelmaking data.

## Project Objective

The objective of this project is to develop predictive machine learning models capable of estimating oxygen consumption using operational process parameters collected from LD steelmaking operations.

The project aims to:

- Improve prediction accuracy
- Identify key influencing variables
- Support process optimization
- Enable data-driven decision making

## Dataset Overview

The dataset consists of operational steelmaking parameters collected from Tata Steel LD operations.

Target Variable:

- SB_O2_CONS

## Methodology

1. Data Cleaning
2. Missing Value Treatment
3. Feature Engineering
4. Feature Selection
5. Model Development
6. Model Evaluation

## Machine Learning Models

### Random Forest Regressor

| Metric | Value |
|----------|----------|
| MAE | 322.57 |
| RMSE | 618.56 |
| R² Score | 0.349 |

### XGBoost Regressor

| Metric | Value |
|----------|----------|
| MAE | 99.83 |
| RMSE | 204.81 |
| R² Score | 0.886 |

## Top Influencing Variables

1. EMB_C
2. EMB_TEMP
3. MB_O2_CONS
4. HM_SI_PCT
5. AIM_C
6. MB_IRONORE
7. MB_DOLO
8. STATION_CODE_BOF2
9. HM_TEMP
10. MB_LIME

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib

## Author

Aditya Kumar

Former Data Analyst Intern at Tata Steel

LinkedIn:
https://www.linkedin.com/in/aditya-kumar-404282375/

GitHub:
https://github.com/adityakumar2005jsr-sketch
