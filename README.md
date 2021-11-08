# Pewlett-Hackard-Analysis

## Overview of the analysis
Pewlett-Hsckard is a big company with a diversity of databases stored. They have several databases containing information about their employees. Since there´s no order on these employee´s databases we were told to give it one. The main purpose is to analyze and determine the amount of employees that are about to retire, or can do so now. Most, or all of them were born between 1952 to 1955.  
Like said before the information was not on a single table. We needed the name, their employee number and date of birth. We retrieved this information and joined the tables we needed. We filtered the information to their year and used the **COUNT** function to know how many are eligible to retire. Finally with this information we created the tables with the results which are in the "results" section.
## Results

### Retirement titles
- The first table we created was the retirement_titles table. Why? So we can get the employees "age in the company". As you can see in the following table:  
![retirement_titles](https://github.com/ManuelRuizF/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles_table.PNG)

### Unique Titles
- Oh no! There´s people that have been sooooo long that they appear more than once in the data, just with different titles. So what we did is that we sorted the data and created the unique table. Please consider the following table:  
![unique](https://github.com/ManuelRuizF/Pewlett-Hackard-Analysis/blob/main/Data/unique_titles_table.PNG)

### Retiring Titles
- As a Data Scientist we don´t just only sort data, we analyze it. What can we infer from this information. We created the retiring titles table to learn more about the retiring employees and their roles. As you can see in the following tables, most of the retiring candidates have senior roles inside Pewlett Hackard. It seems that a lot of people will get a promotion!  
- Please consider the following retiring titles table:
- ![retiring_table](https://github.com/ManuelRuizF/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles_table.PNG)  

### Mentorship Elegibility
- As final table we have the mentorship elegibility table. Since there will be new vacant roles, we need to know who can have a mentorship before getting a better role. We filtered the people that are from the year 1965. Consider the following table:  
- ![mentor_table](https://github.com/ManuelRuizF/Pewlett-Hackard-Analysis/blob/main/Data/mentor_table.PNG)


## Summary
We export every table created to csv files. To prior analyzing.
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- About ~55,000~
- More than 50% of them company will be either in mentorship or is eligible to retire. So the company must hire.
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Not enough, there are more people leaving that ones that can receive a mentorship. Pewlett Hackard must hire!
