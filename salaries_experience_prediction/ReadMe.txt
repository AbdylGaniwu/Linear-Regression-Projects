# Salary Prediction using Linear Regression

## Overview
This project demonstrates how to build a **Linear Regression model** to predict employee salaries based on years of experience using the `statsmodels` library. The dataset contains two variables: years of experience (independent variable) and salary (dependent variable).

The project includes:
- Data loading and exploration.
- Visualization of the relationship between years of experience and salary.
- Training a linear regression model using `statsmodels`.
- Making predictions based on the model.
- Visualizing actual vs. predicted salaries.
- Evaluating the model's performance using the R-squared metric.

## Technologies Used

- **Python**: Programming language.
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For visualizing data through scatter plots and regression lines.
- **statsmodels**: For building and training the linear regression model.

## Dataset
The dataset, `salaries.csv`, consists of the following columns:

1. **Years of Experience**: Independent variable (X) representing the number of years an employee has worked.
2. **Salary**: Dependent variable (Y) representing the corresponding salary of the employee.




### 1. Load and Explore the Data
The dataset is loaded using `pandas` and a quick inspection of the first few rows is done using `head()`. The `info()` function is used to get details about the data types and missing values (if any).

### 2. Data Preprocessing
- The feature variable (`X`) and target variable (`Y`) are separated.
- Since `statsmodels` requires an intercept term, a constant is added to the feature variable `X` using `sm.add_constant()`.

### 3. Data Visualization
A scatter plot is generated to visualize the relationship between years of experience and salary, showing that a linear relationship exists.

### 4. Model Training
Using `statsmodels.api.OLS`, a linear regression model is trained on the data. The summary of the model, which includes the R-squared score and p-values, is printed.

### 5. Making Predictions
Once the model is trained, predictions are made for new years of experience values such as 7, 5, and 3.5 years. The predicted salaries are displayed.

### 6. Visualizing Results
The actual salaries from the dataset are plotted along with the regression line that represents the predicted salaries based on years of experience.

### 7. Model Evaluation
The R-squared score is used to evaluate the model's performance. The R-squared value close to 1 indicates that the model explains a large portion of the variance in the data.



## Conclusion

This project demonstrates how to use a simple Linear Regression model to predict salaries based on years of experience using the `statsmodels` library. The model performed well with an R-squared value of approximately **0.89**, indicating a strong linear relationship between the independent and dependent variables.

