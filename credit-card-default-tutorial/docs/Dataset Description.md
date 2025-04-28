## Dataset Description 

We will use the credit card default dataset from the UCI Machine Learning Repository. Some key features about the dataset are as follows:
-  24,000 observations made by a bank in Taiwan on distinct credit card holders from April 2005 to September 2005. (./data/raw/data.csv) 
- binary variable default.payment.next.month as response variable.  It indicates whether or not the credit card holders are defaulters next month (Yes = 1, No = 0)
- 23 features are available to predict the response variable. 

- Client personal information:
1. `LIMIT_BAL`: Amount of given credit (in New Taiwan dollars): it includes both the individual consumer credit and his/her family (supplementary) credit.
2. `SEX`: 1 = male; 2 = female.
3. `EDUCATION`: 1 = graduate school; 2 = university; 3 = high school; 4 = others.
4. `MARRIAGE`: Marital status, 1 = married; 2 = single; 3 = others.
5. `AGE`: Age in years.

- History of past payments from April to September 2005, i.e., the delay of the past payment referred to a specific month: 6. `PAY_0`: Repayment status in September, 2005. 7. `PAY_2`: Repayment status in August, 200; ...; `PAY_6`: Repayment status in April, 2005.

The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; ...; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

- Amount of bill statement (in New Taiwan dollars), i.e. a monthly report that credit card companies issue to credit card holders in a specific month: 12. e.g., `BILL_AMT1`: Amount of bill statement in September, 2005. 13. `BILL_AMT2`: Amount of bill statement in August, 2005 ; ...; 17. `BILL_AMT6`: Amount of bill statement in April, 2005.
- Amount of previous payment (in New Taiwan dollars): 18. e.g., `PAY_AMT1`: Amount of previous payment in September, 2005;...; 23. `PAY_AMT6`: Amount of previous payment in April, 2005.
