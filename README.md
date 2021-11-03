# Pewlett-Hackard-Analysis
## Overview of the Analysis: 
### Background: 
Pewlett Hackard is a large company boasting several thousand employees and it’s been around for a long time. Pewlett Hachard is looking toward the future in two ways: first, it’s offering a retirement package for those who meet certain criteria. The second way, its starting to think about which positions will need to be filled in near future. The number of upcoming retirements will leave thousand of job openings. What would happen to the company if they didn’t look a head and prepare for these many vacancies? The company decided to perform employee research to find the answer to this question.
### The Purpose:
The purpose of this project is to determine the number of retiring employee [Data](https://github.com/intisarkhalil/Pewlett-Hackard-Analysis.git) per title and identify employees who are eligible to participate in a mentorship program. The employee data available is six csv files because Pewlett Hackard has been used EXCEL and VBA to work with their data. But now they decide to use SQL.  In this analysis we will write a **SQL** query using **PostgreSQL** server and **pgAdmin** interface.
The relationships between the six csv data files were designed the following ERD. We use **SQL** tools and function to: 
- Create new tables with the ```INTO``` statement
- Export a table as a ```CSV``` file
- Filter queries with the ```WHERE``` clause
- Use the ```INNER JOIN``` clause to join two tables on a similar column
- Use the ```ON ()``` clause
- Use an alias instead of a full table name
- Use the ```ORDER BY``` clause.
- Use ```DISTINCT``` to retrieve a single row defined by the ```ON ()``` clause. The row that is returned is specified by the ```ORDER BY``` clause.

 ![image](https://user-images.githubusercontent.com/62036983/140103767-80f8d404-cf6a-429c-b5ff-11cabd8e3be9.png)

## Results: 
### The Number of Retiring Employees by Title
- The following image shows the Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. 

![image](https://user-images.githubusercontent.com/62036983/140103848-e0195ae8-ea5b-4d74-a705-fba0df63c3cf.png)

- The following image show the unique titles table that the retirement title after we remove the duplicate entries for some employees because they have switched titles over the years.

![image](https://user-images.githubusercontent.com/62036983/140103892-1db07b8b-c81f-4b61-a5ad-3a28ad44c843.png)

- The following image Retiring Titles table that has the number of retirement employees by most recent job title.

![image](https://user-images.githubusercontent.com/62036983/140103978-b3f2e87f-5812-47f0-b071-d53782cbd65e.png)

### The Employees Eligible for the Mentorship Program
The following image show the mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

 ![image](https://user-images.githubusercontent.com/62036983/140104060-826d4cfb-cae0-494f-9fc3-0131cc0e4ab6.png)

## Summary: 
Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?

![image](https://user-images.githubusercontent.com/62036983/140104144-7f473d38-e92f-4070-9050-7d6730fd7414.png)
 
90,398 roles are in urgent need to be filled out as soon as the workforce starts retiring at any given time.

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
 
![image](https://user-images.githubusercontent.com/62036983/140104235-8de4b7eb-9ec8-47f7-bfa4-3ac6b35cce08.png)
 
No, there are only 1,549 employees eligible to participate in the mentorship program, and this number is not enough compared to the estimated total number of new employees (90,398).

 ![image](https://user-images.githubusercontent.com/62036983/140104283-34628275-7a02-4dc9-9aed-fbc280087082.png)




