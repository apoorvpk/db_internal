# databricks internal project

We need to manage employees in bench

Approach
In this we have a survey form as a source wich we later converted in the csv file format. This csv data either we can upload adls location. then adls location to databricks. Databricks location we will do transformation and filtering of the data.And finally, we use visualization tool like powerbi on the final refined data present in databricks notebook. 

filtered and transform based on below logic:

1.Daily salary ->from montly salary
2.find the bench date  
3.Number of days since on bench
4.maximum salary of employees who are sitting on bench. i.e. Daily salary * ( Number of days since on bench - number of leaves taken) 

#Overdue of certification -> email alerts to whome not completed certification. 

#Bar chart pie chart to show employees activity.

From adls to databricks two options:
1. Mounting of adls 
2. Unity catalog

we will place event trigger too between adls and databricks
