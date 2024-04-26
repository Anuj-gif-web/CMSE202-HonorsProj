# CMSE202-HonorsProj
Project name: APPROVAL PREDICTION MODEL

Abstract:
This project develops a predictive model to determine whether a loan should be approved based on various applicant features. Using historical loan application data, the model assesses factors like income, credit history, and employment status to predict loan approval outcomes. This tool aims to assist financial institutions in making informed, data-driven decisions

The dataset, loan_data.csv, comprises several attributes that are critical to loan approval decisions, including Loan ID, gender, marital status, number of dependents, education level, employment status, applicant and co-applicant incomes, loan amount, loan term, credit history, property area, and the loan approval status itself. These features collectively provide a comprehensive overview of an applicant's financial and personal background, which are essential for assessing their eligibility for a loan.

The methodologies implemented in this project encompass a range of statistical techniques and machine learning models:

Data Preparation-
Initial data cleaning involved handling missing values and encoding categorical variables to prepare the dataset for further analysis.

Intial Data Analysis-
This phase focused on understanding the relationships and distributions of various features relative to loan approval.

Model Development-
Simple Linear Regression was first used to establish a baseline for prediction, focusing on the impact of credit history.
Multiple Linear Regression integrated multiple variables to evaluate their combined influence on loan approval decisions.
Logistic Regression and Support Vector Machine (SVM) were later applied for binary classification to predict loan approval status, given their appropriateness for categorical outcomes.

Evaluation-
The models were assessed using metrics such as accuracy, precision, recall, F1-score, and mean squared error to gauge their effectiveness.

Conclusion-
The Loan Status Prediction project highlights the important role of predictive modeling in enhancing the efficiency and fairness of loan approval processes. Through the application of  statistical methods and machine learning algorithms, financial institutions can improve their decision-making capabilities, benefiting both the lenders and borrowers in the long run.
