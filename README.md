# Employee Attrition and Workforce Analytics

This project involves analyzing employee attrition and workforce data from a company to build predictive models, identify employee segments, and analyze performance and salary progression. The goal is to provide insights into employee turnover and help HR departments optimize workforce strategies.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Overview](#data-overview)
- [Usage](#usage)
- [Models and Analysis](#models-and-analysis)
  - [Employee Attrition Prediction](#1-employee-attrition-prediction-classification)
  - [Employee Segmentation Using Clustering](#2-employee-segmentation-using-clustering)
  - [Performance and Salary Progression Prediction](#3-performance-and-salary-progression-prediction)
  - [Employee Attrition Analysis Dashboard](#4-employee-attrition-analysis-dashboard)
  - [Employee Demographics Report](#5-employee-demographics-report)

## Project Overview

The goal of this project is to predict employee attrition (whether an employee will leave the company), segment employees into clusters based on their attributes, and predict salary and performance progression. It also includes visualizations and interactive dashboards to understand employee turnover patterns.

## Data Overview

The dataset used in this project is sourced from a company's HR system and includes 35 features such as employee demographics, job satisfaction, monthly income, and performance ratings. The target variable for attrition prediction is `Attrition`, where `Yes` indicates the employee left, and `No` indicates the employee stayed.
   
## Usage

Preprocess Data: The dataset should be loaded from a CSV file containing employee records. The df DataFrame holds the data.

Train Models: Several models are used in this project to perform classification, regression, and clustering:

- Employee Attrition Prediction: Predict whether an employee is likely to leave the company.
- Employee Segmentation Using Clustering: Segment employees into groups based on their features.
- Performance and Salary Progression Prediction: Predict the future salary or performance rating of employees.
- Employee Attrition Analysis Dashboard: Visualize attrition patterns.
- Employee Demographics Report: Analyze the demographics of employees who left vs. those who stayed.
- Run the notebook or Python scripts to train the models and visualize the results.
