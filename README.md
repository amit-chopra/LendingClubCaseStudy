# LendingClub
> The aim of this exploratory data analysis is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate


## Table of Contents
* [General Info](#EDA: understand attributes that may influence tendency of default)
* [Technologies Used](#python, pandas, seaborn)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


- Business Probem: Can we identify patterns to identify cusomters that may likely default on loans?


- Lending Club data set has been used. However, many customer behavior attributes were not available for analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loan amount, Funded amount and Funded amount Investor are right skewed distributions with median loan amount ~$10,000 and Inter Quantile Range from $15,000 to $5,000

- Consumers who had DTI >25 & loan amount > average loan_amount had loan amount to annual income ratio of 29.38% compared with 16.27% for entire population. This loan amount to annual income percentage drops to 14.75% when the Verification status of the customer is 'Source Verified'. This may lower chances of customer default

- When Source is Verified, percentage of loans given to customers with lower DTI increases compared with percentage of loans given to customers with higher DTI. 

- Further analyis will be done with more behaverial data 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn


