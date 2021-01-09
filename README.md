# Credit-Risk-Model-V.2-Extra-Credit
Code &amp; Instructions for v.2 model using Lending Club Dataset



# Introduction

For our project, two models were created using Kaggle Lending Club Dataset
   1. Predicting whether a loan will be approved
   2. Predicting whether an approved loan will be a bad loan


# Predicting whether a loan will be approved

2007-2018 Kaggle Lending Club Dataset was used to determine what features are important predictors of Bad Loans. Bad loans are considered any approved loans that  are considered charged off, defaulted, in grace period or late 16-120 days    (Bad Loans: 8 % , Good Loans: 88 %). For V.1, a random forest model was used to achieve 72% accuracy on new data and 36 features were kept. For V.2, a Neural Network Model was used with only 3 features Term, Loan Amount & Debt-to-Income Ratio to achieve 99% accuracy on new data. Our findings confirms the main factors that determine bad loans but also opens the door for implementation using in house data

# What is Lending Club?

LendingClub is a US peer-to-peer lending company, headquartered in San Francisco, California. It was the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market. LendingClub is the world's largest peer-to-peer lending platform.





# Summary

1. Most of the loans issued were in the range of 10,000 to 20,000 USD.The year 
2. 2015 was the year were most loans were issued
3. Loans that have a high interest rate(above 13.23%) are more likely to become a bad loan .
4. Loans that have a longer maturity date (60 months) are more likely to be a bad loan.
5. The reason that client applied the most for a loan was to consolidate debt
6. Renters are more likely to default on a loan vs Home Owners
7. Feature Reduction and Deep Learning Models on a larger dataset as well as better handling of missing values can improve model performance

