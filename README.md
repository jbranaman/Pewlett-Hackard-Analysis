# Pewlett Hackard Analysis
## Overview of Project
This is an employee analysis preparing for the impending retirement of employees.
### Purpose
This report determines the number of retiring employees by title and identifies employees who are eligible to participate in a mentorship program.

## Results
* Data was queried to display employees names with a birth date between the beginning of 1952 and the end of 1955 with their employee number and titles. However, the data displayed repeat entries of employees because the employees had multiple titles over the years and the data repeated for each title as can be seen below.
<img width="690" alt="Retirement Titles Data Query" src="https://user-images.githubusercontent.com/96451672/154732751-613ae05a-1674-4549-b000-b0b490fb16ee.png">

* It was necessary to filter out the duplicate employee entries by not including entries that had an employment 'to_date' in the past therefore displaying employees with their current title.
<img width="532" alt="Unique Titles Data Query" src="https://user-images.githubusercontent.com/96451672/154733482-a97b8c28-4252-4ef5-81b0-23bdb7afd315.png">

* With the titles now being narrowed down, the data on employee titles could be consolidated into a table from a query that counted the number of unique titles. The results show that the vast majority of those retiring are in senior roles.
<img width="253" alt="Retiring Titles Data Query" src="https://user-images.githubusercontent.com/96451672/154734972-7bcb20c9-7e4c-471a-a783-e974a71c9cc8.png">

* Data was queried to determine those eligible for the mentorship program based on their birth date displaying only those still at the company.
<img width="789" alt="Mentorship Eligibility Data Query" src="https://user-images.githubusercontent.com/96451672/154737324-1abb52f2-e0be-4d4e-b662-83dc496a3b19.png">

## Summary

After querying the number of unique titles of those eligible for the mentorship program, the majority of those eligible are in 'Senior Staff' (570 employees) and 'Engineer' (502 employees) roles. It can also be noted that those eligible for the mentorship program generally have the same amount of experience at the company as those retiring as their hire dates fall in the same range. It can be concluded that a large amount of hiring into senior roles needs to occur as soon as possible to add more employees to replace those retiring rather than solely relying on other younger tenured employees to replace them.
