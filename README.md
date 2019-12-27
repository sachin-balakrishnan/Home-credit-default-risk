# Home-credit-default-risk
Binary classification to identify potential loan defaulters in Home Credit's customer base. 

The dataset used in this analysis is - https://www.kaggle.com/c/home-credit-default-risk/data. The EDA for base table, EDA for secondary tables, imputation for base table and model files uploaded in the repository.

## Problem statement and our motivation to take up this challenge
Home credit is an international non-bank financial institution, which focuses on lending to people with little or no credit history. In the US, the unbanked/underbanked population comes up to 22% households. This population is often exploited and taken advantage of by untrustworthy lenders. This project aims to aid Home Credit to predict the repayment capabilities of underbanked customers in the US, thereby provide a positive loan experience for the lender as well as the loanee.

## Approach
The data is spread across seven tables, each representing a factor which Home Credit make use of in understanding the customer behavior. The biggest challenge was to merge these tables and filter out relevant features. As the first step, we conducted exploratory data analysis to get a high-level overview of the features. 
Moving from there, we had to perform feature engineering to filter out the redundant/insignificant predictors and create new ones to tailor to our needs. We used LightGBM to model the target variable and used Area Under the ROC curve as the evaluation metrics. The complete code and model comparison are available in the repo. 
 
