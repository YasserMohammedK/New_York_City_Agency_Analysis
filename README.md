
## New York City Agency Analysis
This dataset contains the salary, pay rate, and total compensation of every New York City employee. In this dataset this information is provided for the 2014, 2015, 2016, and 2017 fiscal years, and provides a transparent lens into who gets paid how much and for what.


## Contents

-[Problem Statement](#Problem_Statement)

-[Data Description](#Data_Description) 

-[Tools](#Tools)

-[Algorithms](#Algorithms)

-[Installation](#Installation)

-[Questions](#Questions)

-[MVP](#MVP)

-[Dataset Resource](#Dataset_Resource)

-[Author](#Author) 

![Logo](https://cdn.luxatic.com/wp-content/uploads/2021/02/Best-Modeling-Agencies-In-NYC.jpg)


## Problem_Statement
This data enables the governmental financial authority to control the granting of investment loans and the ability to conduct a review of capital projects to benefit from the financing of bond proceeds.

### Data_Description

Dataset: Salaries paid to New York City employees over four years

It has 2,194,488 rows , 16 columns.

| Field Name        | Description| Type|  
| ------------- |:-------------:|:------------:|
| Fiscal_Year      | Is a one-year period of time that a company or government uses for accounting purposes and preparation of its financial statements | Int | 
| Agency_Name      | Recruitment agency names      | Object  |
| Last_Name | The employee's last name      |Object |
| First_Name    | The employee's first name |Object |
| Agency_Start_Date       | Start date of each agency |Object |
| Work_Location   | Work Location of each agency |Object |
| Title_Description       | Job title |Object |
| Leave_Status_as_of_June_30      | Vacation status | Object|
| Base_Salary  |  Basic salary without allowances  | Object |
| Pay_Basis  |  The principal condition in terms of time, production, or other criteria that, along with salary rate, determines the compensation paid to an employee  | Object|
| Regular_Hours  |  All hours of work or paid leave except overtime hours  | Float|
| Regular_Gross_Paid  |  The total amount of money an employee receives before taxes and deductions are taken out   | Object|
| OT_Hours  |  Any hours worked by an employee that exceed their normally scheduled working hours  | Float |
| Total_OT_Paid  |  Money earned at an increased rate for working more than the usual number of hours in one week  | Object|
| Total_Other_Pay  |  The compensation and benefits that become payable under the Agreement or otherwise  | Object |

## Tools
Jupyter Notebook

Language: Python

Libraries: numpy, pandas, seaborn, Plotly

## Algorithms

machine learning: Linear Regression
## Installation

Run pip install command to install related packages.

```bash
!pip install numpy
!pip install pandas
!pip install seaborn
!pip install Plotly
```
    
## Questions
1. How many people do the various city agencies employ, and how much does each department spend on salary in total?

2. What are the most numerous job titles in civic government employment?

3. Where does overtime pay seem to be especially common? How much of it is there?

4. How do New York City employee salaries compare against salaries of city employees in Chicago? Is the difference more or less than the difference in cost of living between the two cities?
## MVP

The objective of the project is to know the financial expenditure and control the granting of loans and investment expenditures to the agencies.
 
## Dataset_Resource

https://www.kaggle.com/new-york-city/nyc-citywide-payroll-data
## Author

[@YasserMohammedK](https://github.com/YasserMohammedK) 

[@aamalsabr1](https://github.com/aamalsabr1)

[@Rahaf-t25](https://github.com/rahaf-t25)
