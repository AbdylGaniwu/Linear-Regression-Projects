# Linear Regression Analysis for Predicting Brain Weight

This repository contains a project that applies **linear regression analysis** to predict **brain weight** based on physiological characteristics such as **head size**, **gender**, and **age range**. The project aims to provide insights into how these factors correlate with brain weight and can be used in fields such as **medical research**, **forensic science**, and **anthropometry**.

## Project Overview

### Objective
The goal of this project is to create a predictive model that estimates brain weight using the following independent variables:
- **Head Size (cm³)**
- **Gender** (Male: 0 /Female: 1)
- **Age Range** (Categorized as 1 or 2)

### Application
- **Medical Research**: Understanding the physiological factors that affect brain characteristics might help explain brain development and potential disorders.
- **Anthropometry & Forensic Science**: Insights from this analysis can be used to understand typical variations in brain weight, aiding in anthropology and forensic studies.

## Dataset
The dataset includes the following columns:
- **Gender**: Male (as 0) or Female (as 1)
- **Age Range**: Categorized into two groups (1, 2)
- **Head Size (cm³)**: The head size in cubic centimeters
- **Brain Weight (grams)**: The target variable we aim to predict




## Methodology
1. **Data Preprocessing**: The dataset was cleaned and prepared for analysis.
2. **Model Selection**: A linear regression model was selected to predict brain weight.
3. **Model Fitting**: The Ordinary Least Squares (OLS) method was used to fit the model.
4. **Evaluation**: The model was evaluated using the **R-squared** metric to understand how well it explains the variance in brain weight.

## Results
- The model produces coefficients for each independent variable, indicating the impact of **gender**, **age range**, and **head size** on brain weight.
- The **R-squared** value shows the proportion of variance explained by the model.

### Example Prediction:
```
Predicted Brain Weight for a sample: 1519.93 grams
```

### Visualization:
A scatter plot was generated to visualize the relationship between **Head Size** and **Brain Weight**, along with the fitted regression line.


## Files in the Repository
- **brain_weight_prediction.py**: The main script that performs the linear regression analysis.
- **headbrain_data.csv**: The dataset used for the analysis.
- **requirements.txt**: List of dependencies required to run the project.
- **visualization.png**: Scatter plot showing the relationship between head size and brain weight.




## Conclusion
This project demonstrates the use of linear regression to predict brain weight based on physiological characteristics. The model provides valuable insights into the relationship between head size, gender, and age range with brain weight. Future improvements may include using additional variables or testing non-linear models for better accuracy.

 
