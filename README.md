# Employee_retention_analysis
This project analyzes employee retention by examining factors like job satisfaction, performance evaluations, workload, and promotions. The goal is to identify key determinants influencing employee turnover and use machine learning to predict attrition, offering actionable insights to improve retention strategies.
Project Description:

# Aim:

The primary goal of the project is to predict which employees are most likely to leave the company, based on factors like job satisfaction, performance, workload, and career growth opportunities. Using these insights, the project offers recommendations to reduce turnover and improve employee satisfaction.

# Data:
	•	Data Source: Kaggle - HR Analytics and Job Prediction dataset
	•	Data Description:
	•	satisfaction_level: Employee-reported job satisfaction level (0–1)
	•	last_evaluation: Score of the employee’s last performance review (0–1)
	•	number_project: Number of projects the employee contributes to
	•	average_monthly_hours: Average number of hours the employee worked per month
	•	time_spend_company: Duration (in years) the employee has been with the company
	•	Work_accident: Whether or not the employee experienced an accident while at work (1 = Yes, 0 = No)
	•	left: Whether or not the employee left the company (target variable, 1 = Left, 0 = Stayed)
	•	promotion_last_5years: Whether or not the employee was promoted in the last 5 years (1 = Yes, 0 = No)
	•	Department: The department in which the employee works (e.g., Sales, HR, IT)
	•	salary: The employee’s salary, categorized into low, medium, or high

# Methods Used:
	1.	Data Preprocessing:
	•	Handling missing values, outliers, and feature transformations were performed to prepare the data for modeling.
	2.	Feature Engineering:
	•	Existing variables were optimized, and new features were created to enhance model performance.
	3.	Modeling:
	•	Logistic Regression: Used to predict the probability of employee attrition, evaluated with precision, recall, F1-score, and accuracy metrics.
	•	Decision Tree and Random Forest: Applied to analyze feature importance and predict employee retention. Metrics such as AUC, precision, recall, F1-score, and accuracy were used for model evaluation.
	4.	Interpretation:
	•	The models were interpreted to identify key factors influencing employee retention, with a focus on understanding the most critical variables for predicting attrition.

By leveraging data-driven insights, this project aims to provide recommendations for improving work culture, managing employee workloads, and optimizing retention strategies.
