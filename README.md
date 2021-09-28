# predicting-employee-absenteeism

## This is an Udemy project.
Cource Name - [The Business Intelligence Analyst Course](https://www.udemy.com/course/the-business-intelligence-analyst-course-2018/).

## Problem :
Absenteeism of employees during work time due to various factors.

## Goal of this Analysis :
weather or not an employee can be expected to be missing for a specific number of hours in a givin work day.

###### Preprocessing and cleaning of data done in jupyter notebook.
- Python version used : 3.9
- library used : Pandas & numpy.

**module already provided by Udemy**

###### technique used in model :
## Logistic Regression

- dependent variable : Absenteeism Time in Hours.
- Indedependent variables : Reason for Absence, Date, Transportation Expense, Distance to Work, Age, Daily Work Load Average, Body Mass Index, Education, Children, Pets.
- Reason of absence further dummied into 4 groups( reason1, reason2, reason3, reaso4): reason 0 removed due to multicolliniarity.
- Extracted month and days of week.
- Rest of the data is same and further model through ML.

Absenteeism model is furhter visually analysed in my [tableau public profile](https://public.tableau.com/app/profile/vijit.singh8031/viz/Employeeabsenteeismprediction/EmployeeAbsenteeismPrediction).

Data source : Udemy
