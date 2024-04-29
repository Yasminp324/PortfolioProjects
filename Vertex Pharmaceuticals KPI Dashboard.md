# Vertex KPI Dashboard

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
- [References](#references)


### Project Overview

This financial analysis aims to provide insights into the performance of a pharmaceutical company over the years between 2017-present. 
By analyzing various key metrics of the company's three financial statements, we seek to identify trends, opportunities, and challenges, 
ultimately making data-driven recommendations. Our goal is to gain a deeper understanding of the company's performance and inform strategic
decision-making.


### Data Sources 

Financial Data: The data used for this analysis is from sec.gov using 10-K reports from the years 2016-2023, which contain detailed financial information.


### Tools

  - Excel: Data Cleaning, Analysis, and Dashboard Creation
    2017[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-17-000017&xbrl_type=v)
    2018[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-18-000009&xbrl_type=v)
    2019[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-19-000006&xbrl_type=v)
    2020[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-20-000007&xbrl_type=v)
    2021[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-21-000006&xbrl_type=v)
    2022[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-22-000007&xbrl_type=v)
    2023[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-23-000007&xbrl_type=v)
    2024[Download here](https://www.sec.gov/cgi-bin/viewer?action=view&cik=875320&accession_number=0000875320-24-000062&xbrl_type=v)



### Data Cleaning/Preparation

In the data preparation phase, I performed the following tasks:

1. Data loading and inspections
2. Handling missing values
3. Data cleaning and error correction
4. Data organization and restructuring



### Exploratory Financial Analysis

EFA involved exploring the sales data to answer key questions, such as:

- What is the trend of revenue over time?
- What is the trend of gross profit margin over the past seven years?
- What is the correlation between research and development expenses and pharmaceutical performance?
- What is the correlation between revenue and research and development expenses?




#### Data Analysis 

- Index Match: Index match was employed extensively to retrieve specific data points from large datasets efficiently. This combination of functions enabled precise lookup and retrieval of information
  based on specified criteria, enhancing data accuracy and facilitating dynamic data analysis and visualization in the Excel dashboard.

      EX:  INDEX(Staging!D4:J88,MATCH(Dashboard!K15,Staging!C4:C88,0),MATCH(Dashboard!Z16,Staging!D3:J3,0))


- Data Validation: Data validation was implemented to create a user-friendly drop-down menu allowing the selection of different years. By choosing a specific year from the drop-down list, users can interact
  with the dashboard dynamically, enabling the display of corresponding data and metrics for the selected year. This feature enhances usability and facilitates focused analysis of financial trends and
  performance over different periods.


- Conditional Formatting: I used conditional formatting to visually represent changes in metrics: pink for decreases and green for increases, enhancing data interpretation and highlighting trends effectively. 



### Results/Findings


The financial dashboard's results are summarized as follows:
1. The company's revenue has been steadily increasing over the past 7 years, with a particular peak in 2020.
2. Gross profit has been steady for the past 7 years.
3. The correlation between Research&Development and pharmaceutical performance was unclear.
4. The correlation between revenue and research&development is strong.

### Recommendations

Based on the analysis, I recommend the following actions:
1. Considering the significant contribution of research and development (R&D) expenses to revenue generation, continued investment in innovation and product development is recommended. This will help maintain competitiveness,
   drive future growth, and capitalize on emerging market trends or customer preferences.

2. Improving the Asset Turnover Ratio indicates efficient utilization of assets to generate revenue. Optimizing asset management practices, such as asset maintenance, utilization tracking, and asset lifecycle management,
   can enhance operational efficiency and profitability.

3. Increasing Earnings Before Interest and Taxes (EBIT) while controlling expenses can boost profitability and ROA. Implementing strategies to enhance operational performance, optimize pricing, and manage costs effectively
   can drive sustainable profitability and maximize returns on assets.


### Limitations
1. Data Integrity and Completeness: I want to highlight that the analysis presented here relies on available financial data, which may have limitations due to missing or incomplete information in the financial statements.

2. Educated Assumptions and Estimates: In cases where specific financial figures were unavailable, I made informed estimates based on industry benchmarks and historical trends to ensure a comprehensive analysis.

3. Potential Margin of Error: While I took every precaution to ensure accuracy, I acknowledge the possibility of human error in data entry and calculations, which may have led to slight discrepancies in the reported figures.

4. Sensitivity Analysis: I recommend conducting a sensitivity analysis to assess the robustness of the findings and the potential impact of variations in key assumptions or input parameters, thereby addressing uncertainties associated
   with data limitations.

6. Recommendations for Future Analysis: In future analyses, I suggest advocating for improved data quality and transparency while exploring alternative data sources to enhance the accuracy and reliability of the analysis.


### References 
1. [Vertex Pharmaceuticals] (https://www.vrtx.com)
2. [WSJ | Markets] (https://www.wsj.com/market-data/quotes/VRTX/financials/annual/income-statement)
3. [Securities and Exchange Commission] (https://www.sec.gov)
4. [YouTube]: The Financial Controller - Controller Dashboard: One KPI Dashboard To Run A Business Part 1(https://www.youtube.com/watch?v=8h0w6J-eLYc)
5. [YouTube]: The Financial Controller - From Financial Statements to KPI Dashboard [Part 2 to Controller KPI Dashboard] (https://www.youtube.com/watch?v=M_TNiR3QyIk) 
 







