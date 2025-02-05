# Emergency Room Analysis
This dashboard demonstrates actionable insights derived from the emergency room data and provides strategic recommendations to enhance operational efficiency and patient satisfaction.

## Project Background
The project involves analyzing emergency room (ER) visit data to assess operational efficiency, patient satisfaction, and service delivery across different demographics. The analysis aims to uncover actionable insights and provide strategic recommendations for improving ER operations and patient experience.

Insights and recommendations focus on:  
**1. Trends in ER visits:** Evaluation of patients visiting the ER, demographics (age, gender, race), and service types (admission status, patient type).\
**2. Wait times:** An assessment of wait times across demographics and service types, such as walk-in vs. referred patients.\
**3. Patient Satisfaction:** An analysis to understand patients' satisfaction  across demographics and service types.

An interactive Power BI dashboard can be downloaded [here](https://github.com/Aisha-Badmus/Emergency_Room_Analysis/blob/main/Patients%20Analysis.pbix)\
Targeted SQL queries regarding various business questions can be found here

## Data Structure & Initial Checks 
Patient database structure as seen below consists of a table: **Patient** with a total row count of 9,216 records.\
Below are the columns, datatype, and descriptions for better understanding.
![database structure](https://github.com/Aisha-Badmus/Emergency_Room_Analysis/blob/main/Db%20structure.jpg)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarization with the datasets.\
The dataset is a csv file. Power BI was used to inspect and perform quality checks including:  
1. Creating new time and moment columns from the date column,  
2. Merging first and last name columns,  
3. Adjusting data formats,  
4. ensuring all records are complete, and  
5. null values for the satisfaction score were left as it means customers didn't give any rating.

## Executive Summary
### Overview of Insights	
The total number of ER visits is 9,216, with a near-even split between male and female patients. Adults dominate the patient base with 77% of visits. The average wait time across all patients is 35.26 minutes, but this varies significantly by department referral and service type. The overall average satisfaction score is 5.47 with some disparities existing across races. ER visits peak in July and are lowest in February with higher visit volumes correlating with a slight increase in wait time and dip in average satisfaction scores.

Below is a snapshot of the Power BI dashboard. The interactive dashboard can be downloaded [here](https://github.com/Aisha-Badmus/Emergency_Room_Analysis/blob/main/Patients%20Analysis.pbix).

![dashboard](https://github.com/Aisha-Badmus/Emergency_Room_Analysis/blob/main/Dashboard%201.jpg)

### Key Insights
**1.	Demographic Dominance and Service Utilization**
- Adults (77% of total visits) are the primary users of ER services, suggesting resource allocation should focus on this group.
- Admitted patients have lower waiting times and better satisfaction scores suggesting good service those admitted.
- Average wait time is higher in the mornings with 35.53 minutes, suggesting a need for additional staffing and resources during this time.

**2.	Waiting Times**
- Patients referred to departments like Neurology and Cardiology exhibit the longest wait times (37 and 35 minutes, respectively), indicating some operational inefficiencies.
- Heatmap indicates that patients aged 51-60 and 70+ have the highest average wait times across multiple racial groups showing a potential inefficiency in handling elderly patients.

**3.	Satisfaction Disparities**
- Racial disparities are evident, with African Americans reporting lower satisfaction scores compared to other groups indicating potential bias or communication gaps.
- Walk-in patients are more satisfied than referred patients, highlighting the need to streamline referral processes to improve satisfaction for referred patients.

## Recommendations
**1. Resource Allocation:** Increase staffing and resource availability during the mornings to handle visit volumes effectively.\
**2. Optimizing Referrals:** Focus on reducing wait times in Neurology and Cardiology through better triaging, appointment scheduling, and resource allocation.\
**3. Addressing Racial Disparities:** Conduct additional research to understand why African Americans report lower satisfaction scores and implement targeted measures to address these concerns.\
**4. Implement an Age-Based Fast-Track System:** Prioritize elderly patients (51-60 and 70+ age groups) by introducing dedicated time slots or priority scheduling.\
**5. Enhance Patient Communication:** Improve communication with referred and non-admitted patients to mitigate dissatisfaction. This includes providing clear expectations about wait times and processes.




