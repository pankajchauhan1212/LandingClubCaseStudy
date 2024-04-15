# Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
 There is a consumer finance company, when the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
 Two types of risks are associated with the bank’s decision:
 
 1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
 
 The data provided in loan.csv contains information about past loan applicants and whether they ‘defaulted’ or not. 
 The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, 
 reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 
 we need to perform EDA to understand how consumer attributes and loan attributes influence the tendency of default.
 Or we can say that we need to figure out the driver variable for the applicants likely to default, the company can further
 utilize this knowledge for its portfolio and risk assessment 



## Conclusions
- Customer took loan maximum for debt_consolidation
- Customers has taken more lone for amount 500 to 20000 and if the loan amount is high then there are more chances of defaulters
- Customer with own home are applying less for loan, in other words the customers with Rented home and Mortagage are more in numbers
- Customer with the grade A are less likely to default but when the grade is increasing the defaulter percentage is also increasing
- Customers who have higher intrest(more then 15%) rate are likely to default and the customer with lesser intrest rate are less likely to default




## Technologies Used
1. pandas
2. numpy
3. matplotlib
4. seaborn


## Contact
Created by pankaj chauhan : GitHub - [@pankajchauhan1212] - 


