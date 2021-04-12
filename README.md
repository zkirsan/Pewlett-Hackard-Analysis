# Pewlett-Hackard-Analysis
The project's goal is to plan an ERD that will apply to the data, design and use a SQL database, import and export large CSV datasets into pgAdmin, 
prepare using different joins to create new tables in pgAdmin, and finally write basic-to intermediate-level SQL statements.

## Overview of the analysis: 
The project's deliverables are;

	1- The Number of Retiring Employees by Title
	2- The Employees Eligible for the Mentorship Program

## Results: 
First, the number of retiring employees by title was created with the inner join function using the table of employees, titles, and the created ERD as a reference. 
It was created the Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952, and December 31, 1955.  
Then, for removing duplicate rows that was using the DISTINCT ON statement to create a table that contains the most recent title of each employee due to some employees 
might have multiple titles in the database -for instance, the promotions.  
Finally, it was used the COUNT function for the final table which has the number of retirement-age employees by most recent job title. 
Second, the Employees Eligible for the Mentorship Program table holds the current employees who were born between January 1, 1965 and December 31, 1965. 

ERD Schema which shows the relationship between the tables to build queries.

<p align="center"><img src="https://github.com/zkirsan/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png"></img></p>

## Summary: 
Human Resources (HR) at Pewlett-Hackard is planning for a "silver tsunami" when more existing staff hit retirement age, 
but they are uncertain how many or in which divisions they will serve. With a quick query shows that 90,398 current employee who are eligible for retirement 
(See the retiring_titles.csv file).

<p align="center"><img src="https://github.com/zkirsan/Pewlett-Hackard-Analysis/blob/main/Retiring_Titles.PNG"></img></p>


 

Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

