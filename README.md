# Kaggle Loan Prediction Competition
Finding and utilizing the best predictive model for the loan approval task, giving the highest adaptive accuracy.

### Goal
The goal for this competition is to create a model that can predict whether an applicant is approved for a loan.

## Overview 
Automatically predicts whether a loan application will be approved using demographic and financial features. Built with typical classifiers like KNN, Random Forests, Decision Trees, and SVM

### Dictionary
| Field Name | Description |
| ---------- | ----------- |
| person_age   | Applicant age |
| person_income    | Applicant's income |
| person_home_ownership    | Housing status (Rent, Own, Mortgage, Other) |
| person_emp_length    | Applicant's employment length |
| loan_intent    | Loan use (Personal, Educational, Medical, Venture, Home Improvement, Debt Consolidation) | 
| loan_grade   | Rating of loan (A, B, C, D, E, F, G) |
| loan_amnt   | Loan amount requested |
| loan_int_rate    | Loan interest rate |
| loan_status    | Status of loan (1 = Denied, 0 = Approved) |
| loan_percent_income    | Debt to income ratio |
| cb_person_default_on_file    | If applicant has a record of defaulting on a loan (Y, N) | 
| cb_person_cred_hist_length    | Applicant's credit history length |

## Getting Started 
###Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Key Python libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
 
### Install Dependencies:
pip install numpy pandas scikit-learn matplotlib seaborn

### Running Notebook
1. Launch Jupyter: jupyter notebook
2. Open loan-prediction-ml.ipynb:
- Load dataset
- Perform preprocessing & EDA
- Encode categorical features
- Train & evaluate models: KNN, Decision Tree, Random Forest, SVM
3. Run accuracy_run.ipynb
- Compare accuracy across models
- Visualize performance
