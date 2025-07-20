Data Science Job Salaries: Analysis & Prediction

A comprehensive project to analyze and predict data science job salaries using machine learning.
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/42b69f94-4390-4807-994c-a02295c9f1da" />


📌 Overview
This project focuses on exploratory data analysis (EDA) and machine learning modeling of Data Science Job Salaries across various roles, company types, experience levels, and geographical locations. The aim is to derive insights from the dataset and build a predictive model that estimates salaries based on job features.

📊 Dataset
Source: unified internship projects - Data Science Salaries Dataset

Records: 607+ entries

Features Include:

job_title

experience_level

employment_type

company_size

remote_ratio

company_location

employee_residence

salary_in_usd (Target variable)

🔍 Project Workflow
📈 1. Data Analysis (Data Analysis work.ipynb)
Checked for null values, duplicates, and outliers.

Visualized:

Salary distribution

Top-paying roles

Salary by experience level

Remote ratio vs salary

Country-wise average salaries

Encoded categorical variables for modeling.

🤖 2. Machine Learning (Machine Learning Work.ipynb)
Preprocessed data with LabelEncoder and feature scaling.

Applied and evaluated multiple regression models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Selected the best-performing model using RMSE and R² metrics.

📌 Key Findings
Experience level and job role are the most significant factors influencing salary.

Remote jobs tend to have slightly higher average salaries.

Large companies usually offer higher compensation.

United States and Switzerland top the charts for average salary offered.
