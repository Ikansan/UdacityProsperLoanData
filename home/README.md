# (Prsoper Loan Data)
## by Awaji-kansan Obediah Iduinung


## Dataset

> I worked on the Prsoper Loan Dataset which consists of 113,937 rowas and 81 columns. Some of the variables contained in the dataset are:Term, ListingCategory (numeric), CreditGrade, EstimatedReturn, Investors, StatedMonthlyIncome, AmountDelinquent, ProsperScore, LoanOriginalAmount, MonthlyLoanPayment, LoanStatus, BorrowerRate, ProsperRating (Alpha), LoanOriginationDate, EmploymentStatus, Occupation, IncomeRange.

> Before I started exploration, I selected these variables to consider: Term', 'ListingCategory (numeric)', 'CreditGrade', 'EstimatedReturn', 'Investors', 'StatedMonthlyIncome', 'AmountDelinquent', 'ProsperScore', 'LoanOriginalAmount', 'MonthlyLoanPayment', 'LoanStatus', 'BorrowerRate', 'ProsperRating (Alpha)', 'LoanOriginationDate', 'EmploymentStatus', 'Occupation', 'IncomeRange'
After that, I dropped the missing values in the ProsperRating (Alpha), AmountDelinquent, ProsperScore, EmploymentStatus, Occupation columns, and converted the datatype of LoanOriginationDate to datetime.


## Summary of Findings

> My interest was to find how the the prosper rating is affected by employment status, loan status, and how it also relates to the original loan amount and the loan term. During the exploration, I found out that there is a direct relationship between the prosper rating, loan amount and term of the loan.

> To properly visualise the LoanOriginalAmountand MonthlyLoanPayment, I used the log scale to reveal hidden points in the variables.

## Key Insights for Presentation

> My main focus was on how Prosper Rating relates to the Employment and Loan Statuses, the Listing Catefory and the Original Loan Amount. I started by visualising the individual variabe of interest. A pointplot of Loan Original Amount vs Prosper Rating Vs Term indicaated a clear relationship among all three vairables

> The appropriate plots for the varibale types were used and I was able to deduce how the prosper rating relates with the other variables under investigation.