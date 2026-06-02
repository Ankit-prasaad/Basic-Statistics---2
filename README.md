# Basic-Statistics-2
# Hospital Patient Data Analysis

This project focuses on analyzing hospital patient and billing data to extract meaningful insights and perform real-world data preprocessing operations using Python and Pandas.

In a hospital environment, patient records often contain missing values, duplicate entries, and data spread across multiple datasets. This project simulates such a scenario and demonstrates how raw healthcare data can be cleaned, transformed, and analyzed for better decision-making.

# Problem Overview

The hospital maintains two datasets:

Patient information (admission details, department, doctor, etc.)
Billing details (bill amount and financial records)

Challenges include missing bill amounts, duplicate patient entries due to follow-ups, and the need to merge multiple data sources.

# Key Operations Performed
Loaded and explored datasets using info(), head(), and shape
Selected relevant billing-related columns for analysis
Removed unnecessary administrative columns
Handled duplicate patient records using drop_duplicates()
Managed missing values by replacing them with mean bill amount
Performed groupby analysis to calculate total billing per department
Merged patient and billing datasets using PatientID
Concatenated new weekly patient records (row-wise)
Added new billing features like insurance coverage and final amount (column-wise)
# Insights & Learnings
Departments contribute differently to total hospital revenue
Data cleaning significantly improves dataset quality and reliability
Merging and concatenation are powerful tools for combining real-world datasets
Handling missing values is crucial in healthcare data analysis
# Tools Used
Python
Pandas
NumPy
# Outcome

This project demonstrates end-to-end data preprocessing and analysis workflow on a healthcare dataset, showcasing how raw hospital data can be transformed into structured and meaningful insights for decision-making.
