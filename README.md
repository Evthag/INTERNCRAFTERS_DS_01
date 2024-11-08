**About Dataset**

**1. Data Source**

This dataset is a synthetic version inspired by the original Credit Risk dataset on Kaggle and enriched with additional variables based on Financial Risk for Loan Approval data. SMOTENC was used to simulate new data points to enlarge the instances. The dataset is structured for both categorical and continuous features.

**2. Metadata**

The dataset contains 45,000 records and 14 variables, each described below:

Column	Description	Type

person_age	Age of the person	Float

person_gender	Gender of the person	Categorical

person_education	Highest education level	Categorical

person_income	Annual income	Float

person_emp_exp	Years of employment experience	Integer

person_home_ownership	Home ownership status (e.g., rent, own, mortgage)	Categorical

loan_amnt	Loan amount requested	Float

loan_intent	Purpose of the loan	Categorical

loan_int_rate	Loan interest rate	Float

loan_percent_income	Loan amount as a percentage of annual income	Float

cb_person_cred_hist_length	Length of credit history in years	Float

credit_score	Credit score of the person	Integer

previous_loan_defaults_on_file	Indicator of previous loan defaults	Categorical

loan_status (target variable)	Loan approval status: 1 = approved; 0 = rejected	Integer


**3. Data Usage**

The dataset can be used for multiple purposes but I used it here just to check the distribution of the variables


**4. Libraries used**

Numpy: Python library used for working with arrays

Pandas: It has functions for analyzing, cleaning, exploring, and manipulating data

Seaborn: library for making statistical graphics in Python

**5. Data Source**

Link: https://www.kaggle.com/datasets/taweilo/loan-approval-classification-data
