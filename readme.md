# Lending Club Case Study.
Lending club is a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision.

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.


## Table of Contents
* [List of tasks](#list-of-tasks)
* [TechnologiesUsed](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## List of tasks
- Data Understanding.
- Data Cleaning and Manipulation
- Univariate Analysis
- StandardUnivariate Analysis
- Bivariate Analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Conclusion from univariate analysis
  - Higher loan amount casues more default cases compare to lower loan_amount
  - Annual Income between 35000 to 66000 more prone to charging off from their loan
  - Average Interest Rate value of charged off has higher than fully paid rate, Higher interest rates may leads to charged off
  - Grade C has high charged off cases, sub_grade C2 has highest charged off cases
  - More expierenced customers(10+ years) has high prone to charged off
  - Rented Source Verified has highest number of Charged Off cases
  - Debt consolidation purpose has high number of loans.
  - Small_busniess loans high in Charged Off case compared to whole number of loans.
  - zip_code range from 900 -999 are taking more number of Chraged Off loans
  - CA state taking more loans and more tends to charged off as well
### Conclusion from bivariate analysis
  - Higher loan amount with higher interest rate leads to ChragedOff cases
  - Higher Income with higher loan_amount leads to Default
  - Lower Dti with interest rate between 11-16% leads to Default
  - More Default cases we can see here in Ownership as Mortgade and emp_length > 10 years
  - High interestrate with 60 months tenure has high probability of 'Charged Off'
  - ZipCode in 900 -999 range(CA state) highest number of default cases Comparitvily high in December month

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas version 1.5.3
- numpy version 1.23.5
- matplotlib  version 3.7.0
- seaborn version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@sunilkumar0007] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
