# Lending Club Case Study
## Problem Statement

### Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. **Two types of risks are associated** with the bank’s decision:
1. If the applicant is **likely to repay the loan**, then not approving the loan results in a loss of business to the company 
2. If the applicant is **not likely to repay the loan**, i.e. he/she is likely to default, then approving the loan may lead to a **financial loss** for the company.

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

 
 ![LendingClubCaseStudy](LendingClubCaseStudy.png)
 When a person applies for a loan, there are **two types of decisions** that could be taken by the company:
1. **Loan accepted**: If the company approves the loan, there are 3 possible scenarios described below:
    1. **Fully paid**: Applicant has fully paid the loan (the principal and the interest rate) 
    2. **Current**: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    3. **Charged-off**: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
2. **Loan rejected**: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 
 The company wants to understand the **driving factors (or driver variables) behind loan default**, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment thereby **cutting down the amount of credit loss**. 

### Recommendations
- Better to reduce the interest rates for small businesses to reduce the default rates less than 12%.
- Based on the analysis the loan company should expand on various states apart from NY and CA only which have earning potential or more equivalent to these states.
- Should target age groups more between 3- 9 years by providing lower interest for purposes like home ownership.
- Risky purposes such as vacation ,moving  etc the rate of interest should be increased as the risk of default exposure will be covered . If not to avoid certain states with certain purpoes which have a high default record should be avoided
- Lending less than 10K which mitigate the risk of default
- Should avoid giving low income group high amount loans above 10k especially states having low income.
