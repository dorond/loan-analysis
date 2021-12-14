# Prosper Loan Data Exploration

## Dataset

A dataset consists of 113,937 Prosper loans, including 81 variables such as 
loan amount, borrower rate/interest rate, loan status, borrower income and many others.
The dataset can be found [here] (https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

The goal of this analysis is to answer the following question: What affects the borrowers interest rate? 


## Summary of Findings


In this exploration, I found that the Prosper Rating given to each applications 
is the determining factor in the offered borrower rate. The contibutions to this 
score are home ownership, income range, debt to income ratio, credit score, employment status.
It seems that these all make small contributions to determining what the Prosper Rating is, 
rather than it being attributed to a single major variable.
Being a home owner, having a higher income, a lower debt to income ration, 
a higher credit score and being full-time employed tend to attract lower borrower rates.
Those not employed tend to get the highest borrower rates, while full-time employed persons 
earning between 50K and 100K+ tend to get the lowest borrower rates.


Outside of the main variable of interest, it was noted that home owners tend to 
have a lower debit to income ratio while having more credit lines over the last 7 years.


## Key Insights for Presentation

For the presentation, I will focus on the relationships between 
Prosper Rating, income range, employment status, home ownership and borrower rate.
I start by introducing the borrower rate distribution, before exploring the relationship between
Prosper Rating and Credit Grade with the borrower rate using box plots. This leads
to the relationship between employment status, income range and borrower rate.

Next I combine these variables together, along with home ownership to get a more
complete picture of the effects of these variables on borrower rate and posrper rating/credit grade.
This is done with a mixture of faceted histograms, scatter plots and bar charts.
