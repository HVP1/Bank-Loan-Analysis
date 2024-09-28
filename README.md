# Loan Risk Assessment Project

## Analyzing Risk in Banking through Python

### Overview
This project explores the use of Exploratory Data Analysis (EDA) in a real-world financial scenario. The objective is to understand how data can assist in managing risk when approving loans, particularly in minimizing financial losses for a bank or financial institution. Participants will apply EDA techniques while learning the fundamentals of risk analytics in the context of banking.

### Project Context
Loan providers often face challenges when deciding whether to extend credit to individuals with limited or no credit history. This can lead to an increased risk of defaults by borrowers who may take advantage of the system. For this project, imagine you are working for a finance company that provides loans to urban clients. You are tasked with applying EDA to identify patterns in the data to ensure that applicants who are capable of repaying their loans are not unfairly rejected.

### Decision Points
When a loan application is received, the company must assess the applicant’s profile to decide whether to approve the loan. The two types of risks involved are:
- **Opportunity Loss**: Denying a loan to a creditworthy applicant results in lost business for the company.
- **Financial Risk**: Approving a loan to an applicant who may default can lead to significant financial losses for the company.

### Data Insights
The dataset contains loan application information and includes two key types of scenarios:
- **Borrowers Facing Payment Issues**: Applicants who have delayed payments beyond a certain threshold on at least one of the initial loan installments.
- **Other Borrowers**: Applicants who have made all payments on time.

### Loan Application Outcomes
Loan applications can result in the following outcomes:
1. **Approved**: The loan is successfully approved.
2. **Cancelled**: The applicant cancels the loan, either due to a change in decision or unfavorable terms.
3. **Rejected**: The loan application is denied by the company, usually because the applicant doesn’t meet certain criteria.
4. **Unused Offer**: The offer is canceled by the applicant at various stages of the process.

### EDA Objective
This project uses EDA to understand how various consumer and loan attributes affect the likelihood of default.

### Dataset Overview
1. **application_data.csv**: Contains detailed client information at the time of loan application, including indications of potential payment issues.
2. **previous_application.csv**: Includes records of prior loan applications and their outcomes (Approved, Cancelled, Refused, Unused Offer).
3. **columns_description.csv**: A data dictionary that explains the meaning of each variable.

### Steps to Follow
1. **Problem Statement & Approach**: Outline the key problem and summarize your approach to analysis. Handle missing data appropriately (removal or imputation), and clearly explain your chosen method.
2. **Outliers**: Identify and discuss potential outliers in the dataset, explaining why these values are considered outliers. No need to remove them for this analysis.
3. **Data Imbalance**: Check for any imbalance in the dataset and calculate its ratio.
   - *Hint: Given the large number of columns, automate your analysis where appropriate to extract insights.*
4. **Analysis**: Perform univariate, segmented univariate, and bivariate analyses. Interpret the results in business terms.
5. **Correlations**: Identify the top 10 correlations for borrowers facing payment difficulties and for other cases (based on the target variable). Segment the data, calculate correlations, and derive insights.
   - **Visualization**: Use visualizations to explain key findings. Choose appropriate graphs to represent numerical and categorical variables. Summarize the most important insights, particularly in differentiating borrowers with payment difficulties from those without.

