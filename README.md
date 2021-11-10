# Lending Club Case Study (EDA)
    The aim of this project is to identify the factors of the high risk applicant who are much likely to default.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
   A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

> If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

> If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

 
  The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. 
    
   The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

 
   In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
   

## Technologies Used
- Pandas
- Numpy
- Matplotlib.pyplot
- Seaborn

## Conclusions
    1. Gradation system may be used as a reliable indicator. Probability of default increases linearly with worsening grade.
    2. Loan applicant with annual income below 10000 more likely to default compare to others.
    3. Loan should be approved after careful scrutiny for person with lower income,  who opted for longer term loan and higher interest rate
    4. Person taking loan for small business purpose is more likely to default
    5. History of public record bankruptcy is an early warning sign of possible future default.
    6. Loan amount above 25000 is more likely to default. It should be sanctioned only after considering grade and other mentioned indicators
    7. Charge off percentage increases when the interest rate is increased.
    8. Also longer term increases the chances of getting defaulted.

## Methodology 

- Data Understanding
- Data Manipulation and cleaning
- Exploratory Data Analysis
- Recommendations

