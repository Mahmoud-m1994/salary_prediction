# Developer Salary Prediction in Norway

## Overview

This project involves predicting developer salaries in Norway using a variety of machine learning models. The data includes features such as age, place, job title, experience (years), education (years), and whether a bonus is included. The goal is to build accurate predictive models and analyze the factors influencing developer salaries.

## Project Steps

1. **Data Collection and Preprocessing**
   - Collected data from [Kode24](https://www.kode24.no/artikkel/her-er-lonnstallene-for-norske-utviklere-2024/81507953)
   - Saved data to a CSV file.
   - Handled missing values and performed data cleaning.
   - Converted categorical data to numerical values manually.
   - Applied feature engineering, including converting ranged data to midpoints.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed data using heatmaps, correlations, and descriptive statistics to understand data distributions and relationships.

3. **Model Building**
   - Built and evaluated multiple machine learning models:
     - **Linear Regression**
     - **Decision Tree**
     - **Random Forest**
     - **Gradient Boosting**

4. **Model Optimization**
   - Fine-tuned model hyperparameters:
     - Used interval search for `max_depth` in Decision Trees.
     - Implemented early stopping and looped through 1000 `n_estimators` for Random Forest and Gradient Boosting.

5. **Prediction and Evaluation**
   - Used the optimized models to predict developer salaries.
   - Evaluated model performance and compared results.

## Dependencies

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `jupyter` (for notebooks)

You can install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
