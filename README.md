# Global Banking Risk and Compliance Analysis
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
  
## Key Findings

- **Debt burden was strongly associated with customer risk.**
High risk customers had an average debt ratio of 45.64% compared to the 22.40% for low-risk customers.

- **Credit score analysis with risk**
166 customers with exceptional credit scores were concentrated in the low risk category. 

- **Pending KYC customers represented a potential compliance concern.**
All 253 customers with Pending KYC status were classified as either High Risk (127) or Medium Risk (126), with no Low-Risk customers in this group.

- **Account holders that carried most debt**
Business and Premium account holders had the highest average debt, at approximately $99.2K and $94.7K respectively.

- **Debt Ratio vs Risk:**
High-risk customers had the highest average debt ratio (45.64%), compared with 29.72% for Medium-risk and 22.40% for Low-risk customers. This shows a clear relationship between higher debt burden and higher assigned risk.

- **KYC and Age Profile**
Pending KYC cases were concentrated among relatively younger customers. High-risk customers with pending KYC had an average age of 40.03 years.

- **KYC and Risk Profile**
Pending KYC cases were concentrated entirely among higher-risk customers and were overwhelmingly associated with the low-income segment.

- **KYC and Geographic Profile**
Pending KYC cases among higher-risk customers were geographically concentrated in a small number of countries rather than being evenly distributed. Japan had the largest concentration indicating a geographic hotspot for compliance review.

- **Income-Based Financial Profile**
High-income customers held the highest average account balance ($231.7K) but also carried the highest average debt ($101.8K). Low-income customers had substantially lower average balances ($14.4K) and debt ($10.4K). Despite these large financial differences, average credit scores remained similar across income groups, ranging from approximately 683 to 735. This is consistent with the fact that credit scoring does not factor in net worth or salary allowing low income individuals to achieve higher credit scores.

## Recommendations
- Prioritise pending KYC cases among high and medium-risk customers for compliance review.
- Investigate the geographic concentration of pending KYC cases, particularly identified to be in Japan.
- Investigate customer groups showing higher debt ratios, as debt burden increases substantially across higher-risk categories.
- Consider multiple financial indicators when assessing customers, since credit score alone did not consistently correspond with overall risk classification.
- Monitor account types and income brackets that are associated with higher debt. 
  
## Conclusion
This project analysed banking data to identify patterns in risk, debt, KYC compliance, income and financial behaviour. The analysis highlighted several areas of potential business and compliance concern, particularly the relationship between debt, risk and the concentration of unresolved KYC cases within specific customer geography and segments. 

