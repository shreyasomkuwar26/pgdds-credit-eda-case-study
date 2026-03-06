# Credit Risk Analysis using Exploratory Data Analysis (EDA)

## Project Overview

Financial institutions face a major challenge in deciding whether to
approve or reject loan applications. Approving loans for risky
applicants may lead to financial losses, while rejecting reliable
customers may result in lost business opportunities.

This project performs **Exploratory Data Analysis (EDA)** on loan
application data to identify patterns and risk factors associated with
loan default. The analysis helps understand which customer attributes
and financial indicators contribute to payment difficulties.

------------------------------------------------------------------------

## Business Objective

The main goal is to **identify variables that indicate a higher
probability of loan default**, helping financial institutions make
better lending decisions.

------------------------------------------------------------------------

## Dataset

The analysis uses three datasets:

### 1. Application Data

Contains customer demographic and financial information when applying
for a loan.

Examples: - Income - Employment details - Education - Loan amount -
Credit details

Target variable: - **TARGET = 0** → Loan repaid - **TARGET = 1** →
Payment difficulties / default

### 2. Previous Application Data

Contains historical loan application information for the same customers.

Includes: - Loan approval status - Previous loan amount - Application
outcome (Approved / Refused / Cancelled)

### 3. Column Description

Metadata explaining the meaning of each column in the dataset.

------------------------------------------------------------------------

## Tools and Technologies

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## Analysis Workflow

1.  Data loading and inspection
2.  Handling missing values
3.  Data cleaning and preprocessing
4.  Univariate analysis
5.  Bivariate analysis
6.  Correlation analysis
7.  Identification of key risk indicators

------------------------------------------------------------------------

## Key Insights

Some important factors affecting loan default include:

-   Customers with **lower income levels** show higher default risk.
-   **High loan-to-income ratios** are associated with repayment
    difficulties.
-   Certain **occupations and employment types** show higher default
    rates.
-   Customers with **previous loan refusals** tend to have higher risk
    profiles.
-   Demographic attributes such as **age and education level** influence
    repayment behavior.

------------------------------------------------------------------------

## Business Impact

The insights from this analysis can help financial institutions:

-   Identify **high-risk applicants**
-   Improve **credit approval strategies**
-   Reduce **loan default rates**
-   Optimize **risk-based pricing models**

------------------------------------------------------------------------

## Repository Structure

    Credit-EDA-Case-Study
    │
    ├── Credit EDA Case Study - Notebook.ipynb
    ├── README.md
    └── dataset files

------------------------------------------------------------------------

## Future Improvements

This project can be extended by:

-   Building **machine learning models** to predict loan default
-   Creating **feature engineering pipelines**
-   Applying **classification algorithms** such as Logistic Regression,
    Random Forest, or XGBoost
-   Evaluating model performance using **ROC-AUC, Precision, Recall, and
    F1 Score**
