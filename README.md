# Pewlett_Hackard_Analysis
## Overview of Project

### Purpose
The purpose of this analysis was to determine the number of retiring employees per title (based on age) and identify employees eligible to participate in a mentorship program (also by age). This information will be used to generate insights about the upcoming "silver tsunami" of retirements, and help Pewlett Hackard prepare. 

### Resources
- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv (all available in the [Resources folder](https://github.com/baileyvo/Pewlett_Hackard_Analysis/tree/main/Data))
- Software: pgAdmin4 6.1, Visual Studio Code 1.63.2

## Results
### Tables from which Insights Were Drawn
![Retiring Titles](https://github.com/baileyvo/Pewlett_Hackard_Analysis/blob/main/Retiring_Titles.PNG)

![Mentorship Eligibility](https://github.com/baileyvo/Pewlett_Hackard_Analysis/blob/main/Mentorship_Eligibility.PNG)- this image shows only the first ten rows to demonstrate the data generated.

### Insights
Four insights can be drawn from the analysis:
- There are 72,428 employees approaching retirement, and presumably that many roles will need to be filled once those staff members have retired.
- Senior Engineers (25,916) and Senior Staff (24,926) represent the titles with the most staff coming up on retirement.
- Managers, with only 2 employees coming up on retirement, do not represent a large threat in the silver tsunami.
- Although the range defined for membership eligibility was narrow, representing only one birth year worth of employees, it is worrying that only 1,549 employees are eligible.

## Summary
After this analysis, there are two major questions to ask:
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Assuming all retiring employees need to be replaced, there are 72,428 roles that will need to be filled as the "silver tsunami" begins to make an impact.
- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
With only 1,549 employees identified in the membership eligibility group, there are not enough to mentor the next generation of Pewlett Hackard employees.

### Further Analysis
There are two additional queries that may provide more insight:
- Dividing the retiring employees by department, so it could be seen which departments need to be most worried about upcoming retirements.
- Identifying the job titles of the mentorship eligibility group, so they could be paired with retiring employees of the same title. 
