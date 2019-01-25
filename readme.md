# Data Analysis of Loan from Prosper


## Dataset

This dataset is a record of loans from Prosper from 2007 to 2014, It records 113,937 loans with 81 variables on each loans. Of these variables, we're particularly interested in factors that affect whether or not someone make paymeny to their loan. In addition, it will also be interesting to see whether the characteristics of borrowers, such as income or job, will affect loan characteristics, such as loan amount, APR or interest rate.


## Findings

**1. Distribution of variables**  
Borrower's APR and interest rate follow a similar distribution, which is slightly bimodal. The mean APR is 0.22 and the mean interest is 0.19. We define good loans as loans with status of completed, current, or finalpaymentinprogress, and bad loans as loans with status of chargedoff or defaulted. Thus, 85% of total loans are good loans, 10% are bad loans. The rest of loans are pastdue. 96% borrowers have a jod, of which most are professionals, and most of them live in California. Roughly half of the borrowers own a house. Borrowers have a mean credit score between 500 and 900, with the mean as 702. Borrowers have an average credit history of 16 years. The distribution of borrowers' monthly-income is strongly right skewed, with a few people having extremely high monthly-income, which does not seem likely. Median income is 4833 dollar per month. The distribution of total loan amount is also right-skewed, with the median being 7000 dollar.  
  
**2. Factors that affect whether a borrower pay his/her loan on time**  
We define good loans as loans whose borrowers pay on time. These are loans with status of completed, current, or finalpaymentinprogress. We define pastdue as loans whose borrowers failed to pay on time within a certain amount of time, most likely within 120 days. We define bad loans as loans whose borrowers failed to pay for an extended period of time, or loans that no longer expect further payments. These are loans with status of chargedoff or defaulted.  
Several factors contribute to whether or not a loan being paid. Loans with lower APR and interest rate and higher original amount are more likely to be paid. Borrowers with higher credit score and longer credit length are more likely to pay on time.  
  
**3. Characteristics of borrowers that affect APR and interest rate**  
Several characteristics of borrowers affect the APR and interest rate of their loans. Unemployed borrowers tend to have higher APR and interest compared to people who have a jod and who have retired. Home owner tend to have a lower APR and interest rate compared to people who do not own a home. Credit score inversely correlates with borrower's APR and interest rate: people with a credit score between 800 and 900 have the lowest APR and interest rate. Monthly income also inversely correlates with APR and interest rate. People earning the lowest salary tend to have the highest APR and interest rate.  
  
**4. Characteristics of borrowers that affect total loan amount**  
Employed people have the highest total loan amount compared to unemployed and retired people. Home owners tend to have higher total loan amount compared to people who do not own a home. Monthly-income positively correlates with loan amount. People earning 18000 dollars or more each month have the highest total loan amount. While people with credit score below 600 have much less total loan amount compared to people who have higher credit score, total loan amounts remain the same for people who have credit score above 700.   
  

## Key Insights for Presentation

1. APR, interest rate, total amount of loan, and the credit score of borrowers were the main factors that may affect whether a loan have been paid on time.  
2. Employment status, credit score and income level are the main factors that affect a person's APR and interest rate.  
3. Employment status, home-owner status, credit score and income level are the main factors that affect a person's original total loan amount.  


