# Prosper Loan Data Exploration
# by Rasha Hosny


## Dataset

> The data consist of 113937 loan record with 81 variables starting from 2005 till 2014 with a lot of information about loans and borrows. I select 18 total variable, in which 5 discrete variable and 13 continuse one. 
> I am most interested to see the some data related to the borrowers such as income to dept ratio and what they can afford on monthly baseis. Also I want to investigate some data related to the loan it self such as Loan Origination Quarter, loan status, APR. I expect that occupation and monthly income will affect the loan amount and its annual interest. 
> There are a lot of data about the borrower, so I think by multivariant analysis these vaibales I could find intersting things.
> I download the data from this link: https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv 

## Summary of Findings

> There are positive strong relation between borrowerAPR and borrowerRate and between upper and lower credit score
> Borrowers with lower APR are retaired, part time and full time jobs. While the largest APR is for not employed which is logic. this is also reflected on BorrowerRate. For credit score I found that borrowers with lower score (upper and lower)is that havn't identifyed jobs
> There is no correlation beween 'MonthlyLoanPayment', 'IncomeRange', 'StatedMonthlyIncome', 'DebtToIncomeRatio', 'OnTimeProsperPayments'
> Loan statuse affected by occupiation, loan type and employment status. Most of dept consoldation is with current status while only 30% was completed. Also when employment status is employed, the current loan status is the largest count with about 45% of the records.
> The best APR is below 0.1 for borrowers with prosper score more than 10. Also the best dept to income ratio is for less than 1.
> Time effect on income range and listing category, in which by 2013 the income increase and subsequently the loans increase.

## Key Insights for Presentation

> First, histogram plot were created to visualize the distribution on borrower's APR percentage. After exploring all possible variables related to BorrowerAPR. ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). Scatter plot and Heatmap were also created to find out that ProsperScore and BorrowerAPR were negatively correlated. The third plot created multiple scatter plots (BorrowerAPR vs ProsperScore) on different letter ratings. The plots showed the lowerest rating(HR) of borrowers received the highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage.