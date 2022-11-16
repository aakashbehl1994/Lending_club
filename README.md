# Lending_club
> This project is for a consumer finance company which works in lending loans to customers. When the company receives a loan application, it has to make a decision based on the applicant’s profile.


We will use EDA to understand what consumer and loan attributes influence the tendency of a default.


* Conclusions - The default rate has been analysed with variables such as GRADES, ANNUAL INCOME, PURPOSE OF LOAN, DEBT-TO-INCOME RATIO and finally for SMALL BUSINESS OWNERS having different GRADES since SMALL BUSINESS OWNERS had the maximum default rate 
* Group member - AAKASH BEHL


## General Information

The data given to us has the information about loan applicants and if they Defaulted or not. The objective is to identify patterns in the data that if a person is likely to default or not, which may be used for denying him the loan or reducing the amount of loan and also lending risky applicants at a higher interest rate, etc.

## Conclusions
- Many people whose status was not verified were given loans
- Many loan are taken for debt consolidation and lot of them are becoming bad loans
- We are making charged off proportion as the key indicator as that explains the proportion of defaults, which is most important for us
- We can see Grade A has the least defaults
- We can see that as income goes higher the percentage of charged off loan decreases
- Small business have the highest rate of default
- Car, credit card and Wedding loans have the lowest rate of default
- Inference - DTI of over 19 has the highest rate of default and as people are more in debt as compared to the income, the chances of default increases
- Since small business owners had the maximum default rate, so looking down futher into that data.We can see that grade D, E, F and G have 30%- 45% default rate
- Inference - Small business owners with D,E,F,G grade have the highest default rate




## Technologies Used
- python -3.7.13
- pandas - 1.3.5
- matplotlib - 3.5.2
- numpy - 1.21.6
- seaborn - 0.11.2


