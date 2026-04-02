Siin on andmetarkuse kursuse materjalid

# Sales Report
You can find the Power BI file for sales Report:
https://github.com/riskosepp/andmetarkus2026/blob/main/SalesReport.pbix
Next, anaylisis steps are explained
## Overview of Dataseet



## Data Cleaning

The original table was "

Avastatud andmekvaliteedi probleemid ja parandused

1) CustomerID: C005 peaks olema C004, muudetud alusfailis 31.03.2026 müügiesindaja sisendi põhjal
2) ProductID: P005 ja P006 peaks olema P004, muudetud alusfailis 31.03.2026 müügiesindaja sisendi põhjal
3) Vigane kogus müügireal S00009, oli 300, muudetud 3-ks puhastatud failis 31.03.2026 müügiesindaja sisendi põhjal
4) Vigane kogus müügireal S00010, oli 2000, muudetud 20-ks puhastatud failis 31.03.2026 müügiesindaja sisendi põhjal

## Analysis

**Recommendations**

# Employee Report

## Problem Statement
HR department wants an overview of active and left employee over time and results of the satisfaction survey.

## Plan
I wull create a Power BI report to give this overview.

## Data
Hr department gave me two files:
- "Employee_Satisfaction_Survey.xlsx"
- "HR_Dataset.CSV"

### Data Cleaning
I checked data for uniqueness, formats and outliers.
Survey dataset didn`t have a unique key column. I creater a new column "AnswerKey" which combined "Question Round" and "Answer ID"
In HR dataset, I removed columns with personal data: "First Name", " Last Name" and "Email". Also removed the column "Employment Status" as the data in that column was not up to date according to the HR department.
Column "Salary" was changed to Decimal Number format
