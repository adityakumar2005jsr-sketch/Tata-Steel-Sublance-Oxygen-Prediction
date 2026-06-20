# LD1 Sublance Secondary Blow Model

## Internship Project at Tata Steel

Machine Learning based predictive modeling of oxygen consumption and secondary blow process parameters in LD1 steelmaking operations using Random Forest and XGBoost.

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

## Model Performance Summary

XGBoost significantly outperformed Random Forest and achieved:

- R² Score: 0.886
- MAE: 99.83
- RMSE: 204.81

- ## Final Results

| Model | MAE | RMSE | R² Score |
|--------|--------|--------|--------|
| Random Forest | 322.57 | 618.56 | 0.349 |
| XGBoost | 99.83 | 204.81 | 0.886 |

The model successfully captured nonlinear relationships among operational steelmaking parameters and demonstrated strong predictive capability for SB_O2_CONS.

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

## Business Impact

The developed XGBoost model achieved an R² Score of 0.886, demonstrating strong predictive capability for oxygen consumption during LD1 steelmaking operations.

Benefits include:

- Improved process monitoring
- Better oxygen consumption estimation
- Reduced operator dependency
- Support for data-driven steelmaking decisions
- Potential cost and productivity improvements

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib

- ## Internship Details

Organization: Tata Steel

Department: LD1 Steelmaking Operations

Role: Data Analyst Intern

Project: LD1 Sublance Secondary Blow Model

## Author

Aditya Kumar

Former Data Analyst and ML Intern | Tata Steel
B.Tech Information Technology, KIIT University

LinkedIn:
https://www.linkedin.com/in/aditya-kumar-404282375/

GitHub:
https://github.com/adityakumar2005jsr-sketch
