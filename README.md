# Analysis of Data Science Professionals' Salaries in 2023
![](salaries.PNG)
---

# Introduction:
In this project, I will be conducting a comprehensive exploratory data analysis and visualization of the dataset to uncover hidden patterns, relationships, and insights that can inform salary negotiations and career decisions in the field of data science.

### Concepts Applied:
1.	Data cleaning
2.	Descriptive statistics
3. EDA
4.	Hypothesis Testing

# Data Sourcing
The dataset was downloaded from kaggle [here](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023). 

It contains 11 columns, each are:
- work_year: The year the salary was paid.
- experience_level: The experience level in the job during the year
- employment_type: The type of employment for the role
- job_title: The role worked in during the year.
- salary: The total gross salary amount paid.
- salary_currency: The currency of the salary paid as an ISO 4217 currency code.
- salaryinusd: The salary in USD
- employee_residence: Employee's primary country of residence in during the work year as an ISO 3166 country code.
- remote_ratio: The overall amount of work done remotely
- company_location: The country of the employer's main office or contracting branch
- company_size: The median number of people that worked for the company during the year

# Problem statement 
1. What are Top 10 Data science job titles in 2023?
2.	Which data science Job titles earn the top salaries?
3.	Which is the top experience level of data scientists in 2023?
4.	What types of employment arrangements are common in this field?
5.  What year has Data Scientists earned the highest?
8.	Where are the top remote jobs locations?

# Data Cleaning
   Cleaned data            |     Raw data
   :----------------------:|:---------------:
   ![](Overview_after.PNG) | ![](Overview_before.PNG)
   
   ##### Tasks carried out are:-
- Made the first row as header and capitalizing the first word for easy readability
- I changed data type from General to **Text**, **Currency** and **Number** where applicable
- I standardized abbreviations using Find/Replace 
- filtered the data to meet certain conditions and checked for blanks

# Data Analysis and Visualization
 Top data science job titles in 2023           |    Data science job titles earning top salaries
   :----------------------:|:---------------:
   ![](Job_titles.PNG) | ![](AvgSalaries.PNG)
   #### Insights:
   1. In terms of job titles, data engineers have the highest position, with data scientists following closely behind.
   2. As anticipated, employees at the executive level typically receive higher average salaries. Additionally, the profession of cloud data architect has become the second highest paid due to the increasing prevalence of cloud computing.
  ---
  
   Experience level of data scientists in 2023   |     Common types of employment arrangements in Data science 
   :-----------------------------------------:|:-----------------------:
   ![](Experience_level.PNG)                    | ![](NumberEploymentType.PNG)
   
   #### Insights:
    1. The data shows that senior-level positions have the highest count accounting for 67% of the whole , then followed by mid-level positions, while executive-level positions are comparatively fewer.
    2. The data indicates that a significant number of individuals are employed on a full-time basis, with the majority of them holding senior positions. Furthermore, it appears that freelancing has become less common in recent times.
    ---
   
   ![](SalaryperYear.PNG)   
   #### Insights:
   1. The data clearly shows that the average salary for data-driven jobs has been on the rise every year, with a notably significant increase observed between 2021 and 2022. This trend highlights the escalating need for qualified and competent professionals in this field.
  
   



