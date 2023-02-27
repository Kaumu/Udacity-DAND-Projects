# Prosper Loan Data
## by Kaumudi Moholkar


## Dataset

> The data has 113937 rows and 81 columns. It has majorly numeric data and a few objects. It has all the information on the loan status, employment status, loan payment information, and so on.  The main area of interest in the columns are Loan status, Employment status, borrower APR, Income range, Income Verifiable, Stated Monthly Income, Debt to Income Ratio, Loan Original amount and so on. 

## Summary of Findings

> I have focussed on predicting which type of loans are more prevalent and if any steps can be taken to improve the company's loan allotment criteria. So I analyzed the numerical and categorical data. 

Categorical Data:

1. Loan Status

2. Employment Status

3. Income Verifiable

4. Income Range

5. Occupation

6. Stated Monthly Income

7. Term

Numeric Data:

1  Borrower APR

2. Debt to Income Ratio

3. Loan Original Amount

> There is a higher APR for the charged-off status across multiple employment statuses. Also, full-time employers have a higher APR range. This can mean there is no proper background check taking place before loan approvals. 
    People working part-time have more loans past due dates indicating they take higher loans than they can afford to pay. Also, self-employed people have default loan status for larger loan amounts, which makes both a high-risk category for future loan approval. 
    The loan amount does not increase linearly with the Income range but we can see that there is an increase in the loan amount with the increase in income.


## Key Insights for Presentation

> There are approximately 12000 charged loans, which is smaller than the rest of the loan status. But there is a multimodal graph, with many small peaks, with one peak of 1500 which is the largest at APR of 0.36. This can clearly states that there are loans allowed although there is a higher APR. These eventually resulted in being charged off. So there was no proper vetting done before loan allotment.

> There are about 26000 employees in full-time employment. With so many people working full-time, people can be expected to be in the lower APR category. This is true for the most part, but then there is a big shoot-in peak with about 1300 people lying in the category of 0.38 APR. This can mean that the vetting or background check before loan allotment is not being done properly overall. 

> For the category of people who are self-employed, there are a lot of loans approved for them. The loan amount ranges from 1000 to 25,000. This is a really great figure. But there are a lot of people falling into the defaulted loan category. This can be observed from the plot, defaulted has the highest range. This means there is a high-risk category for future loan approval.

> There can be observed an increase in the loan amount with respect to an increase in income. There is not any linear increase in the loan amount, but a small amount can be seen with a greater increase at 100,000+ income range people. The income range of 0 dollars cannot be regarded as there is a lot of data where the income range is not displayed or employed. Based on the plot we cannot necessarily state that people with no income displayed lie in the category of 0. 
