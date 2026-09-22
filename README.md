# Hospital-Healthcare-Analytics-Resource-Optimization-Excel
Excel-based healthcare analytics case study analyzing patient demographics, medical conditions, insurance billing, patient footfall, and hospital resource optimization through scenario modelling

## Project Overview

Hospital Healthcare Analytics & Resource Optimization is an Excel-based healthcare analytics project focused on analyzing 10,000 patient records to identify meaningful patterns in patient demographics, medical conditions, healthcare billing, insurance providers, and hospital patient footfall.

The project was designed around three key business problems:

1. Demographic Analysis of Medical Conditions
Analyzed the distribution of medical conditions across different age groups and genders to identify demographic patterns and understand how conditions such as arthritis, cancer, asthma, diabetes, hypertension, and obesity vary across patient segments.

2. Patient Billing & Cost Analysis
Analyzed the average billing amount across medical conditions and insurance providers to identify significant variations in healthcare costs. The analysis was used to identify condition-specific and insurance-specific billing patterns and formulate potential cost-management considerations for patients.

3. Hospital Resource Management
Analyzed daily patient footfall and admission types (Emergency, Urgent, and Elective) to identify periods of high and low hospital demand. Scenario analysis was then performed to evaluate how shifting elective patients from high-demand periods to lower-demand periods could help smooth patient volumes and improve utilization of limited hospital resources such as beds, doctors, and nursing staff

Project type: Healthcare Analytics Case Study
Tool: Microsoft Excel
Dataset size: 10,000 patient records × 20 fields

## Tools & Techniques used
Microsoft Excel
PivotTables
PivotCharts
Data aggregation and segmentation
Calculated fields / percentage deviation analysis
Age-group and gender analysis
Insurance-provider comparison
Time-series / day-wise analysis
Scenario analysis
Business insight generation

## Why i chose This Project 
I chose this project because I wanted to solve a real-world business problem using data rather than just create visualizations. Healthcare data allowed me to analyze patient demographics, medical conditions, billing and insurance patterns, and then use patient-footfall data to explore how hospitals could better utilize limited resources. It also gave me the opportunity to demonstrate my Excel and analytical skills through PivotTables, dashboards and scenario analysis

## What Business Problem Does it Solve 
Hospitals operate with limited resources such as beds, doctors, nursing staff, and medical facilities, while patient demand can fluctuate significantly across different days and patient groups. This project addresses the challenge of using available healthcare resources efficiently while understanding patient and cost patterns

# Business Questions
# 1. Demographic Analysis of Medical Conditions

Objective: Identify the most prevalent medical conditions across demographic groups.

Key analysis:

1.Condition distribution by gender
2.Condition distribution across age groups
3.Age × gender segmentation
4.Identification of demographic concentration patterns

# 2. Patient Price Optimization

Objective: Identify billing trends and recommend ways patients can potentially reduce healthcare costs.

Key analysis:

1.Percentage deviation from the overall average billing
2.Insurance-provider × medical-condition comparison
3.Identification of Best Insurance Provider For Each Disease
4.Identifying Pattern Between What Age x Gender Should choose which Insurance For future

# 3. Hospital Resource Management

Objective: Identify patient-footfall patterns and improve utilization of limited hospital resources such as beds, doctors, and nurses.

Key analysis:

1.Year-wise and month-wise patient trends
2.Day-wise patient footfall
3.Admission-type analysis: Emergency, Urgent, and Elective
4.Scenario modelling to redistribute flexible elective demand
5.Created Scenerios for better Resource Allocation For Hospital 

# Data Preparation
Cleaned and transformed data using Excel Power Query Editor.
Standardized text, categorical values, blanks, and data types.
Extracted Year, Month, Day, and Age Groups.
Used VLOOKUP to map Blood Group information.
Standardized admission types: Emergency, Urgent, and Elective.
Prepared the dataset for PivotTable, PivotChart, and scenario analysis.

## Key Findings

# Demographic Insights
•	The dataset contains 5,075 female and 4,925 male patients, giving a relatively balanced gender split.
•	Hypertension is the most frequently observed condition with 2,155 cases.
•	Arthritis generally increases with age.
•	Cancer also shows an overall increasing pattern with age.
•	Asthma is concentrated among younger patients.
•	Obesity peaks in the 48–57 group and then declines across older groups.
•	Gender patterns vary by condition: female counts are higher for obesity and diabetes, while male counts are higher for hypertension and asthma.

# Billing & Insurance Insights
Major finding: billing variation is much larger across medical conditions than across insurance providers.
Overall insurer deviations from the average billing range only from approximately -2.61% to +3.62%
Condition                        Lowest Observed Billing Provider
Arthritis                        Cigna

Asthma                           UnitedHealthcare

Cancer                           Medicare

Diabetes                         UnitedHealthcare

Hypertension                     Medicare

Obesity                          Blue Cross


# Patient Footfall & Resource Insights
•	Daily patient arrivals are uneven, creating periods of high and low resource demand.
•	The baseline dataset peaks at approximately 497 patients on day 15 and reaches a low of 204 patients on day 6.
•	Patient volume is concentrated around the middle of the month, creating potential pressure on beds, doctors, nursing staff, and other hospital resources.
•	Elective patients provide the greatest scheduling flexibility compared with emergency and urgent admissions.
•	Scenario modelling was used to move elective demand away from peak periods toward lower-volume days, with the objective of smoothing workload and preserving capacity for emergency care.

# Resource Management Scenarios
Normal Scenerio(Without Analysis)
The Patients footfall is not regular 
<img width="1238" height="450" alt="Normal scenerio" src="https://github.com/user-attachments/assets/15a5c78b-d450-4b68-af38-d61129a5f8c5" />


## Scenario 1 — Demand Redistribution

Patients were redistributed from the high-demand middle period toward lower-demand days at the beginning of the period.
The model reduced the daily peak from approximately 497 to 401 patients, demonstrating how demand smoothing can reduce workload concentration.
<img width="1238" height="452" alt="image" src="https://github.com/user-attachments/assets/cec4c6ef-b95c-45b5-b8f1-99e81eefb5a6" />


As You can see a smoother curve for The patients Footfall
## Scenario 2 — 80% Elective Patient Transfer

A targeted scenario moved 80% of elective patients from the high-demand middle period toward earlier lower-volume days while retaining emergency and urgent demand.
The simulated peak falls to approximately 404 patients, showing that targeted elective scheduling can flatten the demand curve while maintaining capacity for less-flexible admissions
