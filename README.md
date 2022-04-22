# Pewlett-Hackard-Analysis

Pewlett Hackard Analysis


Part 1 – Overview of Analysis

The main goal of this analysis is to determine the number of retiring employees by title, while also identifying which employees are eligible for Pewlett Hackard’s mentorship program. Our retiring employees by title information displays the titles of all employees born between January, 1 1952 and December, 31 1955. 
Initially, a query was created that retrieved the emp_no, first_name and last_name columns from the employees table. That same table retrieved the title, from_date, and to_date columns of the titles table in the Pewlett Hackard query. The tables were joined using the primary key, filtered by birth_date, and the resulting information was placed into a new table. 
Next, the unique_titles table was generated to find the first occurrence of the emp_no in our new table by using the DISTINCT ON function. Following that step, the ORDER BY COUNT function was used to exhibit the total number of each title (from our unique_titles table). I then composed a query that retrieved columns from our employees and dept_emp table, filtered data on current employees born in 1965 then ordered the table by emp_no.
Part 2 – Results & Findings
•	The retirment_titles table shows every employee eligible for retirement, and how long they have worked at each position over the course of their career.
•	The unique titles table depicts the most recent title for employees of retirement age.
•	Our retiring_titles shows us the a majority of the employees of retirement age (57,668/90,398 = 64%) have senior titles.
 


•	The final portion of the analysis shows mentorship eligibility. Referring to the image below, it’s evident that most of these employees have senior titles.
 
Part 3 – Conclusion

Seeing as though 63 % of the workforce is either retirement or mentorship eligible, there will be many positions to fill over the next 5-10 years. A point of concern is that there may not be enough people in the workforce to fulfill those roles. It would behoove companies to learn about what their current employees have done to warrant such a lengthy, successful career. This will allow them to create development pathways to build future employees. There is a great chance that the future generations will be much more technology savvy and efficient due to tech being a key component of their upbringing. This aspect will help companies continue to trend in the right direction by keeping bottom line elevated.

