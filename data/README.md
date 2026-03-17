# Data Notes

This project is based on the public **HR employee attrition dataset**. The data is used here to study which employee characteristics are most associated with attrition and to support a predictive analysis of turnover risk.

## Dataset source

The original CSV can be downloaded from Kaggle:

[HR Analytics and Job Prediction – Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)

To run the notebook locally, place the dataset file here with the following name:

`data/HR_comma_sep.csv`

## What the dataset contains

The dataset is structured at the **employee level**, where each row represents one employee record and the target variable indicates whether the employee left the company.

The analysis uses variables such as:

- satisfaction level: Employee-reported job satisfaction level [0–1]
- last evaluation score: Score of employee's last performance review [0–1]
- number of projects: Number of projects employee contributes to
- average monthly hours: Average number of hours employee worked per month
- time spent at the company: How long the employee has been with the company (years)
- work accident: Whether or not the employee experienced an accident while at work
- promotion in the last 5 years: Whether or not the employee was promoted in the last 5 years
- department: The employee's department
- salary: The employee's salary level category (e.g., low, medium, high)
- left: Whether or not the employee left the company

## How the data is used in this project

In this repository, the dataset is used for two main purposes:

1. **Exploratory analysis** of attrition patterns across workload, satisfaction, tenure, and evaluation history  
2. **Predictive modeling** to classify whether an employee is likely to leave

The project’s main emphasis is not only prediction, but also understanding the business patterns behind turnover and translating them into practical HR insights.

## Data quality observations from the analysis

During the analysis, the dataset showed:

- approximately **15,000 employee records**
- **no missing values**
- **3,008 duplicate rows**, which were reviewed and removed before modeling
- an attrition rate of roughly **16.6%**
