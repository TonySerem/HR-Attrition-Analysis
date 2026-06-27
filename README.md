# HR-Attrition-Analysis
In this project we analyse employee turnover to understand why employees leave an organization, who is leaving, and how the company can reduce unwanted turnover

## Dashboard Preview
## 1. Attrion by Employee Satisfaction
Description: The dashboard includes the key metrics such as Total number of Employees and Attrition Rate.
Layout: The dashboard is divided into five main sections: Attrition by Employee's Working Years, Attrition by Employee Satisfaction, Attrition by Distance to Work, Attriton by Department and Attrition BY Gender.
Key Metrics:
-	Total number of Employees: 2,925
-	Attrition Rate: 17%

## 2. Attrition by Job Role, Employee Working Years and Employee Education
Description: The dashboard includes the key metrics such as Total number of Employees and Attrition Rate.
Layout: The dashboard is divided into three main sections: Attrition by Job Role, Attrition by Employee Working Years, Attrition by Employees Education.
Key Metrics:
-	Total number of Employees: 2,925
-	Attrition Rate: 17%

## 3. Age And Performance Attrition
Description: The dashboard includes the key metrics such as Total number of Employees and Attrition Rate.
Layout: The dashboard is divided into two main sections: Attrition by Age bracket and Gender and Attrition by Employee Performance.
Key Metrics:
-	Total number of Employees: 2,925
-	Attrition Rate: 17%

  ## Tools Used
- Power Bi
- Power Query
- DAX

## Data Preparation - Power Query
- Removed top rows
- Changed the first row to be headers
- Removed columns 40-49 which had no meaningful information
- Added a conditional column called distance status to group Employee distance to work into; Near by, Far and Very Far
- Added a conditional column called Employee Workin Years to group Employee Working Years into; between 0-10, 11-20 and 21-30
- Added a conditional column called Employee Satisfaction to group Employee Satisfaction into; Very Satissfied, Satissfied and Dissatisfied
- Added a conditional column called Age Group to group Employee's Age into; 18-25, 26-35, 36-45, 46-55 and 56 plus

## DAX Measures
- Total Employees
- Total Attrition
- Inactive Employees
- Low Performance Employees
- High Performance Employees
- Department Attrition
  
## Objectives
- The primary purpose of this HR attrition analysis is to identify the factors driving employee departures, predict attrition trends, and implement evidence-based strategies that improve employee retention, reduce costs, and strengthen overall organizational performance

## Analysis
- Key performance indicators (KPI's); Total Number of Employees and Attrition Rate
- Attrition by Employee's Working Years
- Attrition by Employee Satisfaction
- Attrition by Distance to Work
- Attriton by Department
- Attrition BY Gender
- Attrition by Job Role
- Attrition by Employee Working Year
- Attrition by Employees Education

## Filters
- Gender
  
## Key Findings and Insights
- Total Number of Employees - 2,925, Attrition Rate - 17%
- Attrition by Employee's Working Years:
  Employees with Total working years between 0-10 years have the highest attrition which is 378 while Employees with Total working years which is 31 plus years have the lowest attrition which is 11
- Attrition by Employee Satisfaction:
  Dissatisfied Employees had the highest Attrion of 151, followed by single Very Satissfied Employees 134, followed by Very dissatisfied with 111 then Satisfied with 96.
- Attrition by Distance to Work:
  Near by Employees had the highest Attrition at 60.16%, followed by Far Employees at 20.73%, then Very far at 19.11%.
- Customer subscription according to Number of contacts with a customer during the campaign:
  Between 1 – 6 contacts with a customer during the campaign had the highest number of subscriptions.

## Conclusion

Summary of Findings: The number of customers who subscribed to a term deposit is quite lower compared to those who did not subscribe to a term deposit across key metrics. New strategies need to be implemented by the marketing department aiming to convince more customers to subscribe to a term deposit.

 ## Recommendations
- Increase marketing campaigns to groups which had a higher subscription to the term deposit, for example, according to number of subscribers per job we could increase marketing campaigns towards those who are in a managerial position since they had the highest number of subscribers.
- Change Marketing Campaign tactics for groups with lower subscriptions to the Term deposit
