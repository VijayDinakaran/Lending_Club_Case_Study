# Lending_Club_Case_Study
This case study aims to identify loan applicants who present a higher risk of default and to analyze the factors that contribute to loan defaults.

### Problem Statement

Our goals in this case study are to determine which loan applicants are at a higher default risk and to examine the contributing reasons for these defaults. We will learn more about applying exploratory data analysis (EDA) to real-world business issues in the banking and finance sector by solving this case study. In addition to using EDA approaches, this study will contribute to the basic understanding of risk analytics in banking by showing how data may be used to reduce financial losses resulting from defaults.

### Business Understanding

Lending club, a consumer finance company that focuses on offering different kinds of loans to clients in different cities. Based on the applicant's profile, the corporation must determine whether to approve a loan application after receiving it. This choice carries the following two main risks:

    1.The company loses business if the loan is denied even though the applicant is likely to repay it.
    2.The company may suffer financial losses if the loan is approved if the applicant is likely to default on the loan.

The provided data includes information about past loan applicants and whether they defaulted or not. The objective is to identify patterns that indicate the likelihood of a person defaulting. This information can be used to make informed decisions such as denying the loan, reducing the loan amount, or lending to risky applicants at a higher interest rate.

### Loan Application Scenarios

When a person applies for a loan, the company can either accept or reject the application:

**Loan Accepted:** If the loan is approved, there are three possible outcomes:

**Fully Paid:** The applicant has repaid the loan in full, including the principal and interest.

**Current:** The applicant is in the process of repaying the loan; the loan tenure is not yet completed.

**Charged-Off:** The applicant has defaulted on the loan, failing to make payments for an extended period.

Loan Rejected: The company rejects the loan application if the candidate does not meet the requirements. There is no transactional history available for these applicants in the dataset.
Goal of the Python Code

#### The Python code presented here will:

    1.Perform Exploratory Data Analysis (EDA) on the provided dataset to uncover patterns and relationships between consumer attributes, loan attributes, and the likelihood of default.
    2.Identify and analyze key variables that serve as strong indicators of loan default.
    3.Generate insights that can inform the company's decision-making process regarding loan approvals, thereby reducing the risk of financial losses due to defaults.

The ultimate objective is to utilize data-driven insights to enhance the company's risk management strategies and improve the overall efficiency of the lending process.

#### Conclusions

**Correlation Matrix**
1. Loan amount, investor amount and funded amount are strongly correlated among each other.
2. Annual income with DTI (Debt-to-income ratio) is negatively correlated, that means whenever annual income is low DTI is high & vice versa.
3. There is a positive correlation between annual income and employment years which means income increases with work experience

**Segmented Univariate Analysis**
1.Most of the loans were taken for the purpose of debt consolidation & paying credit card bill
2. Comparatively number of charged off count are also high for the loans taken for these 2 purpose
3. Most of people took loan who live in rented house or have mortgaged their property

**Bivariate Analysis**
1. Grade "A" has very less chances of charged off
2. Grade "F" and "G" have very high chances of charged off

#### Technologies Used
pandas version: 1.5.3
numpy version: 1.24.3
seaborn version: 0.12.2


#### Acknowledgements
- This project is done as part of IIIT Bangalore Post Graduate Certificate in AI/ML course
  
Presented by:<br>
Vivek Vikash<br>
Vijay Mallepudi<br>

