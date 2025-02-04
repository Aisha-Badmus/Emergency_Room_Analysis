# Emergency Room Analysis
This dashboard demonstrates actionable insights derived from the emergency room data and provides strategic recommendations to enhance operational efficiency and patient satisfaction.

## Project Background
The project involves analyzing emergency room (ER) visit data to assess operational efficiency, patient satisfaction, and service delivery across different demographics. The analysis aims to uncover actionable insights and provide strategic recommendations for improving ER operations and patient experience.

Insights and recommendations focus on:  
  - **Trends in ER visits:** Evaluation of patients visiting the ER, demographics (age, gender, race), and service types (admission status, patient type).
  - **Wait times:** An assessment of wait times across demographics and service types, such as walk-in vs. referred patients.
  - **Patient Satisfaction:** An analysis to understand patients' satisfaction  across demographics and service types.

An interactive PowerBI dashboard can be downloaded here\
Targeted SQL queries regarding various business questions can be found here

## Data Structure & Initial Checks 
Patient database structure as seen below consists of a table: **Patient** with a total row count of 9,216 records.\
Below are the columns, datatype, and descriptions for better understanding.

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets.\ 
Power BI was used to inspect and perform the quality checks including:
-	Creating new time and moment columns from the date column,
-	Merging first and last name columns,
-	Adjusting data formats.

## Executive Summary
### Overview of Insights	
The total number of ER visits is 9,216, with a near-even split between male and female patients. Adults dominate the patient base with 77% of visits. The average wait time across all patients is 35.26 minutes, but this varies significantly by department referral and service type. The overall average satisfaction score is 5.47 with some disparities existing across races. ER visits peak in July and are lowest in February with higher visit volumes correlating with a slight increase in wait time and dip in average satisfaction scores.

