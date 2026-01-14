# Loan-Approval-Prediction
Loan Approval Dataset containing applicant demographics, income, credit history, and property details, designed for machine learning and predictive modeling to determine loan approval outcomes.
# Loan Approval Prediction Dataset

![License](https://img.shields.io/badge/License-MIT-green) ![Python](https://img.shields.io/badge/Python-3.8-blue)

## Description
The **Loan Approval Dataset** contains information about loan applicants and their profiles, used to predict whether a loan will be approved or rejected. This dataset is ideal for **classification tasks** in machine learning and helps in understanding factors affecting loan approval decisions.

## Dataset Features
The dataset typically includes the following columns:

| Column Name          | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `Loan_ID`            | Unique identifier for each loan application                                 |
| `Gender`             | Applicant’s gender (Male/Female)                                            |
| `Married`            | Whether the applicant is married (Yes/No)                                   |
| `Dependents`         | Number of dependents (0, 1, 2, 3+)                                         |
| `Education`          | Applicant’s education level (Graduate/Not Graduate)                         |
| `Self_Employed`      | Whether the applicant is self-employed (Yes/No)                             |
| `ApplicantIncome`    | Applicant’s monthly income                                                  |
| `CoapplicantIncome`  | Co-applicant’s monthly income                                               |
| `LoanAmount`         | Loan amount in thousands                                                    |
| `Loan_Amount_Term`   | Term of the loan in months                                                  |
| `Credit_History`     | Credit history meets guidelines (1 = Yes, 0 = No)                           |
| `Property_Area`      | Urban/Semiurban/Rural property location                                     |
| `Loan_Status`        | Loan approval status (Y = Approved, N = Not Approved)                       |

## Dataset Size
- **Number of records:** ~614 (common for standard versions)  
- **Number of features:** 12 (excluding the target `Loan_Status`)  

## Usage
This dataset can be used for:
- Predicting loan approval using classification algorithms  
- Data preprocessing and feature engineering exercises  
- Exploratory Data Analysis (EDA) and visualization  

### Example Code
```python
import pandas as pd

# Load dataset
data = pd.read_csv("loan_data.csv")

# Display first 5 rows
print(data.head())
