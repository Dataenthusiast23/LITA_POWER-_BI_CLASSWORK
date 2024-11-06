This is the documentation of the Power BI Class work on HR Attrition during my training
at LITA through the Incubtor Hub.

# EMPLOYEE ATTRITION ANALYTICS 

[Abstract](#abstract)

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Project Objective](#project-objective)

[Basic statistics about the dataset](#basic-statistics-about-the-dataset)

[Tools Used](#tools-used)

[Methodology](#methodology)

[Analysis](#analysis)

[Approach](#approach)

[Dashboard Overview](#dashboard-overview)


## Abstract
This project analyzes the attrirtion of an Organisation with the Employeee
population of 1470 personnels. The analyzes covers the Employee demographics, Business travels, 
Departments, Education fields, Job Roles, Education, Distance from home.   


## Project Overview
---

This project specifically focused on identifying why employees voluntarily leaves, 
understand how employee-friendly is the organisation.


## Data Sources
---
The dataset used in this analysis was obtained from the LITA _Class LMS powered by the Incubtor Hub.
The original data included various HR demographics and other fields metrics collected from the 
organisation's records. It contains 41 colums with some of the colums including but not limited to the following:

   - Attrition : Represent the attrition status
   - Age band : Represent the age ranges
   - DEpartment: Sections in the organisation
   - Education Field : This is the course of study of each employee
   - Employee Number : Unique identifier of each persnnel
   - GEnder : Identifies male and female 
   - Job role : The position held by each employee
   - MAarital Status : whether Married, Single or divorced



## Project Objective
---

The primary objectives of this analysis are:

 - To determine the attrition rate
 - to determine the factors Influencing attrition
 - to determine the employees at risk of leaving
 - to design strategies to reduce attririon and
   retain top talents.




### Basic statistics about the dataset
---

   - Number of Employees 1,470

   - Number of Attrition 237

   - Number of Current Employees 1,233

   - Attrition Rate 16%

   - Average Age 37


## Tools Used
---

 - Microsoft Excel [Download Here](https://www.microsoft.com)
 - Microsoft Power BI  [Download Here](https://www.microsoft.com)
 - Github for Buiding portfolio

  ## Methodology
  ---

### Data Cleaning
 Not much was done here beacuse the data was clean and except checking to ensure 
 the datatype was correct with the columns.

 ### Added new columns
 ---
 
  - Added  columns for attrition count, age sort and job satisfaction ratinng


### Explorative Data Analysis
---

   After downloading the data in Excel, it was imported into Power BI query editor 
   and the following were perfoemed

   - DAX:  attrition rate, average age measures were created using DAX function.

   - Dashboard Creation:  An interactive dashboard was created to present keys findings .


## Analysis
---

### Analysis Questions

  - What is the number of attrition?

  - What is the number of current employees?

  - What is the average age?

  - What is the attrition count by department?

  - What is the attrition count by Educational field?


### Approach

   The questions were addressed using different visuals to identify key trends.  


### Dashboard Overview






![HR TRACKER DASHBOARD 1](https://github.com/user-attachments/assets/1605806d-d167-4370-b63b-6404df262047)









![HR TRACKER DASHBOARD 2 ](https://github.com/user-attachments/assets/85172b65-9efc-4df2-b614-2f63b050794b)


### Insights Generation
---

 
 Attrition Count by Department

 The R&D department has the highest attrition rate, which could be due to the nature of the work, stress levels, 
 or other factors influencing employee turnover. The HR department has the lowest attrition, indicating relatively
 better retention.

 Attrition Count by Educational Field

 Life Sciences has the highest attrition by far in the Educational field, suggesting challenges in retaining employees
 with a Life Sciences background. Others like Human Resources has the lowest attrition.
 Employees from Life Sciences and Medical backgrounds seem more likely to leave, possibly due to job dissatisfaction, 
 career growth opportunities, or competitive demand in the industry.

 Attrition by Age Band

 Younger employees (especially in the 25-34 age group) are more likely to leave, which may indicate that they are 
 seeking better opportunities, career growth, or facing dissatisfaction in their current roles.

 
Attrition by Age Group and Gender

 In all age groups, male employees have a higher attrition rate than females, with the highest attrition seen in males aged 35-44.
 Retention strategies may need to target younger and mid-career male employees specifically.


Current Employees by Age Band and Gender

The largest employee age group is 25-34, with a total of 540 employees, followed closely by the 35-44 age group with 384 employees.
In both these age groups (25-34 and 35-44), there is an almost equal distribution between female and male employees, with a slight majority of male employees.
There are significantly fewer employees under 25 and over 55, with only 76 in the under-25 age group and 39 in the over-55 age group.
The gender distribution across all age bands shows a near-equal representation, though slightly more male employees overall.


Attrition Count by Job Role

The Laboratory Technician role has the highest attrition, with over 60 employees leaving, followed by Sales Executive and Research Scientist roles.
Attrition rates generally decline across the other roles, with Healthcare Representative, Manager, and Research Director roles having
the lowest attrition counts. This suggests that the roles with higher technical demands (like Laboratory Technician and 
Research Scientist) or possibly higher stress environments (like Sales Executive) have higher turnover rates.


 
 Attrition Count by Marital Status

Single employees have the highest attrition rate, followed by married employees, with divorced employees showing the lowest attrition rate.
This trend could indicate that single employees may be more open to changing jobs or have fewer commitments that tie them to a particular
role compared to their married or divorced counterparts.



 
 Employee Satisfaction by Job Role

The Laboratory Technician and Research Scientist roles show high levels of dissatisfaction and very dissatisfaction, with over 20 dissatisfied 
employees in Laboratory Technician role.
Sales Executive roles also have notable dissatisfaction levels, though there are some satisfied employees as well.
Roles like Healthcare Representative, Human Resources, and Manager have relatively low dissatisfaction levels, which may imply better job 
satisfaction or workplace conditions in these roles.



Employee Distribution by Education Field

Life Sciences is the most common education field, with 89 employees, followed by Medical (63).
Life Sciences also shows high levels of dissatisfaction, with 42 employees reporting dissatisfaction across different levels.
This could suggest that employees with a Life Sciences background, who may often fill roles like Research Scientist and Laboratory Technician, 
are experiencing job dissatisfaction, aligning with the high attrition rates in those roles.




Current Employees by Marital Status and Gender

The majority of employees are married, with 589 married female and male employees.
Single employees follow, with 152 females and 198 males, while divorced employees are the smallest group.
The marital status distribution shows a balanced gender representation, but given the higher attrition for single employees, 
the company may want to investigate what motivates them to leave.









 






















Key Takeaways

1. High Attrition in Specific Departments and Fields: The R&D department and employees with a Life Sciences background show
   high attrition. These areas may require targeted retention efforts, like addressing work conditions, stress levels, or
   offering career growth paths.

2. Gender Disparity in Attrition Rates: Male employees exhibit higher attrition across all age groups. This could be due to
   role distribution, career aspirations, or workplace culture factors that differ between genders.


3. Age-Based Attrition Trends: Younger employees, particularly those aged 25-34, have the highest attrition rates,
   likely due to their pursuit of career growth. Retention strategies focusing on professional development, mentorship,
   and engagement could help reduce attrition in this group.
















In conclusion, addressing the high attrition in the R&D department and among younger employees, particularly those from Life Sciences and males, 
could positively impact retention. Implementing targeted strategies that address department-specific issues and provide career advancement
opportunities may help improve overall employee satisfaction and retention.





 











