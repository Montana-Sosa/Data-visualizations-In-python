# (Loan Data Exploration)
## by (Williams Miebi)


## Dataset Overview:
The provided data set consists of several key performance indicators such as borrowerAPR,borrower rate,income range, prosper rating, etc of 113937 loans.The key performance indicators are what determines if a prospective borrower will be granted a loan and how many percent interest will charged for the loan and the time duration that will be granted for payment of the loan.

## Summary of Findings
### INSIGHT 1:
After exploring the dataset, I observed that there are certain key factors that affects/influences if a borrower will get their loan approved or not and how much interest they will be charged for their loans.
By examining Certain key performance indicators such as the prosperscore, prosper rating.
I was able to observe how certain others factors influences/affetcs the prosper score, prosper rating.
The following factors below was observed to affect the KPI's:
1.Credit score
2.Revolving credit balance
3.Stated monthly income
4.Debt to income ratio
5.Avaialble bank credit.
6.Is borrower home owner or not
The creditscore have a strong negative correlation with the borrower APR and Borrower rate, the plots showed us that the higher the credit score, the lesser the borrower APR and borrower rate charged on the loan collected by the borrower.
Credit score also had a strong positive correlation with prosper rating and propser score, this did not come as a surprise.
Surprisingly revolving credit balance was found to have a positive correlation with the prosper score. Maybe it's because  a higher revolving credit balance is indicative of the borrower's consistency in paying back their loans and having a good track record.
I also found out that borrowers with higher prosper rating tends to have a better monthly income.The both variables were found to have a positive correlation.
Debt to income ratio was negatively correlated with the prosper score, the plots indicated that a higher debt to income ratio will result in a lower prosper score and this ultimately affects if the loan will be approved for the client or not.
Available bank credit also plays an important role in determining the borrowers prosper score and prosper rating.It was seen to have a strong positive correlation with the loan original amount, and the creditscore as well.The higher the available bank credit, the higher the prosper rating and score.
It was surprising to see the data indicate that clients with a high propser rating will be charged a higher interest rate(borrower APR) with a higher loan amount, it was a bit shocking, but made alot of sense.
Borrower Rate and prosper rating have a strong negative correlation,the better the propser rating, the lesser the interest rates(borrower APR).
Owning a home while applying for a loan affects the outcome of the loan. It was seen via the plots that homeowners had higher counts in the top four prosper rating categories.
### INSIGHT 2:
The following factors were found to have a strong correlation with borrower APR;
1.prosper rating
2.Prosper score
3.Credit score
4.Delnquencies in past 7years
5.Available bank credit
6.Loan Original Amount
7.Debt to income ratio
The factors above either had a negative or positive correlation with borrower APR.
### INSIGHT 3:
The 12 months sub category of the term variable had the highest APR, while the other two were of the same value.
There was an increase in the rate from 12 to 36 months and from 36 to 60 months, there was no increase .
This indicates that the term appers to have an effect on the borrower rate and not have a very significant effect on the annual interest rates that the client will be charged.
In summary the loan term has a very little effect on the annual APR , but a slightly stronger effect on interest rates.

## Key Insights for Presentation

For the presentation, i will be looking at what factors affects outcome of a loan's status, to see if it will be accepted or rejected, I will also take a look at if the loan term affetcs the annual percentage rate of the borrower.
I focused on factors that had either a strong positive or negative correlation with the prosper score and prosper rating .
I started by examining the distribution of variables and afterwhich a heatmap was used to get a general overview of the correlation of both categoricl and numerical variables. After which different kinds of plot was used to get a clearer relationship and correlation between variables that affects the prosper score and ratings.I also used a plot to display the effect of loan term on prosper rating and borrower APR.