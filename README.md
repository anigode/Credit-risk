# Credit Risk Analysis Project
This project focuses on predicting credit risk using a machine learning approach. The dataset contains detailed information about loan applicants, such as employment status, income, loan amounts, credit history, and more. By training machine learning models, we can classify loans as either risky or safe, helping financial institutions make more informed lending decisions.
- Table of Contents
- Introduction
- Installation
- Usage
- Data
- Models
- Evaluation
- Libraries
## Introduction
The goal of this project is to assess and predict the risk of loan defaults using machine learning models. The dataset includes various features such as employment length, annual income, debt-to-income ratio, and loan status, which are crucial in determining the likelihood of a loan being fully paid or going into default. Logistic regression and random forest models are implemented for predictive analysis.
## Installation
To set up the project, clone the repository and ensure you have Python installed (preferably version 3.6 or above). Install the required libraries.
## Usage
Place your dataset CSV file (e.g., loans_full_schema.csv) in the project directory. Then run the credit_risk_analysis.py script to preprocess the data, train the model, and evaluate its performance. The cleaned data and results will be saved in the project directory.
## Data
The dataset used in this project includes key features like:
- emp_length: Number of years employed
- annual_income: Annual income of the applicant
- debt_to_income: Ratio of debt to income
- loan_status: The target variable indicating whether the loan is fully paid or in default

The script performs data preprocessing steps such as:
- Checking for missing values and imputing where necessary
- Encoding categorical variables using one-hot encoding
- Scaling numerical data for model input
## Models
The following machine learning models are implemented in this project:
- Logistic Regression: A model used for binary classification of the loan status.
- Random Forest Classifier: A more advanced ensemble method for predicting loan outcomes based on multiple decision trees.
## Evaluation
The performance of the models is evaluated based on:
- Accuracy: The proportion of correctly predicted loan statuses.
- AUC-ROC: A metric representing the trade-off between true positive rate and false positive rate.
- Confusion Matrix: A summary of prediction results to show actual vs predicted values.
## Libraries
This project depends on the following Python libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
