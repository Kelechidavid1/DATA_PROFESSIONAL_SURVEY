# DATA PROFESSIONAL SURVEY
This project is a survey of data professionals on Linkedin, X and other social media accounts and the aim of this project is to perform Exploatory Data Analysis (EDA) on the information obtained from different data professionals. Here is the link to the dataset used: [A Data breakdown of Data Professionals](https://github.com/AlexTheAnalyst/Power-BI)  

## DATA COLLECTION AND SKILLS USED  
The data contains information of data professionals such as their demographics, roles, salary range in dollars, favourite programming language, as well as other questions that aims to quantify how happy they are with their current jobs. The survey was posted on Linkedin and X where 630 data professionals responded to. The data was loaded into Power Query and cleaned before it was exported to Power BI for onward visualization.    
**STEPS IN DATA CLEANING USING POWER QUERY**  
-Imported from Excel and loaded to the Power Query Editor.  

-Column from browser to referral were deleted from the dataset table as they served no purpose for my analysis.  

-The column "which tittle best fits your current role", "which country do you live in" and "what industry do you work im" was cleaned by splitting the column by a delimeter and grouping all other responses as "others". The new colon is now deleted.  

-Also, the column "Favorite Programming Language" was splitted by column using the colon delimeter and grouping all other responses as "others". The new colon is now deleted.  

-For the column with the current salary, the average for the ranges of the salary were taken after splitting the column for the current yearly salary. The new column was then renamed to "Average Salary".  

**VISUALIZATION USING POWER BI**  

## DATA ANALYSIS AND FINDINGS  
![DATA PROFESSIONAL DASHBOARD](https://github.com/user-attachments/assets/b8215171-f66c-45ed-95d5-03eda2b0d82c)  

1. *Demographics of Survey Takers*  
Total survey responses: 630 people participated.
Average age: 29.87 years, suggesting most participants are early to mid-career professionals.
Country distribution: The United States dominates the survey responses, followed by India, the UK, and Canada.
2. *Salary Trends*
Highest-paying job title: Data Scientist earns the highest average salary, followed by Data Engineer and Data Architect.
Lowest-paying roles: Database Administrator and Student/Intern roles have the lowest average salaries.
Gender salary comparison: The pie chart on "Average Salary by Sex" suggests a gender pay disparity, with males earning a larger portion of the total salaries.
3. *Work Satisfaction*
Happiness with Work-Life Balance: 5.74/10, indicating moderate satisfaction but potential room for improvement.
Happiness with Salary: 4.27/10, suggesting that many data professionals are dissatisfied with their pay.
4. *Programming Language Preferences*
Python is the most popular programming language, significantly ahead of others like R, C/C++, JavaScript, and Java.
## DISCUSSION AND INTERPRETATION
-Data science roles pay the highest, making them attractive career choices.  
-Salary dissatisfaction is notable, which may indicate a demand for better compensation in the industry.  
-Python dominates programming choices, reinforcing its importance for data professionals.  
-Work-life balance is moderately rated, but improvements may be needed.  

## CONCLUSION AND RECOMMENDATIONS  
The dashboard reveals that data science roles offer the highest salaries, but salary dissatisfaction remains high among professionals. Python is the dominant programming language, and work-life balance satisfaction is moderate. While the majority of survey respondents are young professionals, there are potential gender pay disparities. These insights suggest a need for better compensation structures and work-life balance improvements in the data industry.

