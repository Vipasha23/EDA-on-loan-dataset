# Exploratory Data Analysis on Loan Dataset

## Overview
In this project, I performed an exploratory data analysis (EDA) on a loan dataset to uncover insights into borrower characteristics, loan terms, and compliance with credit policies. The analysis was carried out using Python libraries including Pandas, Matplotlib, and Seaborn.

## Dataset
The dataset includes the following features:
- `int.rate`: Interest rate on the loan
- `installment`: Monthly installment amount
- `log.annual.inc`: Log-transformed annual income of the borrower
- `dti`: Debt-to-income ratio
- `fico`: FICO credit score
- `days.with.cr.line`: Days of credit history
- `revol.bal`: Revolving balance
- `revol.util`: Revolving credit utilization ratio
- `credit.policy`: Credit policy compliance (1 = meets policy, 0 = does not meet)
- `purpose`: Purpose of the loan
- `delinq.2yrs`: Number of times the borrower was delinquent in the past 2 years
- `pub.rec`: Number of derogatory public records

## Analysis Details

### 1. Descriptive Statistics
I calculated the mean, median, and standard deviation for key numeric features:
- `int.rate`
- `installment`
- `log.annual.inc`
- `dti`
- `fico`
- `days.with.cr.line`
- `revol.bal`
- `revol.util`

### 2. Distribution Analysis
I analyzed the distribution of FICO scores among borrowers to understand the creditworthiness of the majority. This distribution provides insights into the typical credit profiles within the dataset.

### 3. Correlation Analysis
I examined the relationships between `int.rate` and other variables to identify which features are strongly correlated. This helps in understanding how various factors influence the interest rates on loans.

### 4. Credit Policy Compliance
I compared the characteristics of borrowers who meet the credit policy (`credit.policy == 1`) with those who do not. This comparison highlights key differences and compliance issues.

### 5. Purpose of Loans
I identified the most common loan purposes and analyzed how loan characteristics vary with different purposes. This helps in understanding borrowing trends and preferences.

### 6. Interest Rate Variations
I explored how interest rates vary across different loan purposes and FICO scores. This analysis provides insights into how interest rates are influenced by these factors.

### 7. Income Analysis
I investigated the relationship between borrowers' income (`log.annual.inc`) and their loan characteristics, including amount, purpose, and interest rate. This analysis reveals how income impacts borrowing behavior.

### 8. Debt-to-Income Ratio
I analyzed the debt-to-income ratio (`dti`) across different loan purposes to derive insights into how this ratio affects loan characteristics.

### 9. Delinquency Patterns
I explored patterns of delinquency (`delinq.2yrs`) across different FICO score ranges to understand how credit scores relate to borrowing issues.

### 10. Public Records Analysis
I assessed the impact of derogatory public records (`pub.rec`) on loan characteristics such as interest rates and loan amounts. This helps in understanding how public records affect loan terms.
