# Pewlett-Hackard-Analysis

Used PgAdmin 4 v6

# Overview

There were several things we were set out to accomplish in this project. We initially had to determine the number of retiring employees and their title. Then we used this to determine who was eligible to participate in the Pewlette-Hackard mentorship program. Using SQL software we sorted the employees born between January 1, 1952 - December, 31 1955. We used the emp_no and title table to retreive the title, from_date, and to_date columns and created a new table using a primary key and sorting by birth_date.

## Delivery 1

A new unique_titles was created inorder to find the find the first occourance of emp_no using the DISTINCT ON function. After that we did an ORDER BY COUNT function to retreive the total number of employees under each title from the unique_titles table we had to create.

## Delivery 2

We were required to find eligable employees for a mentorship program out the retiree pool we created earlier. We used another DISTINCT ON function to retreive the first occurance of the employee for each set of rows defined by our On() clause.

# Results

  - We found the count of every employee that is near retirement and what positions they work at "title" in the Pewlett-Hackard company we put that information into the retirement_titles table snippet below:
  
  ![image](https://user-images.githubusercontent.com/96445453/154882008-b434647e-3041-4abc-963d-4f8b0dd3cecd.png)

  - In the unique_titles table we dropped the from_date and to_date in order to clean up the data:
  
  ![image](https://user-images.githubusercontent.com/96445453/154882259-a5873ae5-942f-4e26-b002-b0a0880551d8.png)

  - In the retiring_titles table we got the overall count of each position that people are retiring from. From this data we can see there is a large amount of Senior titles 57,668/90398, nearly 64% :
  
  ![image](https://user-images.githubusercontent.com/96445453/154882360-0259bdff-4f8d-4da7-b445-5e93efa169d3.png)

  - The membership_eligibility table below gives a list of all personel that are good candidates to mentor younger employees inorder to replace themselves without an interuption to company productivity:

![image](https://user-images.githubusercontent.com/96445453/154883060-9190e221-2fde-4910-a29a-26d68536877f.png)

# Summary

With the "Silver Tsunami" coming to Pewlett-Hackard over 130000 employees will be eligible for retirement according to the retirement_titles table with over 90000 of those being unique titles. There are a great many positions therefor that will greately benefit from a mentorship program and it will need to be implemented as soon as possible  in order to minimize holes in the workforce.

With the mentor_eligibility table we can see that there are nearly 50000 employees that are capable of mentoring new employees. If they each mentor two new employees they will be able to fill the gaps needed inorder to continue business as usual when the Senior staff retires.





