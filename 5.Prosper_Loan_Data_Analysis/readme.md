# Loan Data Exploration

## by Suresh Lokiah

## Dataset

The dataset is made up of 113,937 rows and 81 columns. The features in the dataset was organized by Loan Listing, Loan, Borrower Demographics, Borrower Credit Information, Investor and Loan ChargeOff . Here is the [dataset](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) and [variable definition](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).  

The dataset was methodically analyzed using a variety of plot types to explore different relationships in the dataset. The findings were documented as 'Notes' after each plot or analysis. Some of the analysis were further drilled-downed to explore patterns.

(The resulting report in slides was peer-reviewed and improved).

The Goal for this analysis is to understand the Loan characterstics that investors must consider to have higher Yields. The Key features that were considered for the analysis are  -> ListingCreationDate, ListingCategory, LoanOriginalAmount, EstimatedReturn, LoanStatus, Term, CreditGrade, BorrowerAPR, BorrowerRate, BorrowerState, Occupation, Recommendations, ProsperScore, LenderYield.

## Summary of Findings

The visualization reveals that for Higher LenderYield the Lender may focus on Loans having the following characterstics:

* Loans around 10k, with 36 Month Term. And additionally, when the RiskScore is 'C', 'D', 'E' and Borrower CreditScoreRangeLower is higher

Interestingly we notice that there are large number of investors going for loans with higher ratings for RiksScore (AA, A, B)
We also notice a corrleation of  Borrowers-IncomeRange to higher Loan Amount

We notice Positive Correlation between BorrowerAPR and LenderYield and slightly positive correlation between CreditScoreRangeLower to  Investors. From our final analysis it seems that Investors may benefit from having higher correlation to CreditScoreRangeLower

Borrower:
The Top 5 Borrower States CA', 'TX', 'NY', 'FL', 'IL' and Borrowers IncomeRange is between 25,0000 - 75,000. Many Borrowers have more than 1 PropserLoans. And we notice that Borrowers on Loans had mostly 0 or < 5 Recommendations() and > 5 Recommendations was very less. )

## Key Insights for Presentation

Seems like investors are teaming up on Loans that have Higher RiskScore  ratings ('AA', 'A', 'B'). However, the our data analysis reveals that Loans with Rating 'C', 'D', and 'E' may give higher yield.  The graphs in the section -> Loans with RiskScore 'C', 'D', 'E'  shows the exact criteria for such loans the Lender may consider.
