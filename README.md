# Initial and Exploratory Data Analysis of the SUPPORT2 Dataset

## Project Description
This project involves performing an extensive initial data analysis (IDA) and exploratory data analysis (EDA) on the "SUPPORT2" dataset from the UC Irvine Machine Learning Repository. The dataset, developed to predict 180-day survival in seriously ill hospitalized adults, was funded by the Robert Wood Johnson Foundation and includes sensitive information such as race and gender. It was collected in two phases (1989-1991 and 1992-1994) with the aim of improving end-of-life decision-making and care.

## Key Components:
- Dataset Overview: Detailed examination of the dataset's size, structure, and general information.
- Descriptive Statistics: Calculation of summary statistics including mean, median, standard deviation, etc.
- Data Quality Assessment: Identification and handling of outliers, missing values, and duplications.
- Visualisation: Creation of basic plots to visualize continuous and categorical features.
- Trends and Correlations: Analysis of trends, correlations, and associations within the data.
- Findings and Recommendations: Summary of key findings, conclusions, and recommendations based on the analysis.

## Summary of Findings:
- Outliers: Indicate severe or complex conditions requiring higher resources.
- Hospital Stays: Longer for ARF/MOSF with Sepsis and Malignancy; shorter for Lung and Colon Cancer.
- Hospital Charges: Consistent across age groups, but higher for ages 51-70 due to resource-intensive treatments.
- Survival Rates: Higher for Colon Cancer, Lung Cancer, and CHF; lower for Coma and ARF/MOSF with Sepsis.
- Age and Hospital Stays: Younger patients (0-30) have longer stays; older patients (91+) have shorter stays.
- Cancer Prevalence: Higher in males, especially for metastatic and non-metastatic categories.
- Diabetes: Most common in middle-aged adults (51-70).
- Glucose Levels: Extremely high levels (above 600) linked to lower survival predictions.
- Creatinine Levels: Elevated levels (above 10) associated with lower survival rates.
- Blood Pressure: Near-zero levels linked to fatal outcomes.
- Heart Rate: Near-zero and extreme rates linked to lower survival predictions.
- Combined Metrics: Glucose, creatinine, blood pressure, and heart rate can identify critical conditions.
- Age and Hospital Stay Length: Positive relationship; older patients tend to stay longer.
- Data Gaps: Significant gaps necessitate careful handling through imputation or exclusion.
- Demographic Trends: Older patients show lower survival probabilities.
- Extreme Data Points: Require careful treatment or exclusion.
- Visualisation Trends: Decreasing survival rates with increasing comorbidities or worsening APACHE scores.
- Variable Distributions: Some skewed, requiring transformation or normalization.

## Tools and Libraries Used:
- NumPy: Essential for performing numerical computations and efficiently handling arrays.
- Pandas: Crucial for data manipulation and analysis, providing powerful data structures like DataFrames.
- Matplotlib: Used for creating a wide range of static, interactive, and animated visualizations.
- Seaborn: Enhances Matplotlib's capabilities by offering attractive and informative statistical graphics.
- Missingno: Helps visualise and understand the presence and distribution of missing data within our dataset.
- Warnings: Suppresses any unnecessary warnings that might clutter the output, ensuring a cleaner and more readable analysis.

## Conclusion:
This analysis on the dataset provided a comprehensive overview of various health metrics and their implications for patient outcomes. By examining outliers, hospital stays, survival rates, and common conditions, we identified critical trends and areas for improvement in healthcare management.

## Resource Allocations:
- Increased Staffing and Specialised Training: For managing complex conditions.
- Advanced Medical Equipment: To better manage severe cases.
- Enhanced Support Services: For older patients and those with chronic conditions.

## Targeted Interventions:
- Early Detection Programs: For conditions like diabetes and cancer.
- Personalised Treatment Plans: Based on patient-specific data.
- Preventive Care Initiatives: To manage risk factors like high glucose and creatinine levels.

These strategies aim to enhance predictive modeling, improve patient care, and ensure efficient use of healthcare resources.

