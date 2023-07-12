# HR Analytics

## Introduction
The objective of this HR attrition project is to explore in more detail the phenomena and reasons behind employees leaving the organization. In addition, the project also aims to uncover valuable insights that will assist the HR team in making the right decisions for the company to enhance employee satisfaction and retention in order to prevent employee attrition.

## Data Sources:
The data is fictional dataset that can be found on Kaggle.com. 

## Process
I will use Microsoft Excel to identify duplicates, check for missing values and perform other cleaning tasks on a dataset consisting of 1470 rows. During the course of this process, it was discovered that there were no duplicate rows that needed to be eliminated and fortunately the data was clean.

## Insights have to be discovered:
-	How many employees are still working with the organization?
-	What is the average age of employees working in the organization?
-	How many employees left the organization?
-	What is the overall retention rate?
-	Which marital status tends to have higher attrition?
-	What is the attrition trend by gender?
-	What is the employee age distribution?
-	What is the stock option level trend of employee?
-	Does the rating on job satisfaction affect employees to quit?
-	How many employees leave the organization by education?
-	What is the average employees monthly income by job role?
-	Which department had the most significant attrition?

### Define KPIs: 
-	**Total Employees**
-	**Active employees**: employees who still remain work at the company.
-	**Total Attritions**: number of employees who left the company.
-	**Retention Rate**: to measure the percentage of active employees.
-	**Average Age**: average age of the total employees.

## Analysis and Visualization
In this process, I will use Tableau to conduct exploratory analysis of the data to answer the questions mentioned earlier.

First, we will break down the KPIs. 

<img width="817" alt="Screen Shot 2023-07-11 at 16 01 48" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/a8b5f9b8-4c5f-4f7b-926a-07bc5ee76670">

Out of all 1470 total employees, there were 237 employees who left the company with a retention rate of 83.88%. The average age of all employees working for the company is 37 years old.\

<img width="150" alt="Screen Shot 2023-07-11 at 16 08 34" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/a5825ee7-c24e-4041-a73b-988cbc2aaf6f">

The Research & Development Department encountered the highest attrition, whereas the Human Resource Department had the lowest.

<img width="250" alt="Screen Shot 2023-07-11 at 16 07 56" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/7cf03c73-dc3d-4584-b4e8-69d49e388b6c">
<img width="250" alt="Screen Shot 2023-07-11 at 16 07 56" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/c0996566-d199-4823-8a7a-63dbfaeae8e7">

The table on the right indicates the job satisfaction rating of all employees as well as the number of employees by job position and the total rating where rating number 1 is the lowest or shows dissatisfaction. the position of being a sales executive is the position with the most employees and also the lowest rating. in contrast to the table on the left which only shows total attrition. it can be clearly seen that the job position of being a laboratory technician is the largest contributor to employees leaving.

<img width="732" alt="Screen Shot 2023-07-12 at 10 33 15" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/076016dc-1552-46c7-94db-893d2730379b">

after discovering the roles that faced the most attrition were laboratory technicians and sales executives. The average salary of laboratory technicians is among the lowest at only 3.2k per month.

<img width="274" alt="Screen Shot 2023-07-11 at 16 07 41" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/4243ebc6-9eaf-49ce-ab94-6f5f7badea85">
<img width="269" alt="Screen Shot 2023-07-11 at 16 55 06" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/63d5e3b6-6e1e-4e1f-8ad5-796704722066">

The chart on the left side demonstrates the majority of employees work between the ages of 24-44. This demographic represents the organization's primary active workforce. Furthermore, the graph on the right indicates that the active workforce is also the one experiencing the most attrition.

<img width="282" alt="Screen Shot 2023-07-11 at 16 06 49" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/d5a52491-795c-4402-922b-56df71918170">

Of all employees who left the organization, many of them were male as many as 63.29% or 150 people compared to female.

<img width="267" alt="Screen Shot 2023-07-11 at 16 07 29" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/bce1267a-a6e3-476b-991f-8d13e62cfed0">

According to attrition by marital status, both men and women who are single lead the most attrition, followed by those who are married.

<img width="271" alt="Screen Shot 2023-07-12 at 10 32 49" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/41b388b5-4cac-453f-a992-c9e1bfb90908">
<img width="280" alt="Screen Shot 2023-07-12 at 10 33 02" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/9b9d954e-6e60-40fa-b54d-7c3903dad507">

Among all employees, the majority do not possess stock options. Furthermore, regarding attrition, over 50% of employees who decided to leave the organization were those who did not have stock options.

<img width="264" alt="Screen Shot 2023-07-11 at 16 08 07" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/fb1c23e9-86ec-4d0d-8dc3-88bc47d5525a">

The highest number of employee attrition can be observed between both males and females is someone who has a bachelor's degree.

In addition to analyzing, I also made an interactive dashboard. and this is how it looks.


<img width="1301" alt="Screen Shot 2023-07-12 at 13 52 30" src="https://github.com/tarahanni/HR_Attrition/assets/135048214/6ca070ed-9a0c-4bcf-b9f9-9e97478398ab">

## Recommendation: 
1. To overcome the high attrition especially in sales executive and laboratory technician roles, the organization should conduct exit surveys to identify reasons for resigning and implement strategies to improve their job satisfaction, such as providing additional training, support and opportunities for growth.
2. Organization is advised to increase salaries, particularly for laboratory technicians. After further investigation, it was found that this job role has the highest attrition and the lowest salary. Adjusting the salary for this job role to be more competitive with industry standards to retain skilled employees is something that needs to be done.
3. Organization experienced the most attrition also in employees who did not have stock options. Organization is advised to implement stock options or other financial incentives to employees in order to enhance retention. By doing this they will be more motivated to give their best contribution and will feel encouraged to improve their daily performance in the organization.
