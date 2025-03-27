# Tableau_HR_Project
This was an example project that was taken from the YouTube channel, Data with Baraa, and it's called Complete HR Tableau Project End-to-End | Like I Do in My Real Projects (https://www.youtube.com/watch?v=UcGF09Awm4Y)

As the new data analyst, I have to provide the information that the HR manager wants. The HR manager wants a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis

## Overall Thought Process Using The Data
1) Constructing The Data Source
- Collect the data
- Connect the data
- Check the data quality
- Check the data types
- Understand & explore the data
  
2) Building Charts
- Analyze requirements and choose chart
- Initial format of sheet
- Create calculated fields and test
- Build chart
- Format chart
  
3) Building Dashboards
- Plan the dashboard (dashboard mockup and container mockup)
- Create container structure
- Putting everything together
- Fixing colors
- Fix texts
- Refine charts
- Fix spacing (inner and outer spacing)
- Fix tooltips
- Add filters and legends
- Add logos and icons

## Summary View
The summary view should be divided into three main sections: Overview, Demographics, and Income Analysis

## Overview
The Overview section should provide a snapshot of the overall HR metrics, including:
- Display the total number of hired employees, active employees, and terminated employees.
- Visualize the total number of hired and terminated employees over the years.
- Present a breakdown of total employees by department and job titles.
- Compare total employees between headquarters (HQ) and branches (New York is the HQ)
- Show the distribution of employees by city and state.

## Demographics
The Demographics section should offer insights into the composition of the workforce, including:
- Present the gender ratio in the company.
- Visualize the distribution of employees across age groups and education levels.
- Show the total number of employees within each age group.
- Show the total number of employees within each education level.
- Present the correlation between employees’s educational backgrounds and their performance ratings.

## Income
The income analysis section should focus on salary-related metrics, including:
- Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
- Present how the age correlate with the salary for employees in each department.

## Employee Records View
Provide a comprehensive list of all employees with necessary information such as name, department, position, gender, age, education, and salary.

Users should be able to filter the list based on any of the available columns.

## Data
The data seen in this project was sample data created by ChatGPT. Below are all of the attributes that you will see within the dataset. There is a total of about 8950 records for human resources.
- Employee ID: A unique identifier
- First Name: Randomly generated
- Last Name: Randomly generated
- Gender: Randomly chosen with a 46% probability for ‘Female’ and a 54% probability for ‘Male’
- State and City: Randomly assigned from a predefined list of states and their cities
- Hire Date: Randomly generated with custom probabilities for each year from 2015 to 2024
- Department: Randomly chosen from a list of departments with specified probabilities
- Job Title: Randomly selected based on the department, with specific probabilities for each job title within the department
- Education Level: Determined based on the job title, chosen from a predefined mapping of job titles to education levels
- Performance Rating: Randomly selected from ‘Excellent’, ‘Good’, ‘Satisfactory’, ‘Needs Improvement’ with specified probabilities
- Overtime: Randomly chosen with a 30% probability for ‘Yes’ and a 70% probability for ‘No’
- Salary: Generated based on the department and job title, within specific ranges
- Birth Date: Generated based on age group distribution and job title requirements, ensuring consistency with the hire date
- Termination Date: Assigned to a subset of employees (11.2% of the total) with specific probabilities for each year from 2015 to 2024, ensuring the termination date is at least 6 months after the hire date
- Adjusted Salary: Calculated based on gender, education level, and age, applying specific multipliers and increments
