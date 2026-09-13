# Global-Banking-Customer-Risk-Analysis
## Overview
This project analyses a synthetic global banking dataset in Microsoft Excel to explore customer financial health, credit quality, KYC status and risk. Financial leverage, demographics and compliance were mainly assessed in the context of 

## Objective 
The objective of this project is to analyze customer financial behaviour to evaluate credit risk and customer segmentation. By examining the relationship between income, debt ratios, credit scores, compliance (KYC) statuses, this analysis provides insights for risk mitigation, financial product marketing, and regulatory compliance. 
## Dataset 
This project uses Global Banking Customer Analytics Dataset, a synthetic portfolio sourced from Kaggle. There are 1600 records from multiple regions and includes information related to:
### Dataset Structure
The dataset contains 1,600 customer profiles with 16 attributes categorized into:
* **Demographics:** Age, Gender, Country, City
* **Account Info:** Account Type, Status, KYC Status, Creation/Active Dates
* **Financials:** Balance, Debt, Annual Income, Credit Score
* **Risk Metrics:** Risk Category, Fraud Flag
'Username' was primarily used as a unique customer-count field in pivot tables.
## Data Preparation
The raw data was imported using **Power Query** with UTF-8 encoding. The dataset was audited and cleaned for missing values, duplicate records, structural inconsistencies, and incorrect data types. Once cleaned, the following analytical fields were engineered to enable deeper customer segmentation:

* **Debt Ratio:** Measures a customer's total financial leverage relative to their income.
* **Credit Score Band:** Categorised credit scores into tiers (e.g., Poor, Fair, Good, Excellent) for easier grouping.
* **Income Category:** Income data was distinctly grouped (e.g., Low, Medium, High Earners).
* **Days Inactive:** Computed to track engagement levels and identify dormant accounts.
  
## Exploratory Data Analysis




## Key Analysis and Findings 
During the analysis, medium risk customers represented the largest group. Business Accounts held the highest debt ratio average. 
wealth accumulation pattern. which age customer become most valuable to bank. Crossed KYC with risk category and found high risk customers who have pending verification. credit score band of exceptional belong to low risk category. Are those low risk categories are all verified. 
who are the high risk category who are pending? Average age of pending KYC is found. 
  
