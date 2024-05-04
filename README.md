# Regression-Analysis-in-R

# Project: What Determines Employee Salaries?

**Authors**: Neeraj Namani 

## Introduction

This project explores the determinants of employee salaries using multiple regression analysis in R. Our focus is on how factors such as experience, education, job role, and industry influence salary levels, aiming to provide insights that could aid in salary structuring and employee retention strategies.

### Objectives

- To identify key factors influencing employee salaries.
- To compare the effectiveness of different regression models in predicting salaries.

## Data Preprocessing

1. **Data Cleaning**: Initial data cleaning involved handling missing values and removing outliers to improve the accuracy of our models.
2. **Feature Selection**: Variables like age, years of experience, education level, and job role were selected based on their expected impact on salaries.

## Exploratory Data Analysis (EDA)

- **Correlation Analysis**: We identified strong positive correlations between salary and factors like age and years of experience. 
- **Visualizations**:
  - Matrix plots and scatter plots to examine relationships between variables.
  - Histograms and box plots to understand the distribution and variability of the data.

## Model Development

### Linear Regression

- We first applied a linear regression model to predict salaries based on the selected variables.
- **Model Summary**: The model showed a good fit with an R-squared value of 0.8825 on the test set.

### Random Forest

- Next, we used the Random Forest algorithm to handle non-linear relationships and interactions between variables more effectively.
- **Model Summary**: The Random Forest model outperformed the Linear Regression with an R-squared of 0.9162 on the test set.

## Model Comparison and Validation

- **Cross-validation**: We performed 10-fold cross-validation to ensure the stability and reliability of our models.
- **Model Metrics**:
  - **Linear Regression**: RMSE: 14352.31, MAE: 9470.211
  - **Random Forest**: RMSE: 14197.53, MAE: 8840.320

## Conclusion

Our analysis confirms the significant impact of experience and education on employee salaries. The Random Forest model, providing a nuanced understanding of these relationships, suggests that complex models may offer better insights for organizational strategies on salary structuring.

