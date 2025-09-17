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

## 🔑 Key Insights  


### 1. Builder Performance  
- **Top Performers (≈117K):** Prestige, L&T Realty, Total Environment.  
- **Strong Competitors (≈115–116K):** Sobha, RMZ, Puravankara, SNN Raj, Brigade.  
- **Observation:** Builder competition is **very tight**, with marginal differences in performance.

### 2. Market Trends & Booking Conversion  
- Inner-city premium micro-markets (Koramangala, Indiranagar, Jayanagar) show **higher booking conversion (~51–52%)**.  
- Peripheral markets (Domlur, Bellary Road) show **lower conversion (~47–48%)**.  
- Indicates **location-driven buyer confidence** in prime areas.  

### 3. Configuration Demand  
- Demand is **evenly split**:  
  - 3BHK: 33.38%  
  - 4BHK: 33.54%  
  - 5BHK+: 33.09%  
- Developers should maintain **diverse inventory** to meet balanced demand.  

### 4. Buyer Segments & Possession Status  
- Buyer types (CXO, HNI, NRI, Startup Founders, Others) are **evenly distributed** across all possession stages.  
- **No strong bias** towards Launch, Ready-to-Move, or Under-Construction projects.  

### 5. Sales Channel Efficiency  
- All four channels (Broker, Direct, NRI Desk, Online) perform **almost equally (~25K each)**.  
- No single channel dominates → A balanced multi-channel strategy works best.  

### 6. Buyer Feedback – Across Sales Channels  
- **Positive Drivers:** Excellent location, amenities, and great views are consistent pull factors.  
- **Pain Points:** Agent responsiveness, connectivity, and office distance remain common concerns.  
- **Observation:** “No Comments” dominates feedback, suggesting limited customer engagement post-visit.  

---

## 📊 Dashboards & Visuals  
1. **Feedback Analysis:** Buyer sentiments across channels and possession stages.  
2. **Sales Efficiency:** NRI vs Non-NRI performance across channels.  
3. **Configuration Mix:** Demand split for 3BHK/4BHK/5BHK+.  
4. **Market Trends:** Quarterly performance by micro-market.  
5. **Builder Performance:** Quarterly contribution and sales ranking.  

---

## 🚀 Conclusion  
- Buyers value **location, amenities, and views** most when purchasing luxury homes.  
- Sales channels are equally efficient, so balanced investment across all is optimal.  
- Demand is **spread across multiple configurations** → developers must diversify offerings.  
- Premium zones like Koramangala & Indiranagar achieve **faster sales conversions**.  
- Competition among top builders is **very close**, highlighting the need for differentiation through customer service and amenities.  

---

## 📌 How to Use  
1. Download and install **Power BI Desktop**.  
2. Clone this repository or download the `.pbix` file.  
3. Open the file in Power BI Desktop.  
4. Explore interactive dashboards (filters, slicers, micro-market comparisons).  

---
