# Loan Eligibility Decider With Microsoft Fabric Synapse Data Science

## Introduction
The Loan Eligibility Decider AI is an innovative machine learning application designed to predict loan application outcomes. It serves as a decision support tool for financial institutions, aiming to streamline the loan approval process and minimize the risk of defaults.

## Background
Loans are a fundamental aspect of the financial sector, enabling individuals and businesses to access capital for various purposes. However, the impact of loan defaults can be detrimental to both the borrower and the lender. For borrowers, defaulting on a loan can lead to severe credit score damage, increased interest rates on future loans, and potential legal action. For banks, defaults can result in financial losses, reduced liquidity, and a tarnished reputation. Therefore, accurately predicting loan eligibility is crucial for maintaining financial health and stability.

## Features
The application utilizes a range of features to assess the risk associated with loan applications:

| Feature | Description |
|---------|-------------|
| `person_age` | Age of the individual applying for the loan. |
| `person_income` | Annual income of the individual. |
| `person_home_ownership` | Type of home ownership (rent, mortgage, own, other). |
| `person_emp_length` | Employment length in years. |
| `loan_intent` | The intent behind the loan application. |
| `loan_grade` | Grade assigned to the loan based on creditworthiness (A-G). |
| `loan_amnt` | The loan amount requested. |
| `loan_int_rate` | The interest rate associated with the loan. |
| `loan_status` | Loan status (0: non-default, 1: default). |
| `loan_percent_income` | Proportion of income allocated towards loan repayment. |
| `cb_person_default_on_file` | Historical default as per credit bureau (Y/N). |
| `cb_person_cred_hist_length` | Length of credit history for the individual. |


## Usage
Dataset has been provided as `Credit_Risk_Dataset.csv`
Web platform is in development with streamlit / Flask and Docker for UI interactions.
