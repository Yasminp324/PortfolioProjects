# Healthcare Payment Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning-/-preparation)
- [Exploratory Financial Analysis](#exploratory-financial-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results-/-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)



### Project Overview

Overview:
This project aims to analyze payment trends and variations within the healthcare industry, focusing on reimbursement patterns for medical procedures across different regions and providers. Using a dataset containing information on DRG codes, descriptions, provider details, and payment metrics such as average total payments and Medicare reimbursements, the analysis seeks to uncover insights into:

1. Procedure Costs: Identifying the most and least expensive medical procedures based on average total payments.
2. Regional Disparities: Examining how payment amounts vary across different hospital referral regions and states.
3. Medicare Reimbursement Landscape: Analyzing the proportion of Medicare payments relative to total payments for various DRGs and descriptions.

By conducting this analysis, the project aims to provide valuable insights for healthcare providers, policymakers, and financial analysts to optimize resource allocation, understand reimbursement dynamics, and improve financial planning within the healthcare sector.

### Data Sources 

Healthcare Data: Includes information for the 100 most common inpatient services and 30 common outpatient services.
-  [data.world] (https://data.world/data-society/hospital-charge-data)

### Tools

  - Excel: Data Cleaning
  - SQL: Data Analysis
    


### Data Cleaning/Preparation

In the data preparation phase, I performed the following tasks:

1. Identified missing values by counting blank cells using =COUNTBLANK(range).
2. Adjusted data types for consistency.
3. Removed duplicate entries to ensure data integrity.
4. Utilized Excel functions such as =MID(), =FIND(), =LEN(), and =LEFT() to extract specific portions of cells for standardization.
5. Adding/Updating database



### Exploratory Financial Analysis

EFA involved exploring the sales data to answer key questions, such as:

- Which medical procedures have the highest average total payments?
- How do average total payments vary across different hospital referral regions?
- What is the proportion of Medicare payments relative to total payments for various medical procedures?




#### Data Analysis 

``` sql


```


### Results/Findings


The financial dashboard's results are summarized as follows:
1.Cost Efficiency Strategies: Identify opportunities to streamline resource-intensive procedures and treatments, such as implementing standardized protocols or leveraging technology to reduce costs while maintaining quality of care.

2. Regional Cost Analysis: Conduct a detailed examination of cost disparities across hospital referral regions to understand underlying factors contributing to variations in healthcare expenditure. This analysis can inform targeted interventions to address cost inefficiencies and improve affordability for patients.

3. Medicare Reimbursement Optimization: Explore strategies to maximize Medicare reimbursement rates by ensuring compliance with billing regulations, negotiating favorable reimbursement agreements, and optimizing coding practices to accurately reflect the complexity of services provided..

### Recommendations

Based on the analysis, I recommend the following actions:

1. Cost Efficiency Strategies: Identify opportunities to streamline resource-intensive procedures and treatments, such as implementing standardized protocols or leveraging technology to reduce costs while maintaining quality of care.

2. Regional Cost Analysis: Conduct a detailed examination of cost disparities across hospital referral regions to understand underlying factors contributing to variations in healthcare expenditure. This analysis can inform targeted interventions to address cost inefficiencies and improve affordability for patients.

3. Medicare Reimbursement Optimization: Explore strategies to maximize Medicare reimbursement rates by ensuring compliance with billing regulations, negotiating favorable reimbursement agreements, and optimizing coding practices to accurately reflect the complexity of services provided..



### Limitations
- Data Completeness and Granularity: One significant limitation is the completeness and granularity of the data available. While the dataset provides insights into average total payments and Medicare reimbursement percentages for various procedures across different regions, it may lack detailed information on specific cost drivers, patient demographics, or clinical outcomes. Without granular data, it can be challenging to perform deeper analyses or identify nuanced patterns that could inform more targeted financial strategies.

- SQLITE Database Constraints: Working with SQLITE as the database management system imposes limitations on the complexity of analyses that can be performed. SQLITE is designed for lightweight, single-user applications, and may not support advanced analytics techniques or handle large datasets efficiently. As a result, the scope and depth of the financial analysis may be constrained by the capabilities of the database platform.


