# Income Classification using Logistic Regression

### Project Brief

**Objective:** In this project, I will build a logistic regression model to classify income based on census data from the 1994 Census database. My goal is to predict whether a person earns more than $50,000 annually based on this data.  
Data source: https://archive.ics.uci.edu/dataset/20/census+income

### Tasks Overview

Here's a breakdown of the tasks I'll be performing using Python and various packages:

1. **Exploratory Data Analysis (EDA) and Logistic Regression Assumptions**: I'll start by checking if the dataset is balanced. Then, I'll create dummy variables for the predictor variables using libraries such as `pandas`, `numpy`, and `seaborn`.

2. **Heatmap of Correlation Values**: I'll visualize the correlation among predictor variables using the `seaborn` library.

3. **Split Data and Fit Logistic Regression Model**: I'll split the data into training and testing sets using `train_test_split` from `sklearn` and fit a logistic regression model on the training set using `LogisticRegression` from `sklearn`.

4. **Model Parameters and Coefficients**: I'll print model parameters, including the intercept and coefficients, using `LogisticRegression` from `sklearn`.

5. **Evaluate Model Predictions**: I'll evaluate the model's predictions on the test set by printing the confusion matrix and accuracy score using functions from `sklearn`.

6. **Model Coefficients and Variable Names**: I'll create a DataFrame of model coefficients and variable names, sorting them by coefficient values.

7. **Barplot of Coefficients**: I'll create a barplot of coefficients in ascending order using `seaborn` and `matplotlib` libraries.

8. **ROC Curve and AUC**: I'll plot the ROC curve and print the AUC (Area Under the Curve) value using `roc_curve` and `roc_auc_score` from `sklearn`.
