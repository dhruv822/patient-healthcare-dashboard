# Patient Healthcare Dashboard
## Project Overview
The Patient Healthcare Dashboard is a data visualization tool designed to provide insights into various aspects of patient care and hospital performance. It uses Power BI to visualize data on patient demographics, medical conditions, hospital admissions, billing amounts, insurance providers, and other relevant metrics. The goal of this dashboard is to assist healthcare providers, administrators, and researchers in understanding patient trends, optimizing hospital operations, and improving patient care.

## Data Sources
The project uses anonymized healthcare data provided in two formats: .csv and .xlsx. Both files contain information about patients admitted to different hospitals, including their demographics, medical conditions, admission types, billing amounts, and insurance details.

## Key Columns in the Dataset:
**1. Name**: Patient's anonymized name <br />
**2. Age**: Age of the patient <br />
**3. Gender**: Gender of the patient <br />
**4. Blood Type**: Patient’s blood type <br />
**5. Medical Condition**: Primary diagnosis or medical condition (e.g., Cancer, Diabetes) <br />
**6. Date of Admission**: Date when the patient was admitted <br />
**7. Doctor**: The doctor assigned to the patient <br />
**8. Hospital**: Name of the hospital where the patient was admitted <br />
**9. Insurance Provider**: The insurance provider covering the patient's medical expenses <br />
**10. Billing Amount**: Total amount billed for the patient’s care <br />
**11. Room Number**: Assigned room number in the hospital <br />
**12. Admission Type**: Type of admission (e.g., Elective, Urgent, Emergency) <br />
**13. Discharge Date**: Date when the patient was discharged <br />
**14. Medication**: Medication prescribed during the hospital stay <br />
**15. Test Results**: Results of any diagnostic tests performed (e.g., Normal, Abnormal, Inconclusive) <br />
## Dashboard Features
The dashboard includes the following visualizations and insights:

### 1. Medical Condition Statistics:

Count of medications and admissions by medical condition to understand the most common diagnoses.
### 2. Admission Type Distribution:

Breakdown of admission types (Elective, Urgent, Emergency) to analyze patient admission trends.
### 3. Hospital Analysis:

Average billing amounts and count of admissions by hospital to highlight performance and cost metrics across different facilities.
### 4. Insurance Billing:

Median billing amount by insurance provider, helping to assess the financial relationships with various insurers.
### 5. Patient Demographics:

Average age and other demographic metrics by medical condition for insights into patient populations.
### 6. Length of Stay Trends:

Average length of stay by year, revealing trends in patient stay duration over time.
## How to Use the Dashboard
### 1. Filters:

Users can filter data by medical condition, hospital, insurance provider, and other fields to narrow down the insights based on specific criteria.
### 2. Visual Interactivity:

Click on different components to view details in context and see how metrics change based on selections.
### 3. Insight Interpretation:

Use the visual trends and distribution charts to understand key metrics like admission trends, billing averages, and patient demographics.
## Files in This Repository
**README.md**: Overview and instructions for the project. <br />
**data/healthcare_dataset.csv**: Raw data in CSV format. <br />
**data/cleaned_healthcare_dataset.xlsx**: Cleaned data in Excel format for use in the dashboard. <br />
**dashboard/patient_healthcare_dashboard.pbix**: Power BI file containing the dashboard. <br />

## Requirements
To view or modify the dashboard, you will need:

**Power BI Desktop** (for .pbix file) <br />
**Python** (optional, for running data cleaning scripts) <br />
