# Task_01_DataAnalytic
# telco Customer Churn – Data Cleaning & Preprocessing  

## Project Overview  
This project focuses on **cleaning and preprocessing customer churn data**.  
The dataset (synthetic/fake but realistic) represents telecom customer information including demographics, services, billing, and churn reasons.  

The main goal:  
- Prepare the raw dataset (with nulls, duplicates, inconsistent formats).  
- Transform it into a clean, structured format ready for EDA and machine learning.  
## Steps Performed  

### Data Cleaning  
- Handled missing values (`Total Charges` → filled with median).  
- Removed duplicate `Customer_ID` entries.  
- Standardized text values (`Male`, `male`, `FEMALE` → `Male/Female`).     

### Data Preprocessing  
- Encoded categorical variables (`Gender`, `Contract`, `Payment Method`).  
- Scaled numerical columns (`monthly_charges`, `total_charges`, `cltv`).  
- Created new features: `tenure_years`, `revenue_contribution`.  
- Prepared `Churn Label` as binary target (0 = No, 1 = Yes).  
- Train-test split for churn prediction models.  

##  Deliverables  
- ✅ Cleaned dataset ready for analysis  
- ✅ Summary of changes (data quality report)  
- ✅ Preprocessed dataset ready for ML models  

## Next Steps  
- Exploratory Data Analysis (EDA) → churn patterns  
- Churn prediction model (Logistic Regression, Random Forest, XGBoost)  

