# Pewlett-Hackard-Analysis
The project's goal is to plan an ERD that will apply to the data, design and use a SQL database, import and export large CSV datasets into pgAdmin, 
prepare using different joins to create new tables in pgAdmin, and finally write basic-to intermediate-level SQL statements.

## Overview of the analysis: 
The project's deliverables are;

	1- The Number of Retiring Employees by Title
	2- The Employees Eligible for the Mentorship Program

## Results: 
First, the number of retiring employees by title was created with the inner join function using the table of employees, titles, and the created ERD as a reference. 
It was created the Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952, and December 31, 1955. Then, for removing duplicate rows that was using the DISTINCT ON statement to create a table that contains the most recent title of each employee due to some employees 
might have multiple titles in the database -for instance, the promotions. Finally, it was used the COUNT function for the final table which has the number of retirement-age employees by most recent job title. 

Second, the Employees Eligible for the Mentorship Program table holds the current employees who were born between January 1, 1965 and December 31, 1965. 

ERD Schema which shows the relationship between the tables to build queries.

<p align="center"><img src="https://github.com/zkirsan/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png"></img></p>

## Summary: 
Human Resources (HR) at Pewlett-Hackard is planning for a "silver tsunami" when more existing staff hit retirement age, 
but they are uncertain how many or in which divisions they will serve. With a quick query shows that 90,398 current employee who are eligible for retirement 
(See the retiring_titles.csv file).

<p align="center"><img src="https://github.com/zkirsan/Pewlett-Hackard-Analysis/blob/main/Retiring_Titles.PNG"></img></p>

Given these forthcoming retirements, HR is planning a mentorship scheme to assist prospective mentees and still gaining a greater understanding of which staff 
will be suitable candidates for mentoring. According to the question, there are 1,940 existing workers that are qualified to be mentors based on their requirements.
 
The table of the Mentorship Eligibilty (See also the mentorship_eligibility.csv file)

<p align="center"><img src="https://github.com/zkirsan/Pewlett-Hackard-Analysis/blob/main/Mentorship_Eligibilty.PNG"></img></p>




