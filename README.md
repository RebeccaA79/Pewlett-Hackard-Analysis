# Pewlett-Hackard-Analysis

## Overview of the analysis

Pewlett-Hackard is about to experience a large-scale retirement. To better understand the impacts of the upcoming retirements and how to appropriately plan for hiring new staff, Management has requested an analysis to determine:

 1. the number of employees retiring by title and

 2. The employees who are eligible to participate in a mentorship program. 

Note, the mentoring program will be structured to allow eligible retirees born in 1965 (between Jan 1 and December 31), to step into a part-time role to train newly hired staff.


A series of sql queries and tables were generated off of existing HR csv files to help answer these questions. 
 
## Results

Based on the data analysis performed, the following :

   [Link to retirees by title csv file] (Data/retiring_titles.csv)
   
   [Link to employees eligible for the mentorship program csv file] (Data/mentorship_eligibilty.csv)

1. There are 72,458 employees eligible for retirement. The breakdown by title is as follows:

   ![Number of retirees by title](Data/# of retirees by title.png)
    
2. The Senior Engineer and Senior Staff titles make up the largest percentage of eligible retirees (approximately 70% combined). Management should consider placing the biggest focus on this population through a combination of hiring and employee retention, where possible.

3. There are 1,549 employees eligible for the mentorship program. 

   ![Number of employees eligible for mentorship][Data/Employees eligible for mentorship program.png]

4. Of the 1,549 eligible for the mentorship program, statistics on two largest retiree groups noted in item 2 above are as follows:

   - Senior Staff make up the largest group eligible for the mentorship program , 417 employees (appropriately 27%).
   
   - Senior Engineers have 298 employees (approximately 19%) eligible for the mentorship program. 

## Summary

Utilizing the results above, two additional queries were generated to address the following questions:
 

 - How many roles will need to be filled as the "silver tsunami" begins to make an impact?

 - Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
