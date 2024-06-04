# Automated Loan Decider with Microsoft Fabric Data Science

## Introduction

Machine Learning has found significant applications in several industries. A major application in Finance or Banking is the
development of Automated Loan Decider System that quickly review applicant's data and decide eligibility accordingly.

This repo is about building a system like that using the `Microsoft Fabric's Data Science` as part of the training
organized by the `9ja Data Platform`.

To join the community, click here: https://community.fabric.microsoft.com/t5/9ja-Data-Platform/gh-p/9jaDataPlatform

## Set up

The data used in this project is a csv file containing records of loan applications sourced from `kaggle.com` and it is provided
in here: [credit_risk_dataset.csv](dataset/credit_risk_dataset.csv).

1. First step is to download the dataset.
2. Log in to [Microsoft Fabric](app.fabric.microsoft.com) and select the `Synapse Data Science` experience.
3. Create a workspace, click on advance settings to select the Trial version (if you do not have subscription).
4. In the workspace, create a Lakehouse.
5. In the Lakehouse, click on `...` on Files to upload the dataset into your LakeHouse.
6. Start with fresh notebook or upload an existing notebook (NOTE: attach the notebook to the LakeHouse).

### Features in the Dataset

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

This version can be used only on Microsoft Fabric as described above.
User interface to interact with the model will be avaiable later with the source code.

## Learning Resources

#### Skills involved in this include:

1. Python: Pandas, Matplotlib, and other libraries
2. Basic Microsoft Fabric Usuage
3. Fundamentals of Machine Learning Concepts

### Here are useful links to learn:
- Python Programming: https://cs50.harvard.edu/python/2022/
- Pandas: https://www.youtube.com/watch?v=ZyhVh-qRZPA&list=PL-osiE80TeTsWmV9i9c58mdDCSskIFdDS
- Matplotlib: https://www.youtube.com/watch?v=UO98lJQ3QGI&list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_
- Machine Learning Concepts: https://www.youtube.com/@professor-ryanahmed (Query any topic or model you want to understand)
