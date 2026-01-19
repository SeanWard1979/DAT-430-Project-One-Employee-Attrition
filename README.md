# DAT-430-Project-One-Employee-Attrition

## Installations
Python 3.8.12 and Jupyter Notebook 6.4.3

## Project Motivations
The baseline to establish using the HR Attrition data set involves determining which factors best predict the possibility of attrition within the company.

## Conclusions
Utilizing a correlation heatmap and looking at VIF values (for collinearity), I settled upon seven different variables that best predict the likelihood of attrition.  Performance Rating, Hourly Rate, Age, Distance from Home, Years in Current Role, Years Since Last Promotion and Education.  Using these seven variables, the Random Forest Classifier was able to obtain a F1 score of 0.85 in predicting no attrition, and a F1 score of 0.69 in predicting attrition.

## File Descriptions
Ward_Sean DAT 430 Project Two Part One.docx : Word document that shares the results of the statistical testing (using Random Forest Classifier and Logistic Regression models).

Ward_Sean_DAT-430_Project_One.ipynb:  The Python code and results for the first Attrition project for DAT-430.

## The Project's Journey
The original attrition dataset featured 34 different variables with varying levels of influence on what causes attrition.  The data was properly cleaned and prepared within Jupyter Notebook.  The categorical data was converted into numerical format using LabelEncoder().  I utilized feature scaling as well.
I used various visualizations such as a correlation heatmap to see the actual impact (if any) the variables have on attrition.  I narrowed it down to Performance Rating, Hourly Rate, Age, Distance from Home, Years in Current Role, Years Since Last Promotion and Education.  

## Licensing, Authors, Acknowledgements, etc.
