# Lending Case Study

## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]

## General Information
> Problem Statement:
consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
Suggest that whether the person will repay the money.
> Dataset which is used:
	- Loan dataset which is being used

## Conclusions
Key Observations from Dataset
Higher the Interest rate and higher the loan amount is causing the Higher charged off  .
Higher Charged off is happening between Sep, Oct, Nov and Dec Month - It based on loan issued date.
Small Business purpose loan has high impact on Charged Off.
60 Months payments loans has high impact of charged-off.
lower income range is the more risky when it comes to loan repayment.
Higher instalments has more risks of charged off.
Key Assumption
Here we have considered the missing employee length as Zero.
Here we considered pub_rec_bankruptcies empty value as Zero
We have set the outliner limit as 95% and excluded the records
Excluded the  columns which is not a driving factor and not many unique values.

## Technologies Used
- Python

- library - pandas
- library - warnings
- library - seaborn
