# Project Title: SaaS Subscription Revenue Analysis

## Table Of Contents

1. Dataset Background & Overview
2. Objectives 
3. Data Structure Overview (ERD)
4. Revenue Analysis
5. Strategic Recommendations
6. Appendix


## 1. Dataset Background and Overview

The data is synthetic, mimicking a real-world B2B SaaS subscription business dataset for the period January 2024 to December 2025. The dataset covers customer segments, subscription information, recurring revenue, subscription changes, plan, churn, payments and account health. It consists of 12 tables. 

The SaaS dataset provides building KPIs aligned with business goals, which increase user retention, optimize service adoption, and prioritize recurring revenue growth and account health. The SaaS dataset offers multiple analyses to support executive, revenue operations, customer success, product, sales, and marketing teams. 

This project aims to translate raw data into actionable insights with recommendations for business success. The dataset is cleaned, validated, and transformed with new features using SQLite in Jupyter Notebook. For data visualizations on Tableau, I used the final cleaned dataset. 

👉 Data source

👉 Doc of the data cleaning & validation log including the definition of KPIs

👉 SQLite queries for data preparation: cleaning & validation 

## 2. Objectives

- Define the right KPIs to track, monitor, and evaluate data
- Measure sustainable MRR and ARR growth
- Identify recurring revenue movement drivers
- Evaluate GRR & NRR performance
- Show revenue growth by customer segment.
- Present cash & invoice amount by segments
- Detect revenue leakage and cash flow risk by company size
- Suggest actionable recommendations to the relevant stakeholders for sustainable business growth.

## 3. Data Structure Overview (ERD)

The entity relationship diagram (ERD) is created in a simplified format with primary keys and foreign keys in one-to-many relationships, which helps preserve each table’s grain and prevents duplicates in MRR.

<img width="454" height="583" alt="v_saas_ERD" src="https://github.com/user-attachments/assets/744c4552-f971-47a0-9e53-916f76c701c3" />


👉 Entity Relationship Diagram (ERD) created on draw.io

## 4. Revenue Analysis on Nov. 2025

👉 Tableau Dashboard: Revenue Analysis
<img width="1040" height="641" alt="saas_revenue" src="https://github.com/user-attachments/assets/99b33cd8-6ad6-4c7c-af3e-1ccdd95dfd4e" />


* Ending MRR reached $2.68M at a steady monthly growth rate of 1.22%, which is supported by $32.3K in Net New MRR. The growth is driven by new acquisitions, so new-logo MRR is the primary growth driver, indicating limited expansion within the existing customer base.
* Revenue leakage totalled $173.3K in churned MRR, representing the largest negative component of the MRR bridge. This signals an opportunity to strengthen retention, renewal management, and proactive customer-success interventions.
* The Enterprise segment is the strongest growth engine and generates the highest Ending MRR, Net New MRR, and MRR growth rate at approximately 5%. This supports prioritizing enterprise acquisition, upsell, cross-sell, and expansion strategies. While the enterprise also records the highest revenue leakage rate at 19%, protecting high-value enterprise ARR through renewal planning, adoption monitoring, and targeted churn-risk mitigation should be a strategic priority.
* The 97.28% cash collection rate shows that invoiced revenue is converting efficiently into cash. It implies the cash conversion is healthy and supports revenue predictability. January’s cash collection spikes more than twice that of typical months, reflecting annual billing cycles and should be considered in cash-flow forecasting.


## 5. Strategic Recommendations

* Customer Success and Revenue Operations teams: To strengthen retention and protect recurring revenue, prioritize high-value accounts with elevated churn risk, particularly in the Enterprise tier. Use health scores, product-adoption signals, and renewal dates to trigger proactive interventions and reduce churned MRR and revenue leakage.
* Sales, Customer Success, and Product teams: To accelerate expansion within the existing customer base, develop targeted upsell and cross-sell programs based on seat utilization, feature adoption, and account growth potential. Also, increasing expansion MRR will reduce reliance on new-customer acquisition and improve sustainable Net New MRR.
* Executives and Finance: To optimize enterprise growth and cash-flow planning, continue investing in the enterprise segment while closely monitoring its 19% revenue leakage rate. Also, align renewal incentives, contract terms, and annual billing strategies with seasonal collection patterns to protect ARR, improve revenue predictability, and maintain a strong cash collection rate.
  

## 6. Appendix

### Caveats And Assumptions
* The dataset is synthetic and does not represent an actual company.
* There are limitations based on the dataset for calculating gross margin and customer-acquisition cost (CAC).
* Revenue recognition may differ from real subscription MRR.
* The Stakeholders referenced in the strategic recommendations are hypothetical and were assigned based on a simulated SaaS company scenario. They do not represent confirmed stakeholders from an actual SaaS company. 


### Tech Stack Used
* **Data Preparation**: SQLite, Python, VS Code
* **BI tool**:  Tableau
* **AI-assisted**: ChatGPT, Gemini






   

