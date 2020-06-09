# ProsperLoan Data Exploration

## Dataset

This [data set](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547699802003000)
contains 113,937 loans with 81 variables on each loan, including loan amount, 
borrower rate (or interest rate), current loan status, borrower income, and many others.
A pdf named "ProsperLoanData.pdf" is presented that will explain all Dataset's Variable.
The project objective is not expected to explore all of the variables in the dataset! But focus on only exploration on about 10-15 of them.

## Summary of Findings


* LoanStatus of all Borrowers are with current and completed state
* EmploymentStatus of all Borrowers are with Employed State
* Majority of the loan applicants are from 50K to 75K range with emloyeed status
* The distribution of monthly income of applicants is a right skewed because there will be few applicants with high salary. 
* Applicants with incomerange of 50K to 75K range have their prosper rating falling under AA, A, B and C 
* LoanStatus with current and completed have own homes when they applied for loans
* The monthly income of borrowers are having higher values for employed, other and full time employment status with the prosper rating of AA, A and B
* We observe that without homeowner tend to have a higher interest rate, and thus lower rating.However homeowner tends to have lower interest rate and higher rating. So we can safely say that homeowner is safest bet when gving a loan. We can also clearly observe that HR prosper rating applicants have higher interest rates


## Key Insights for Presentation

For the presentation, I focused mainly with the features that are impactful for approval of loanstatus
I start by looking at the distrbuiton of each and every numeric and categorical variables and did all the necessary univariate, bivariate and
mulitvariate analysis on the selected varaibles.

The major insights obtained are :


* Majority of all Borrowers had loanStatus with current and completed state
* EmploymentStatus of all Borrowers are with Employed State
* Top IncomeRange of all Borrowers are within $50,000-74,999
* Majority of the borrowers are with an occupation of Professional and Executive
* Majourity of the Borrowers are Employed with about 90%(i.e almost 70000 people)
* The borrowers rate follow an approximately unimodal distribution, with the peak around 0.16. 
* The most common Proper rating the the borrowers get was C(4) with 21.6% or we can say that 21.6% borrowers get Prosper rating of C but only 6.7% borrowers get the Rating of AA (7)
* The loan applicant that has the Income range form 1− 24,999 has very low loan amount in compaired to lest of the applicate having higher than the folloeing income range
* For any Income Range of Occupation , the most common PropserRating will Be C(4)
* Loan original amount and monthly loan payment is highly correlated and it is expected and borrowers interest rate and proper score are highly correlated(-vely), Borrower interest rate and loanamount are -vely correlated.


To conclude this analysis , I say that the loan approval status is heavily dependent on the applicant's information on IncomeRange,
 Homeownerstatus and employment status.
