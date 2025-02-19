# DATA PROFESSIONAL SURVEY
This project is a survey of data professionals on Linkedin, X and other social media accounts and the aim of this project is to. Here is the link to the dataset used: [A Data breakdown of Data Professionals](https://github.com/AlexTheAnalyst/Power-BI)  

## DATA COLLECTION AND SKILLS USED  
The data contains information of data professionals such as their demographics, roles, salary range in dollars, favourite programming language, as well as other questions that aims to quantify how happy they are with their current jobs. The survey was posted on Linkedin and X where 631 data professionals responded to. The data was loaded into Power Query and cleaned before it was exported to Power BI for onward visualization.    
**STEPS IN DATA CLEANING**  
-Imported from Excel and loaded to the Power Query Editor.  
-Column from browser to referral were deleted from the dataset table as they served no purpose for my analysis.  
-The column "which tittle best fits your current role", "which country do you live in" and "what industry do you work im" was cleaned by splitting the column by a delimeter and grouping all other responses as "others". The new colon is now deleted.  
-Also, the column "Favorite Programming Language" was splitted by column using the colon delimeter and grouping all other responses as "others". The new colon is now deleted.  
-For the column with the current salary, the average for the ranges of the salary were taken after splitting the column for the current yearly salary. The new column was then renamed to "Average Salary".

