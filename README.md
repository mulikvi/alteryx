# Geospatial Healthcare Analysis

## Overview
This project leverages an Alteryx workflow to analyze geospatial healthcare accessibility and demographic trends, with a focus on California and the United States. The workflow integrates healthcare, demographic, and COVID-19 datasets, processes the data, and delivers actionable insights through reporting and visualization.

---

## Workflow Components

### 1. Input Data Sources
- **Hospital_General_Information.csv**  
  Contains hospital details such as location, type, and ratings.  
- **USWagesByZip.csv**  
  Includes demographics and wage data by ZIP code.  
- **time_series_covid19_confirmed_US.csv**  
  COVID-19 case data for U.S. states and counties.  

### 2. Data Preparation
- **Filter Tool**  
  Filters data for specific states (e.g., California) or country-level COVID-19 data (e.g., United States).  
- **Summarize Tool**  
  Aggregates data to calculate totals and averages for metrics such as hospital capacity, wages, and COVID-19 cases.  

### 3. Data Transformation
- **Join Tool**  
  Combines datasets using geographic identifiers (e.g., state, county).  
- **Formula Tool**  
  Adds calculated fields or cleans data for final reporting.  

### 4. Data Output
- **Excel File**: Outputs data to `Demo.xlsx` for further analysis and presentation.  
- **Query Connection**: Provides dynamic data for visualizations and dashboards.  

---

## Key Features
- Focus on California-specific healthcare metrics.  
- County-level breakdown of healthcare, demographics, and COVID-19 data.  
- Integration of COVID-19 trends for enhanced geospatial insights.  

---

## Final Output
The workflow generates:  
- Interactive dashboards for healthcare accessibility.  
- Automated reports for stakeholders.  
- Key performance indicators (KPIs) to identify underserved areas.  

---

## Screenshot of Workflow

<img width="802" alt="alteryx" src="https://github.com/user-attachments/assets/9222718c-ff02-4ca2-a1d8-f0b21651c5ee" />

---

## How to Use
1. Clone this repository.  
2. Open the `.yxmd` workflow file in Alteryx.  
3. Update the file paths to your local dataset locations.  
4. Run the workflow to generate the output files.  




