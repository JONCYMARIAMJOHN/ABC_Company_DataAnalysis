# ABC_Company_DataAnalysis
The project is for analyzing a dataset from ABC company and generating a comprehensive report detailing information about their employees across various teams.

## Overview
The dataset consists of 458 rows and 9 columns, which includes employee name, team, number, position, age, height, weight, college and salary. Employee name can be considered as the index, which is to identify each data. 

## Data Preprocessing
Corrected the "height" column by replacing it with random numbers between 150 and 180
Also checked dataset information, null values, duplicated values, description etc.
Most of the columns have non-null values except College and Salary
College have 84 null values ans salary have 11.
No duplicate rows are there in the dataset.

## Data Analysis
#### Distribution of employees accross team
Evaluated the no. of employees on each team 
Insights :
'New Orleans Pelicans' has highest no.of employees which is 19
'Memphis Grizzlies' has 18 employees
Then 3 teams includes 16 employees, 2 includes 14 employees and the rest have 15 employees.
So the percentage split is higher for 'New Orleans Pelicans ' which is 4.148472

#### Employees seggregation based on position
Found count of employees in each position
Insights :
102 employees have the position 'SG', which is the highest count
100 employee are 'PF'
Employees with 'C' position are lesser in the company. Only 79 employees

#### Predominant age group
Evaluated the predominant age group in the company by creating a new dataframe for age group by applying cut() function on the existing dataframe
Insights : 
Employees in the range 20-29 age are more in the company, there are 334 emplyees in the range
119 employees are in the range 30-39
Only 3 are in range 40-49 and noone are there who are 50 or above.

#### Salary expenditure
Total salary expenditure was calculated team wise and position wise
Insights :
Team having highest salary expenditure is 'Cleveland Cavaliers', which is 72902950 and lowest is 'Washington Wizards' which is 76328636.
Position having highest salary expenditure is 'C', which is 466377332 and lowest is 'SG', which is 396976258

#### Age and salary correlation
THe correaltion between age and salary is 0.214
Insights :
As the correlation coeffictient is a postive value, there is a relationship between age and salary of employees
Means aged employees are having higher salary compared to youngér ones.

## Conclusion
The given dataset is a clean information about the employees in ABC company. The above insights can be used to identify the trends and be used for companies development.

