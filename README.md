Credit Risk Prediction Project
1.	Credit Risk Prediction This project implements a credit risk prediction model using machine learning techniques. The goal is to predict whether a loan will be fully paid or default based on various features. The analysis involves data cleaning, preprocessing, model training, and evaluation.
2.	Table of Contents
•	Introduction
•	Installation
•	Usage
•	Data
•	Models
•	Evaluation
•	Libraries
•	License
3.	Introduction The aim of this project is to predict the status of loans (Fully Paid or Default) using a dataset containing various loan features. It employs techniques such as data cleaning, filling missing values, one-hot encoding of categorical variables, and standard scaling of numerical features. The project uses logistic regression and random forest classifiers for model training and evaluation.
4.	Installation To set up the project, clone the repository and install the required libraries. Ensure you have Python installed (preferably version 3.6 or above).
5.	Usage
•	Place your dataset CSV file (e.g., loans_full_schema.csv) in the project directory.
•	Run the credit_risk_prediction.py script to execute the analysis.
•	The cleaned data will be saved as CreditRiskData.csv in the project directory.

6.	Data
•	The project uses a dataset containing loan information, which includes various features related to the loans, such as:
•	loan_status_Fully Paid: Target variable indicating whether the loan was fully paid.
•	Other features related to loan applicant details and loan characteristics.
•	The script performs the following data preprocessing steps:
•	Removes columns with more than 50% missing values.
•	Fills missing numerical values with the mean of the column.
•	Fills missing categorical values with the mode.
•	Encodes categorical variables using one-hot encoding.

7.	Models The following machine learning models are implemented in this project:
•	Logistic Regression: Used to predict the probability of a loan being fully paid.
•	Random Forest Classifier: An ensemble method used for improved accuracy through hyperparameter tuning.
Each model is evaluated using metrics such as accuracy and AUC-ROC.
8.	Evaluation The performance of the Logistic Regression model is evaluated based on:
•	Accuracy: The ratio of correctly predicted instances to the total instances.
•	AUC-ROC: The area under the receiver operating characteristic curve, indicating the model's ability to distinguish between classes.
The confusion matrix is also visualized to show the model's prediction performance.
9.	Libraries The project depends on the following Python libraries:
•	pandas
•	numpy
•	seaborn
•	matplotlib
•	sklearn


