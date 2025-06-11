# 🏥 HealthTech Analytics – SQL & Python for Data-Driven Healthcare Decisions

## 📘 Overview

This repository contains a Jupyter Notebook that demonstrates how to use SQL and Python to analyze healthcare data from a relational database. The case study is based on a simulated project at **HealthTech Analytics**, a startup helping hospitals improve patient care and operational efficiency through data insights.

## 🗂️ Case Study Scenario

HealthTech Analytics has provided access to a healthcare database with the following tables:

- **patients** (`patient_id`, `name`, `gender`, `birth_date`, `city`)
- **visits** (`visit_id`, `patient_id`, `visit_date`, `doctor_id`, `diagnosis_code`)
- **doctors** (`doctor_id`, `name`, `department`)
- **treatments** (`treatment_id`, `visit_id`, `treatment_name`, `treatment_cost`)
- **diagnoses** (`diagnosis_code`, `diagnosis_description`)

The goal is to use SQL queries within Python to answer complex business questions and visualize key healthcare trends.


## 🔧 Technologies Used

- **Database**: SQLite (can be adapted to PostgreSQL)
- **Language**: Python 
- **Libraries**: `sqlite3`, `pandas`, `matplotlib`, `seaborn`, `datetime`


## 🎯 Project Objectives

### 1. Data Setup & Exploration (6 marks)
- Connect to the database using Python.
- Query to list the number of patients by city.
- Visualize the result using a bar chart.

### 2. Diagnosis Trends by Department (6 marks)
- Use joins to calculate how many diagnoses are made per department.
- Present the result in a table.
- Briefly interpret the findings in Markdown.

### 3. Cost Analysis per Patient (6 marks)
- Query total cost of treatments per patient.
- Identify the top 5 patients by spending.
- Create a horizontal bar chart to visualize results.

### 4. Advanced Insight – Frequent Patients & Visit Patterns (6 marks)
- Identify patients with more than 5 visits in the last year.
- Analyze visit frequency across months.
- Display visit trends in a line graph.
