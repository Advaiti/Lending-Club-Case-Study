# Lending Club Case Study
> A comprehensive analysis to identify the key factors influencing loan defaults and provide actionable insights for better risk management.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background: This project involves analyzing a dataset containing information about past loan applicants to understand the factors that influence loan defaults.
Business Problem: The primary goal is to minimize financial losses due to loan defaults by identifying risky applicants. By understanding the driving factors behind defaults, the company can make informed decisions on loan approvals, set appropriate interest rates, and manage risk effectively.
Dataset: The dataset includes detailed records of loan applications from 2007 to 2011, including applicant demographics, loan characteristics, and repayment status.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Most of the loans are of short term (36 months)
- Most of the loans are for debt consolidation purpose
- Most of the loans are taken by people who live in a rented accomodation or mortaged properties.
- Loan count has an increasing trend both month-wise (Jan-Dec) and year-wise (2007-2011)
- Loan Amount: Higher loan amounts are associated with higher default rates, indicating increased risk with larger loans.
- Borrowers with annual income exceeding $15,000 are less likely to default.
- Interest Rates: Borrowers with higher interest rates tend to default more, suggesting that higher rates are a risk indicator.
- Annual Income: Lower annual incomes correlate with higher default rates, emphasizing the importance of assessing borrower income.
- Debt-to-Income Ratio (DTI): Higher DTIs are linked to increased default risk, indicating over-leveraged borrowers are more likely to default.
- Loan Term: Loans with longer terms (60 months) have higher default rates compared to shorter-term loans (36 months).
- Home Ownership: Homeowners have lower default rates compared to renters or those with other housing situations.
- Verification Status: Verified income status is associated with lower default rates, highlighting the importance of income verification.
- Employment Length: Longer employment history correlates with lower default rates, suggesting job stability is a key factor in loan repayment.
- Loan Purpose: Certain loan purposes, such as small business loans, have higher default rates compared to others like credit card refinancing.
- Geographic Influence: Default rates vary significantly by state, indicating regional economic factors play a role in loan repayment.
- Public Record Bankruptcies: Borrowers with public record bankruptcies have higher default rates, underscoring the risk associated with such histories.
- Debt consolidation accounts for the majority of loan investments and exhibits a notably high default rate exceeding 15%.
- Loans issued in 2009 saw a decreased default rate, likely due to more cautious lending practices post the 2007-2008 banking crisis.
- Loans with grades of 'C' and higher exhibit a high default rate, notably exceeding 40% for F5 and G3 grades.
- There is a pronounced increase in default rates for loans with interest rates exceeding 12.5%.
- Default rates surpass 30% for loans with interest rates greater than 20%.
## Recommendations
### Discontinue
- Loans to borrowers with more than one public record of bankruptcy
- Loans to Grade F borrowers
- Loans with an interest rate above 20%
### Reduce
- Loans to borrowers with annual incomes less than $15,000
- Loans to borrowers in Florida, New York, Nevada, California, or Texas
- Loans to borrowers with grades above 'C'
- Loans with an interest rate above 12.5%
- Loans with a term of 60 months
### Increase
- Loans with interest rates between 7.5% and 10%
- Loans to Grade 'A' borrowers
- Loans to borrowers with zero public record bankruptcies
- Loans with a term of 36 months
- Loans for credit card consolidation purposes
- Loans with smaller amounts
- Loans to borrowers with lower debt-to-income ratios



## Technologies Used
- Pandas - version 1.3.3
- NumPy - version 1.21.2
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2
- Jupyter Notebook

## Acknowledgements
- This project was inspired by real-world applications of risk analytics in the banking and financial services industry.
The project was based on the EDA techniques and methodologies taught in various data science and analytics courses.
Special thanks to the contributors of the dataset and the resources available on risk management.


## Contact
Created by [Chidambaram-Ananthakrishnan](https://www.linkedin.com/in/chidambaram-ananthakrishnan/)

