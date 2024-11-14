# HR_Attrition_Tracker
This repository contains information about the Attrition Analysis of a company

# PROJECT TITLE: Attrition Analysis and Insights

## Table of Contents
[Introduction](Introduction)

[Data Overview](Data-Overview)

[Methodology](Methodology)

[Pivot tables](Pivot-tables)

[Visualizations](Visualizations)

[Findings](Findings)

[Recommendations](Recommendations)


## INTRODUCTION
### Problem statement 
Employee attrition is the gradual reduction in employee numbers. This represents a significant challenge for organizations, affecting operational efficiency. High attrition rates can lead to increased recruitment and training costs, lower employee morale, and the loss of valuable institutional knowledge. Identifying the key drivers of attrition and understanding the patterns behind employee departures are critical for implementing effective retention strategies. This analysis aims to address the company’s ongoing concern with high attrition rates and provide actionable insights to reduce it.

### Objective of the Analysis
The primary objective of this analysis is to assess the attrition trends within the organization over the last quarter, identify the key factors contributing to employee turnover, and highlight any patterns or correlations that can guide future retention efforts. By breaking down attrition data by department and demographic characteristics, we aim to provide a comprehensive view of the factors influencing employee departures. This report will also highlight potential gaps in current retention strategies and suggest targeted interventions to improve employee retention.

### Scope of the Analysis
This analysis covers employee turnover data for the second quarter of 2023, focusing on both voluntary and involuntary attrition. The analysis includes data from all departments within the company, with specific attention given to departments exhibiting higher-than-average turnover rates. Additionally, the report will examine attrition trends based on employee role, and demographics (age, gender, job title) to identify any specific groups or areas that may require focused retention strategies. The scope of this analysis is limited to internal employees who left the company voluntarily or involuntarily.


## DATA OVERVIEW
### Data Sources
HRIS systems (Workday), payroll systems, and employee satisfaction surveys.

 
### Key Features
Attrition Count: Total number of employees who left the organization.

Current employees count: Total number of current employees.

Departments: Breakdown of attrition by department.

Demographics: Age, gender, job title, educational field etc.

### Tools used 
For Data cleaning: Microsoft Excel

For Analysis: Microsoft Excel and PowerBI

For Visualization: PowerBI


## METHODOLOGY

The dataset was loaded into Microsoft Excel. It was cleaned by addressing the blanks, removing duplicates, and ensuring consistent formats across the cells. Data was summarized by attrition count by department, educational field, gender, business travels, marital status using the Pivot tables in Microsoft Excel. This gives us summarized information about the dataset. Further, the cleaned dataset was imported into PowerBI server to perform more analysis such as calculating the attrition rate, average of employers, total attrition and average monthly income. After obtaining satisfied results, visualizations were created using the same PowerBI.


## PIVOT TABLES
![Screenshot 2024-11-13 113851](https://github.com/user-attachments/assets/a5089f6d-354d-44a1-810f-0c1bb9bc0753)

![Screenshot 2024-11-13 113953](https://github.com/user-attachments/assets/4ee343c1-37cd-408b-9bf5-da7e5326b4b2)



## VISUALIZATIONS
![newset](https://github.com/user-attachments/assets/a4b66476-f0d5-4fb1-8d11-f2c1f67cf12b)

![Screenshot 2024-11-14 143026](https://github.com/user-attachments/assets/abd425dd-1483-4b0a-bb01-b21cefcb74b6)



## FINDINGS

In Q2 2023, a total of 237 employees left the company, resulting in attrition rate of 16%. The turnover rate was highest in the R&D and Sales departments, which accounted for 94% of the total exits, leaving HR department as the lowest exit rate at 6%. Male gender with 63% attrition is beats that of the females.

Employees in Life Sciences educational field has the highest attrition rate at 37% and the lowest educational field is the Human Resources.
Those that travel frequently for business contributes the highest exit rate at 65%, while those don’t travel has the lowest rate at 5%.

Life Sciences educational field has the highest number of employees that are very dissatisfied with their job and also the highest number of very satisfied employees. This could be because they are educational field with the highest employees.

Laboratory Technicians have the highest very dissatisfied employees and Sales representatives have the highest very satisfied employees.


## RECOMMENDATIONS
### 1.	Focus on Retaining Key Departments
   
Since R&D and Sales departments have the highest turnover rates, implement targeted retention strategies:

I would suggest conducting exit interviews to identify specific pain points within this department, such as workload, lack of growth opportunities, or unmet job expectations. Addressing these issues may help retain talent.
Also, given the high attrition rate, incentives like performance-based rewards, flexible work options, or mentorship programs can keep the teams engaged and motivated.

### 2.	Gender-Specific Retention Strategies

Since male employees have a significantly higher attrition rate, I recommend;

Conducting Focus Groups and Surveys: This can help uncover specific factors affecting male employees’ job satisfaction or areas they find challenging.
Introducing Mentorship Programs: Pairing employees with mentors, especially for career guidance, could increase engagement and retention.

### 3. Reduce Attrition in the Life Sciences Educational Field

The Life Sciences educational field has both high attrition and polarized satisfaction levels. 

Target Growth and Development: Offer tailored training programs, certifications, and cross-functional projects to improve job satisfaction and reduce dissatisfaction.
Enhance Engagement: Establish regular one-on-one feedback sessions and set clear career growth paths, addressing both dissatisfaction and enhancing satisfaction for those already engaged.

### 4. Reassess Travel Requirements

Employees who travel frequently have the highest attrition rates. To improve retention, I suggest these few options;

Introduce Flexible Travel Options: Allow virtual meetings as alternatives to reduce travel demands. For those who must travel, provide additional support like travel bonuses, better accommodations, or time-off post-travel.

Evaluate Job Role Suitability: Consider hiring travel-preferred candidates for roles with high travel demands or explore alternative ways to distribute travel responsibilities among willing employees.

### 5. Engage Highly Satisfied Sales Representatives for Insights

Sales representatives reported high job satisfaction. You can leverage their experiences to improve engagement in other departments by:

Peer Learning Initiatives: Implement cross-departmental discussions or learning sessions where highly satisfied Sales reps share tips on job satisfaction.
Identify and Replicate Best Practices: Determine which practices contribute to the high satisfaction in Sales and explore adapting them in departments with lower satisfaction.

### 6.	Improve Job Satisfaction for Laboratory Technicians

With Laboratory Technicians reporting the highest dissatisfaction, options such as:

Workload and Role Clarity: Consider reviewing the workload to ensure job roles are clear and manageable to avoid burnout.
Career Growth Opportunities: Offer specific development programs or paths for promotion to make Laboratory Technicians feel more valued and invested in their roles.



