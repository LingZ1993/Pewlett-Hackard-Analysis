# Pewlett-Hackard-Analysis

## Overview of the Analysis
The purpose of this analysis is to analyze large sets of data using postgresql, to check and see how many employees are eligible to retire, and to avoid duplicate data we need to use the 'DISTINCT ON' statement to modify the querie, and then we count how many employees are eligible for retirement group by each specific title. this way we are making data very easy to read and understand, using postgre we can achieve so many different assignments. 

## Results
1. In retirement_titles.csv files gives us all of the information and show us the list of employees are eligible to retire and their information, title, first and last name and also their hire date and end of hire date; 
2. But since the csv file contains duplicate data showing that some employees have more than 1 title, so we want to limit the number of title to only one, so we create 'unique_titles.csv' file, we can see that each name only have one unique emp_no. 
3. After we get unique titles for employees that are eligible to retire, we want to show people how many people for each title are eligible to retire, so that way it is easier to get an idea on how many people for each title, so in 'retiring_titles.csv' file we can see the numbers for each specific title. 
