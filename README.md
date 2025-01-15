# Supervised-Regression-SalaryPrediction
This project aims to predict employee salaries based on their years of experience using supervised regression models (Linear Regression, Decision Tree Regression, and Random Forest Model). The dataset contains information about years of experience and corresponding salary values.

## Goal
1. Developing accurate salary prediction models based on years of experience.
2. Analyzing and comparing model performances to identify the most effective approach
3. Creating a practical tool for salary estimation based on work experience.
   
## Project Structure
### 1. Data Ingestion
      -Loading data from 'salary data.csv' using pandas
### 2. Exploratory Data Analysis (EDA)
      -Visualization of relationship between experience and salary
      -Scatter plot implementation using seaborn
### 3. Data Preprocessing
      -Duplicate data check and removal
      -Missing value identification
      -Data preparation for modeling
### 4. Model Implementation
      -Data splitting (75% training, 25% testing)
      -Three different models regression (Linear Regression, Decision Tree, Random Forest)
### 5. Model Evaluation
      -Mean Squared Error (MSE) calculation
      -R² Score evaluation
      -Visual comparison of actual vs predicted values
      -Performance comparison between training and test sets

## Insight and Result
The analysis revealed a strong positive correlation between years of experience and salary, with no missing values or duplicates in the dataset. Among the three models tested, Random Forest demonstrated the best performance with high R-squared values and low RMSE.
   
