# Employee Attrition Analysis using Power BI

## Overview
ABC Corporation, a multinational company, aims to address employee attrition challenges by implementing a Power BI project. This case study outlines project objectives, data sources, methodology, and deliverables.

## Project Objectives
1. **Identify Key Drivers of Attrition:** Determine primary factors influencing employee attrition.
2. **Segmentation Analysis:** Analyze attrition rates across various segments (departments, job roles, genders, education levels) to identify high-risk groups.
3. **Dashboard and Reporting:** Design an interactive dashboard to present insights and recommendations effectively.

## Data Sources
1. **Database:** Three database tables provided:
   - `Employee_survey`: Employee satisfaction, work-life balance, etc.
   - `Manager_survey`: Manager responses regarding employee performance, etc.
   - `EmployeeInfo`: Demographic information, job role, etc.
2. **IN/OUT Times:** Two sheets extracted from the Clock-In-Machine for year 2015 containing in/out times for all employees.

# Dimensional Modeling

In our modeling approach, we prioritize the attrition process as the primary business focus, emphasizing key metrics such as attrition rate and total attrition.

## Business Process and Metrics
- **Attrition:** The primary business process under scrutiny.
- **Key Metrics:**
  - Attrition Rate
  - Total Attrition

## Declare The Grain
- **Grain:** Each individual employee serves as the primary unit of analysis.

## Define The Dimensions
1. **Employee Information:** 
   - Contains demographic data, job role, and other pertinent employee details.
   
2. **Employee Survey Data:**
   - Includes responses from employees regarding satisfaction, work-life balance, etc.
   
3. **Employee Key Performance Indicators (KPIs):**
   - Encompasses data related to employee performance and evaluations, such as manager surveys and other KPI metrics.
     
![image](https://github.com/AliMagdy100/Attrition_Analysis_Using_PowerBI/assets/87953057/b2ddabea-fcf9-4678-80e2-5737c10bdd84)



## Attrition Dashboard
**According to Employees Info** 
![image](https://github.com/AliMagdy100/Attrition_Analysis_Using_PowerBI/assets/87953057/cc871e38-f03a-4b78-a26f-e00793b9879d)

