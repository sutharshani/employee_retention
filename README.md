# Employee Retention Issue – a Predictive Analysis

Employee attrition or turnover occurs when an employee leaves the organization.
It is different from employee discharge, termination, resignation, and abandonment.
In the case of employee attrition, when the employee leaves the company, employee position remains unfilled.
In the case of turnover, the position is filled by a replacement employee.

[Link to GitHub](https://github.com/sutharshani/employee_retention)

# Table of Contents
1. [Introduction](#introduction)
2. [Data Background](#data-background)
3. [Prerequisite](#prerequisite)
4. [Project Status](#project-status) 
5. [Methods Used](#method-used)
6. [Versioning](#versioning)
7. [Authors](#authors)
8. [Acknowledgement](#acknowledgement)
9. [Reference](#reference)

## Introduction
Here I will discuss how we can build a model that can help HR in identifying employees that can leave the organization
so that they can work with employees and take corrective measures to reduce the attrition problem related to employees
leaving the organization. In Data Science world to deal with this issue the term used is *Employee churn analytics*
which is the process of assessing your staff turnover rates in an attempt to predict the future and reduce employee churn.

It usually cost an average of 20% of the employee’s annual salary because of  employee turnover for a mid-range position.
> **For example:** It will cost about $7,000 to replace an employee who is getting paid $35,000.

The Center for American Progress found in their study that turnover can cost estimated price of 100% to 300% of
the base salary of the replaced employee, wages and role of an employee. 

In this predictive analysis, I will research the dataset to find a solution for the below:
* What causes the employee attrition ?
* Is there any way to predict the likelihood of an active employee leaving the company ?
* Can we identify key indicators to understand why an employee can leaving the company?

[back to top](#table-of-contents)

## Data Background
For this project, I am using dataset from Kaggle that is present at below URL:

https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset.

Features present in the dataset are:
1. 'Age',
1. ‘Attrition’
1. 'BusinessTravel'
1. 'DailyRate'
1. 'Department'
1.	'DistanceFromHome'
1. 'Education'
1.	'EducationField'
1.	'EmployeeCount'
1.	'EmployeeNumber'
1.	'EnvironmentSatisfaction'
1.	'Gender'
1.	'HourlyRate'
1.	'JobInvolvement'
1.	'JobLevel'
1.	'JobRole'
1.	'JobSatisfaction'
1.	'MaritalStatus
1.	 'MonthlyIncome'
1.	'MonthlyRate'
1.	'NumCompaniesWorked'
1.	'Over18'
1.	'OverTime'
1.	'PercentSalaryHike'
1.	'PerformanceRating'
1.	'RelationshipSatisfaction'
1.	'StandardHours'
1.	'StockOptionLevel'
1.	'TotalWorkingYears'
1.	'TrainingTimesLastYear'
1.	'WorkLifeBalance'
1.	'YearsAtCompany'
1.	'YearsInCurrentRole'
1.	'YearsSinceLastPromotion'
1.	'YearsWithCurrManager'

In this case study, I am trying to solve employee churn issue and feature attrition looks like the feature is most interesting,
and this will be the target variable. This tells about whether attrition happened or not.
So, the target variable will be *Attrition*, and the remaining features will be input attributes which will help us find the target attribute.

[back to top](#table-of-contents)
## Prerequisite
You will need the following applications to execute this project-

* Python 3 (or Anaconda distribution with Python 3)
* Jupyter or any other notebook

[back to top](#table-of-contents)
## Project Status
Work in progress. I will be uploading more details soon. 

[back to top](#table-of-contents)

## Method Used
For this I will be performing classification and regression methods to build a model to understand which method works
best and I will use that as my final model for this project.
* *Classification*: I will use historical data with predefined target variables AKA labels (churner/non-churner) to train
  an algorithm. With classification, we can answer the employee churn or not.
* *Regression*: I will use it to estimate the relationship between a target variable and other data values that influence
  the target variable. Regression analysis allows estimating how many variables in data influence the target variable.

**Potential Issues?**
There are below challenges I will face while working on this analysis.
* There is no single churn methodology that is proven to work in most situations; either machine learning models or
  survival regression could be appropriate based on the application.
* A churn model is only as good as the features going into it. I may face some roadblocks like target leakage,
  unavailable or missing information. I might need for optimal feature transformations.
* When estimating model accuracy, it's important to choose the correct metric to optimize, and the right validation
  dataset to train the model on.
  

[back to top](#table-of-contents)

## Versioning
Git is used for project versioning. 

[back to top](#table-of-contents)

## Authors
Shani Kumar 

[back to top](#table-of-contents)

## Acknowledgement
Based on the model's prediction HR will be able to understand about employees at risk of leaving the company. Also,
from the associated key factors analysis, they will be able to understand why certain employee is at risk and what
changes they can do that might reduce the risk and employee will remain with the company. \
[back to top](#table-of-contents)

## Reference

[back to top](#table-of-contents)
