
This project summary focuses on the comprehensive data cleaning and preparation steps performed on the HR dataset, making it perfectly suited for a GitHub README file.

👥 HR Analytics Dataset Preprocessing and Cleaning
This project focuses on the initial steps of a Human Resources (HR) data analysis, specifically loading, inspecting, and extensively cleaning the HR_Dataset.csv to ensure high-quality data fit for machine learning and exploratory analysis.

The goal of this phase was to deliver a clean, non-redundant dataset ready for modeling employee attrition (the left column).

🛠 Data Cleaning and Preparation Steps
The data cleaning process involved two primary checks: handling missing values and removing duplicate records.

1. Data Loading and Initial Inspection
The data was loaded into a pandas DataFrame.

The initial dataset contained 14,999 entries and 10 columns.

The target variable, left, was separated from the features (x is features, y is the target).

Features were classified into quantitative (e.g., satisfaction_level, number_project) and categorical (e.g., Departments, salary).

Feature Name	Data Type	Description
satisfaction_level	float64	Employee satisfaction rating.
last_evaluation	float64	Score of the last performance evaluation.
number_project	int64	Number of projects worked on.
average_montly_hours	int64	Average monthly work hours.
time_spend_company	int64	Tenure in the company (years).
Work_accident	int64	Whether employee had a work accident (0/1).
left	int64	Target variable: Employee turnover (0=No, 1=Yes).
promotion_last_5years	int64	Whether promoted in the last 5 years (0/1).
Departments	object	Department name.
salary	object	Salary level (low, medium, high).
