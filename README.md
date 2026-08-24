## Hi there 👋


I'm a Data Science student at BPP (54SADJCQB) with an interest in applying data skills to real-world and public datasets.

So far, my work has focused on developing practical skills in data engineering, analytics, and visualisation through academic projects and hands-on experience with industry-style data.



### Modules completed 🌱
- Data Infrastructure & Tools
- Data Engineering
- Data Visualisation
- Data Analytics

### Tools & Technologies 😄
- SQL, Python, DAX
- Power BI, Snowflake, Excel
- JIRA, Confluence, GitHub

### Current focus 💬
- Classification on an industry-style dataset (Private Dataset) - this cannot be shared due to containing sensitive Data
- Logistic Regression modelling on a housing dataset  (Public Dataset)

Check out my projects, details of it are below✨
---
[Click Here to view my Logistic Regression Model - Data Science Project](https://github.com/54SADJCQB-BPPProfessionalPractice/Data-Science-Portfolio/blob/main/Data%20Science%20Project%20(PUBLIC%20DATASET).ipynb)

[Click here to view my Time Series Analysis - Impact Project](https://github.com/54SADJCQB-BPPProfessionalPractice/Data-Science-Portfolio/blob/main/Time%20Series%20Analysis.ipynb)


# Data-Science-Portfolio
**Project Overview**
This README portfolio showcases a hypothesis-driven data science project investigating the factors that influence house sale likelihood. Using a Kaggle housing dataset and Logistic Regression, the project demonstrates end-to-end data science skills.
 Skills Demonstrated: 
 - Data cleaning and Preperation
 - Exploratory Data Anlysis
 - Statistical modelling
 - Predictive analysis
 - Model evaluation
 - Sensitivity analysis
---
Project Context
---
**Business Problem:**
Property sellers, analysts and property platforms often make decisions based on assumptions about what drives a successful sale. However, it is not always clear which property characteristics have the greatest influence on whether a property will sell. This project investigates which structural and location-related features are most strongly associated with house sale likelihood. Using Logistic Regression, the analysis tests whether property size and neighbourhood quality have greater influence on sale outcomes than room-count measures, providing a more evidence-based understanding of housing market behaviour. 

---
**Research Question:**
The objective was to assess whether size and location-related property characteristics have greater influence on sale likelihood than room-count measures through the hypothesis:

H1: Size and location-related variables, particularly Square_Footage and Neighborhood_Quality, will have a greater influence on the likelihood of a house being sold than room-count measures such as Num_Bedrooms.

H0: Size and location-related variables, particularly Square_Footage and Neighborhood_Quality, will not have a greater influence on the likelihood of a house being sold than room-count measures such as Num_Bedrooms.

---
**Dataset Source:**
The dataset used in this project is the House Sales Dataset sourced from Kaggle. Each row represents an individual property and contains structural and location-related characteristics that may influence sale likelihood.

---
**Target Variable**
Will_Sell_Proxy:
 1 = Sold
 0 = Not Sold

**Key Results**
Test Accuracy: 91%
F1-Score: 91%
ROC-AUC 1.00


---
**Conclusion:** H1 was partially supported. Square footage ad a substantially greater predictive influence than bedroom count, supporting the size element of the hypothesis. Neighbourhood quality however contributed little power, so the location-quality element was not supported


# Impact Evaluation
**Project Overview**

Insurance claim volumes fluctuate throughout the year, creating challenges for workforce and resource planning. This project investigated whether historical claims data could identify seasonal trends and accurately forecast future demand to support operational decision-making.


---
Project Context
---
**Business Problem:**
It is nearly impossible to successfully predict workforce to meet claim volumes demand, which means the company are majorly understaffed and struggling whnebusy and when overstaffed it is financially inefficient for the company

---
**Research Question:**
H₀: Historical claims data does not contain significant seasonal patterns and cannot reliably forecast future demand.
H₁: Historical claims data contains significant seasonal patterns and can be used to forecast future demand.

---
**Dataset Source:**

A public Kaggle insurance claims dataset containing 90,001 records (2021–2026) was used due to the confidentiality of Beazley claims data. The dataset was cleaned, duplicates removed, and claim dates aggregated into monthly claim volumes for analysis.

---
**Target Variable**
Monthly insurance claims demand, measured through aggregated monthly claim volumes to identify seasonal patterns and generate forecasts. 

**Key Results**
Claims consistently peaked in Q1 and Q4 (December) and were lowest between April and June. 
ACF/PACF analysis identified significant 12 and 24-month lags, confirming annual seasonality. 
The null hypothesis was rejected, demonstrating that historical claims data can support forecasting.
SARIMA outperformed ARIMA, reducing forecast error by approximately 40% (MAPE reduced from 11.0% to 6.6%).

---
**Conclusion:** 
The project demonstrated that insurance claim demand follows predictable seasonal patterns and can be forecast effectively using time series modelling. SARIMA provided the most accurate forecasts, enabling more proactive workforce planning and supporting an estimated £15,200 annual efficiency saving if implemented in an operational environment

<!--
**54SADJCQB-BPPProfessionalPractice/54SADJCQB-BPPProfessionalPractice** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.


-->
