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
