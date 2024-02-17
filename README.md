# LOAN_APPROVAL_PREDICTION
Wise Project

The idea behind this ML project is to build an ML model and web application that the bank can use to classify if a user can be granted a loan or not.

Data Set Description:

The dataset contains information about Loan Applicants.

👉 There are 13 variables in this data set:

5 categorical variabls

8 continuous variables

This dataset attributes:

loan_id

no_of_dependents

education

self_employed

income_annum

loan_amount

loan_term

cibil_score

Credit_History

marital_status

Gender

bank_asset_value

loan_status

To load the training data in your colab, use the below command:

loan_dataset = pd.read_csv('Load Data.csv')

Data Description

Loan_ID: A unique ID assigned to every loan applicant

Gender: Gender of the applicant (Male, Female)

Married: The marital status of the applicant (Yes, No)

Dependents: No. of people dependent on the applicant (0, 1, 2, 3+)

Education: Education level of the applicant (Graduated, Not Graduated)

Self_Employed: If the applicant is self-employed or not (Yes, No)

Annum_Income: The amount of income the applicant earns

LoanAmount: The amount of loan the applicant has requested for

Loan_Amount_Term: The no. of days over which the loan will be paid

Credit_History: A record of a borrower's responsible repayment of debts (1 - has all debts paid, 0 - not paid)

Loan_Status: Is the Loan Approved or Not


Test Dataset:

Load the test data "Loan_Prediction_dataset.csv". You can load the data using the below command.

loan_dataset = pd.read_csv('train_u6lujuX_CVtuZ9i (1).csv')

Loan Prediction Project References:

This project on loan prediction was completed with reference to various resources. Below are the main references used:

Kaggle Datasets:

Ninzaami - Loan Prediction

Abdelruhman Essam - Loan Status Prediction

YouTube Videos:

Loan Status Prediction by Siddardhan

ML Project - Loan Prediction by Data Thinkers

Loan Eligibility Prediction Tutorial by Edureka!

Other Resources:

ChatGPT and Google:

Utilized for understanding terms and resolving challenges encountered during the project.

These resources provided valuable insights, datasets, and tutorials that aided in understanding loan prediction concepts and implementing the project effectively. Each resource contributed to different aspects

of the project, including data exploration, feature engineering, model selection, and evaluation.
