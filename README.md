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








![hr project dashboard 2 ](https://github.com/user-attachments/assets/a9cabfde-d8aa-4224-9b9a-b27b09b76ddd)






### Insights Generation
---

 
1. Attrition Count by Department

     The R&D department has the highest attrition rate, which could be due to the nature of the work, stress levels, 
     or other factors influencing employee turnover. The HR department has the lowest attrition, indicating relatively
     better retention.

2. Attrition Count by Educational Field

    Life Sciences has the highest attrition by far in the Educational field, suggesting challenges in retaining employees
    with a Life Sciences background. Others like Human Resources has the lowest attrition.
    Employees from Life Sciences and Medical backgrounds seem more likely to leave, possibly due to job dissatisfaction, 
    career growth opportunities, or competitive demand in the industry.

3. Attrition by Age Band

   Younger employees (especially in the 25-34 age group) are more likely to leave, which may indicate that they are 
   seeking better opportunities, career growth, or facing dissatisfaction in their current roles.

 
4. Attrition by Age Group and Gender

    In all age groups, male employees have a higher attrition rate than females, with the highest attrition seen in males aged 35-44.
    Retention strategies may need to target younger and mid-career male employees specifically.


5. Current Employees by Age Band and Gender

     The largest employee age group is 25-34, with a total of 540 employees, followed closely by the 35-44 age group with 384 employees.
     In both these age groups (25-34 and 35-44), there is an almost equal distribution between female and male employees, with a slight majority of male employees.
     There are significantly fewer employees under 25 and over 55, with only 76 in the under-25 age group and 39 in the over-55 age group.
     The gender distribution across all age bands shows a near-equal representation, though slightly more male employees overall.


6. Attrition Count by Job Role

    The Laboratory Technician role has the highest attrition, with over 60 employees leaving, followed by Sales Executive and Research Scientist roles.
    Attrition rates generally decline across the other roles, with Healthcare Representative, Manager, and Research Director roles having
    the lowest attrition counts. This suggests that the roles with higher technical demands (like Laboratory Technician and 
    Research Scientist) or possibly higher stress environments (like Sales Executive) have higher turnover rates.


 
7. Attrition Count by Marital Status

    Single employees have the highest attrition rate, followed by married employees, with divorced employees showing the lowest attrition rate.
    This trend could indicate that single employees may be more open to changing jobs or have fewer commitments that tie them to a particular
    role compared to their married or divorced counterparts.



 
8. Employee Satisfaction by Job Role

    The Laboratory Technician and Research Scientist roles show high levels of dissatisfaction and very dissatisfaction, with over 20 dissatisfied 
    employees in Laboratory Technician role.
    Sales Executive roles also have notable dissatisfaction levels, though there are some satisfied employees as well.
    Roles like Healthcare Representative, Human Resources, and Manager have relatively low dissatisfaction levels, which may imply better job 
    satisfaction or workplace conditions in these roles.



9. Employee Distribution by Education Field

    Life Sciences is the most common education field, with 89 employees, followed by Medical (63).
    Life Sciences also shows high levels of dissatisfaction, with 42 employees reporting dissatisfaction across different levels.
    This could suggest that employees with a Life Sciences background, who may often fill roles like Research Scientist and Laboratory Technician, 
    are experiencing job dissatisfaction, aligning with the high attrition rates in those roles.




10. Current Employees by Marital Status and Gender

     The majority of employees are married, with 589 married female and male employees.
     Single employees follow, with 152 females and 198 males, while divorced employees are the smallest group.
     The marital status distribution shows a balanced gender representation, but given the higher attrition for single employees, 
     the company may want to investigate what motivates them to leave.









 






















Key Takeaways

- High Attrition in Specific Departments and Fields: The R&D department and employees with a Life Sciences background show
   high attrition. These areas may require targeted retention efforts, like addressing work conditions, stress levels, or
   offering career growth paths.

- Gender Disparity in Attrition Rates: Male employees exhibit higher attrition across all age groups. This could be due to
   role distribution, career aspirations, or workplace culture factors that differ between genders.


- Age-Based Attrition Trends: Younger employees, particularly those aged 25-34, have the highest attrition rates,
   likely due to their pursuit of career growth. Retention strategies focusing on professional development, mentorship,
   and engagement could help reduce attrition in this group.

- High Attrition in Technical Roles: The Laboratory Technician, Sales Executive, and Research Scientist roles have high attrition rates, 
  which could be due to job stress, satisfaction levels, or potential career growth in other companies or industries.

- Satisfaction Issues in Certain Fields: Dissatisfaction is high in roles requiring a Life Sciences background, 
  which might suggest a need for improved working conditions, better career support, or more engagement opportunities 
  for employees in technical fields.

- Marital Status and Retention: Single employees are more likely to leave compared to married or divorced employees, 
 which could be an area for retention strategies.

- Age Group and Employee Distribution: The company’s workforce is concentrated in the 25-44 age range, with a balanced gender distribution. 
 This demographic may require specific career development and satisfaction-focused initiatives to reduce turnover.


In conclusion, addressing the high attrition in the R&D department and among younger employees, particularly those from Life Sciences and males, 
could positively impact retention. Implementing targeted strategies that address department-specific issues and provide career advancement
opportunities may help improve overall employee satisfaction and retention.
Also, the organization may benefit from targeted retention programs, especially for single and technically skilled employees, 
as well as initiatives to improve job satisfaction in high-attrition roles.

















 











