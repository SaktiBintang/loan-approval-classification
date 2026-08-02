# Loan Approval Classification Using Machine Learning

A machine learning classification project to predict loan approval status based on applicants' personal, financial, and loan-related characteristics.

## Project Overview

This project aims to build and compare machine learning classification models for predicting whether a loan application will be approved or not.

The project covers the machine learning workflow from exploratory data analysis and data preprocessing to model development, evaluation, improvement, and interpretation.

## Dataset

The dataset contains **45,000 records and 14 features** related to loan applicants.

The target variable is:

- `loan_status` — Loan approval status

Some of the features include:

- `person_age`
- `person_gender`
- `person_education`
- `person_income`
- `person_emp_exp`
- `person_home_ownership`
- `loan_amnt`
- `loan_intent`
- `loan_int_rate`
- `loan_percent_income`
- `credit_score`
- `previous_loan_defaults_on_file`

## Objectives

The main objectives of this project are:

- Explore the characteristics of the loan approval dataset.
- Perform data preprocessing and feature selection.
- Build classification models to predict loan approval status.
- Compare the performance of different classification algorithms.
- Apply model improvement techniques.
- Identify the features that have the strongest influence on the prediction.

## Machine Learning Workflow

The project follows these main steps:

1. Exploratory Data Analysis (EDA)
2. Missing Value Checking
3. Duplicate Data Checking
4. Outlier Handling
5. Categorical Encoding
6. Feature and Target Separation
7. Feature Selection
8. Train-Test Split
9. Standardization
10. Model Development
11. Model Evaluation
12. Model Improvement
13. Feature Importance Analysis
14. Business Interpretation

## Models

Three classification algorithms were developed and compared:

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)

## Model Improvement

Several techniques were applied and compared to improve model performance:

- Cross-Validation
- Hyperparameter Tuning
- SMOTE
- Class Weight
- Threshold Tuning

The models were evaluated using multiple metrics to understand the effect of each improvement technique.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC
- ROC Curve
- Precision-Recall Curve
- Learning Curve

## Key Results

Random Forest achieved the best overall performance among the three classification algorithms used in this project.

After Hyperparameter Tuning, Random Forest achieved an accuracy of approximately **92.53%**.

Feature Importance analysis showed that the most influential features included:

- `previous_loan_defaults_on_file`
- `loan_int_rate`
- `person_income`
- `loan_percent_income`
- `loan_amnt`

Random Forest was selected as the most suitable model for this loan approval classification problem.

## Business Implications

The model can be used as a decision-support tool for the initial assessment of loan applications.

The prediction results and feature importance analysis can help financial institutions perform an initial assessment more efficiently and consistently.

However, the model should be used as a supporting tool rather than a complete replacement for human decision-making.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Project Structure

```text
loan-approval-classification/
│
├── README.md
├── loan_approval.ipynb
├── dataset/
│   └── loan_data.csv
│
└── images/
    └── ...
    