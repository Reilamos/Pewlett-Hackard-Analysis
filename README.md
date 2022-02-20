# Pewlett-Hackard-Analysis

Used PgAdmin 4 v6

# Overview

There were several things we were set out to accomplish in this project. We initially had to determine the number of retiring employees and their title. Then we used this to determine who was eligible to participate in the Pewlette-Hackard mentorship program.

Using SQL software we sorted the employees born between January 1, 1952 - December, 31 1955. We used the emp_no and title table to retreive the title, from_date, and to_date columns and created a new table using a primary key and sorting by birth_date. 

For Deliverable 1 a new unique_titles was created inorder to find the find the first occourance of emp_no using the DISTINCT ON function. After that we did an ORDER BY COUNT function to retreive the total number of employees under each title from the unique_titles table we had to create.
