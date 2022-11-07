# (Prosper Loan Data Exploration)
## by (Bruce Mahagwa)


## Dataset

The Dataset https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000used for this project contains 81 variables containing information about Prosper Bank transactions from the period 2007 and 2014. This analysis focused on the following variables: LoanStatus, EmploymentStatus, CurrentDelinquencies, IncomeRange, IsBorrowerHomeOwner, BorrowerRate, ProsperPrincipalBorrowed, Term, BorrowerAPR, AmountDelinquent, EmploymentStatusDuration, DebtToIncomeRatio, LoanOriginalAmount, LoanOriginalAmount, and LenderYield.

_Note_
This project focused mainly on using matplotlib and seaborn visualizations to uncover insights.
Part One contains the exploratory phase where I endeavor to uncover insights whereas Part 2 is the explanatory phase where I explain the key findings of the investigation with just a few visualizations. I have also created a slide presentation of part 2.

## Summary of Findings

The analysis successfully investigated 16 variables to uncover insights using univariate, bivariate, and multivariate plots. The following are some key findings from each section of the analysis.
### Univariate
1. Most accounts are either currently active or already completed. However, there is also a significant number of accounts are chargedoff or defaulted.
2. Most accounts are owned by people who are employed. The retirees have the smallest share of accounts. 
3. Most accounts have zero delinquencies.
### Bivariate
1. As Principal Borrowed increases, Borrower Rate decreases.
2. There are more delinquencies in the 36-month Term than any other Term.
3. As Borrower Rate increases, current delinquencies also increase.
4. Most loan accounts have a loan amount of less than 10,000 dollars.
5. Most accounts that are delinquent are delinquent on amounts below 10,000 dollars. 
6. There is no obvious relationship between Debt to income ration and employment duration.
7. As Term increases, Lender Yield does NOT increase.
### Multivariate
1. The unemployed have the highest BorrowerAPR rate.
2. Retirees spend the least amount of time paying loans.
3. The employed borrow the most amount of money.
4. The employed take the longest amount of time to pay.
5. Individuals under the "Not displayed" income group have the lowest amount delinquent.
6. Individuals under the "$100000" income class have one of the highest amount delinquent.


## Key Insights for Presentation
1. Prosper bank is good at handling its accounts becuase most of their loan accounts are either being currently serviced or are completed. Additionally, the accounts that are delinquent have low delinquent amounts of less than 1000 dollars.
2. As the cost of borrowing increases, it is very likely that there will be more delinquent accounts. This observation is supported by the fact that as one borrows large sums of money at Prosper Bank, the Borrower Rate reduces. Since the bulk of accounts at Prosper Bank have low loan amounts, the loanees pay a high Borrower Rate and thus are more likely to have more delinquent accounts. 
3. Customers at Prosper Bank under the "Not displayed" income group have the least amount of money delinquent whereas those with the 100, 000 dollar income group has the highest amount of money delinquent.
