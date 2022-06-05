# Salary-Prediction
This is a take home assignment for the ML Engineer position at Indeed.

## The business question

** Being a job search engine, it’s helpful if Indeed can suggest an approximate salary to job seekers for a given job post. Your first task as an Indeed Data Scientist is to develop a salary prediction system.**

**The goal:** Provide estimated salaries for a new job posting.

<ins>**How does this help Indeed Flex?**<ins>
* A user of the job search engine is able to get an approximate salary for a job they are seeking. 
* Indeed Flex can use the system to determine the most searched jobs. 

## Solution

Using the data provided, I build a salary prediction model that is able to provide approximate salaries for job seekers based on their education level, industry, major and proximity to a metropolitan area. 

8 models are tested on the transformed dataset, where categorical features are one hot encoded, and 2 models are tested on the dataset without transforming categorical features. Root Mean Squared Error is used as an evaluation metric. 

Please find detailed analysis on this [**notebook**](link). A summary presentation is also [**available**](). 


