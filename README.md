# HR Analytics Project

## Project Overview
This project aimed to analyze HR Data to gain  insights into employee trends, attrition and provide strategid decision making. 

### Project Objectives
1. Analyze current HR department attrition patterns
2. Identify key factors contributing to turnover
3. Develop targeted retention strategies
4. Create implementation roadmap for recommendations

## Data Collected
The HR Data analyzed in this Project comprised of 1,470 number of record and included the key  following variables:
#### Variables
  - Attrition: Employee turn over(0/1, Yes/No)
  - CF_age band: Categorical Age groups( under 25, 25-34, 35-44, 45-54 and above 55)
  - Department: organizational department
  - Educational Field: Employee field of study
  - Gender
  - Marital Status: Employees's marital status ( Single, Married, Divorced)
  - Job Role: Employee Job title
    
### Tool Used
---
 - Power BI

### Methodology
1. Data Cleaning and preparation
2. Exploratory Data Analysis(EDA)
3. Formula Used
4. Data Visualization

### Data Cleaning and Preparation
---
In the initial phase of the data cleaning and data preparation, we perform the following functions:
  1. The data was loaded, tranformed and cleaned.
  2. Conditional columns were added such as  Attrition count, age sort and Job Satisfaction Rating

### EXploratory Data Analysis
---
EDA involves the exploring of the data to answer some questions about the data such as:
 #### Attrition
  1. What is the overall attrition rate in the organisation?
  2. Which Department have the highest/ lowest attrition rate?
  3. Is there a correlation between monthly income and attrition?
 #### Demographics
  1. What is the age distribution of the employee?
  2. what is the average age of the employee?
  3. What is the most common educational fields among Employee?
  4. Is there a difference in the attrition rate between marital status group?
 #### Job Characterictics    
 1.  Is Job satisfaction related to attrition?
 2.  What Job roles have the Highest/Lowest attrition rate?
 3.  Is Job satisfaction related to attrition?
 #### Strategic Decision Making
  1. What initiatives can we employ to reduce attrition?
  2. How can we optimize employee retention strategies departmen-wise?

### Formula Used
```Power BI
Attrition Rate = Attrition count / CF_current Employee
```
  
#### Data Visualisation
---
![HR Screenshot](https://github.com/user-attachments/assets/50769208-b7d1-4f08-a6d7-501e46dfb1ff)

From our visualization we can answer the questions raised from Exploratory Data Analysis
 - 237 employees have left the oraganization and Attrition Rate is 16%
 - The Pie chart reveaed that R&D had the highest attrition in department level (133 employees)
Educational Field Distribution of Attrition:
- Life Sciences shows the highest attrition (around 80 employees)
- Medical field is second (about 64 employees)
- Marketing and Technical fields show moderate attrition (around 35 and 32 employees respectively)
- Other fields and Technical Degree show lower attrition rates (11 and 7 employees respectively)

Gender Distribution of Attrition:
- Male employees account for 63.29% of attrition
- Female employees account for 36.71% of attrition

This visualization suggests that:
1. The organization has a significant attrition challenge, particularly in R&D and Life Sciences
2. There's a gender imbalance in attrition, with males leaving at a higher rate
3. Technical and support roles seem to have better retention than scientific and sales roles

### using the Filter function to determine the attrition from each Educational Field
---
#### Human Resource

![HR HM](https://github.com/user-attachments/assets/41ae6711-0b4b-4a69-8e9c-cb248f612497)

##### Key Findings
 - From the total employee in the organisation, Human Resource have 27 employees and the number of people that left the organisation is 7 with an attrition rate of 26%.
 - Attrition count by department shows that  59 people left R&D, 29 from sales department and 1 from HR.
 - 100% of departing employees had HR educational backgrounds
 - HR department's 26% attrition rate exceeds organizational average by 10%
 - Small team size magnifies impact of each departure

## Strategic Recommendations
1. Implement stay interviews
2. Review compensation structures
3. Launch flexible work arrangements
4. Establish regular feedback mechanisms

### Life Science
--- 
![HR LS](https://github.com/user-attachments/assets/a0e2f9c8-5ffb-4459-86a4-974b66bf4398)

- From the total employee in the organisation, Life Science have 606 employees and the number of people that left the organisation is 89 with an attrition rate of 15%.
- Attrition count by department shows that  59 people left R&D, 29 from sales department and 1 from HR.

### Marketing
---
![HR MKT](https://github.com/user-attachments/assets/389c3c72-5935-426b-ab01-60bad7a137ef)


The number of employee that left the organisaion from Marketing account for 35 and the department they left from is sales department


### Medical
![medical](https://github.com/user-attachments/assets/34627784-83c9-4285-82e8-bcca18d7bbdd)



### Other
![other](https://github.com/user-attachments/assets/20116660-f8e2-4cdc-89b8-70e4cc28c49a)

### Technical
![technical](https://github.com/user-attachments/assets/7a0859a0-7b2e-4526-87c6-15e7d6ae0886)


![image](https://github.com/user-attachments/assets/6564f1c4-be8e-47cf-8453-0c844f8d22ef)


The visualisation shows the Job role and and their Job Role and their Satisfation level and the marital status of the employee in the orgnisatiom





### Recommendations:
- Conduct exit interviews to understand why HR professionals are leaving
- Review compensation and career development opportunities
- Assess workload and team structure given the small team size
- Develop retention strategies specifically for HR professionals
- Consider implementing mentorship programs to improve engagement
