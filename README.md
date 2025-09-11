# Luxury Housing Sales Analysis – Bengaluru

**Sales Analysis Dashboard for Luxury Housing in Bengaluru**

---

## Problem Statement
Build a complete real estate analytics solution using Python for advanced data cleaning, load the refined dataset into a SQL database, and use Power BI to directly connect to SQL and build a dashboard. The goal is to replicate a real-world enterprise-level data pipeline and analysis environment using a complex housing dataset with 1,00,000+ records.

---

## Overview

Raw datasets often contain missing values, duplicates, inconsistent formatting, and outliers.  
This project demonstrates systematic **data cleaning and preprocessing** techniques to transform messy data into a reliable and structured format ready for analysis through Power BI.

---

## Objectives
- Handle **missing values** (imputation with mean/median/mode, group-based filling).
- Remove **duplicates** and irrelevant data.
- Standardize **date and numeric formats**.
- Correct **inconsistent text entries** (case formatting, stripping whitespace, removing special characters).
- Detect and handle **outliers**.
- Ensure the dataset is ready for **exploratory data analysis (EDA)** or **machine learning pipelines**.

---

## Contents
| File | Description |
|------|-------------|
| `Luxury_Housing_Bangalore.csv` | Raw dataset containing housing sales records |
| `Luxury Housing Sales Analysis.ipynb` | Jupyter Notebook with data cleaning, EDA, visualization, and interpretation |
| `Luxury_House_Analysis.pbix` | Power BI dashboard for interactive insights and storytelling |

---

## Libraries/Modules needed for the project!
  - Pandas
  - numpy
  - matplotlib
  - seaborn
  - psycopg2

---

## Data Cleaning Steps
1. **Data Inspection**
   - Shape of the dataset, column data types, missing values summary
2. **Handling Missing Data**
   - Drop or impute missing values
   - Group-based mean/median filling
3. **Removing Duplicates**
   - Identify and drop duplicate rows
4. **Standardization**
   - Convert date columns to standard format
   - Ensure numeric columns are in proper data type
   - Normalize categorical text (case, spacing, spelling corrections)
5. **Outlier Detection**
   - Using IQR or z-score
   - Decide whether to cap, transform, or remove
6. **Export**
   - Save cleaned dataset for downstream use
     
---
## Import Cleaned data to SQL For future analysis
1. **Schema**
    - Create appropriate Schema for the dataframe to store the cleaned data 
2. **Insert**
    -  Insert the data to the created table
3. **Validate**
    - Execute basic queries and check the data
    
---

## Power BI Analysis
  Load the data and create chars,Map,KPI as per the data available for analysis and insights.
  
  <img width="1327" height="746" alt="Market Dashboard" src="https://github.com/user-attachments/assets/14f30594-849d-4343-abe5-9556fb9e9b45" />

  <img width="1320" height="737" alt="Buyer_trend" src="https://github.com/user-attachments/assets/2bcafdfe-e884-4983-8833-051ccadc4ce9" />

  <img width="1312" height="737" alt="Buyer Feedback on Sales channel" src="https://github.com/user-attachments/assets/c080b0bb-f7c2-4e92-80f9-6f2ecfaeacf7" />



---
# Luxury-Housing-Sales-Analysis-Bengaluru
Sales Analysis Dashboard for a Luxurious House - Bangaluru
