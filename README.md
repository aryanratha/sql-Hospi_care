# sql-Hospi_care
This project focuses on analyzing inpatient discharge data to uncover operational trends, evaluate hospital length of stay (LOS), and understand demographic distributions. 

📌 Project Overview
This project focuses on analyzing inpatient discharge data to uncover operational trends, evaluate hospital length of stay (LOS), and understand demographic distributions. By leveraging a comprehensive real-world medical dataset, this analysis provides actionable insights into how patient volume and discharge patterns fluctuate across different variables.

📊 The Dataset
The data originates from the cardiology unit of Hero DMC Heart Institute (Dayanand Medical College and Hospital, Ludhiana, Punjab, India), a tertiary care facility.

Timeframe: April 1, 2017 – March 31, 2019 (2 Years)

Scale: 14,845 total admissions across 12,238 unique patients (including 1,921 readmissions).

Variables Tracked:

Administrative: Date of Admission, Date of Discharge, Type of Admission (Emergency vs. Outpatient).

Demographics: Age, Sex, Locality (Rural/Urban).

Patient History: Smoking, Alcohol, Diabetes Mellitus (DM), Hypertension (HTN), Prior CAD, Prior CMP, Chronic Kidney Disease (CKD).

Lab Parameters: Hemoglobin (HB), Total Lymphocyte Count (TLC), Platelets, Glucose, Urea, Creatinine, BNP, Raised Cardiac Enzymes (RCE), Ejection Fraction (EF).

Comorbidities: 28 additional features including Heart Failure, STEMI, and Pulmonary Embolism.

🎯 Business Objectives
As a Data Analyst for Auto Care Hospital, the primary goal was to optimize hospital bed management and understand patient flow by analyzing:

Length of Stay (LOS): How do different diagnoses and patient histories impact the average time spent in the hospital?

Demographic Distribution: How do discharge rates vary across different age groups and genders?

Operational Trends: What does the daily discharge volume look like? Are there specific days of the week that experience peak discharge rates?

🛠️ Technical Stack & SQL Concepts
All data exploration and analysis were performed using Microsoft SQL Server. The queries heavily utilized the following advanced SQL concepts:

Data Aggregation: GROUP BY, SUM(), COUNT(), AVG()

Conditional Logic: CASE WHEN statements to categorize age groups and length of stay tiers.

Advanced Querying: Common Table Expressions (CTEs) and Subqueries to build temporary result sets for complex calculations.

Window Functions & Sorting: ORDER BY and Ranking functions to identify peak admission/discharge days and operational bottlenecks.

🚀 Key Insights & Analysis Areas
(Note: You can update this section with your actual findings once you complete the queries)

Day of the Week Trends: Identified which days require heavier staffing for discharge processing.

Age & Gender Profiling: Segmented patient data to find the demographics with the highest volume of emergency admissions.

LOS Bottlenecks: Correlated specific comorbidities (e.g., CKD, STEMI) with extended lengths of stay.
