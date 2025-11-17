📌 Employee Turnover Analytics – Machine Learning Project

This project predicts employee turnover for Portobello Tech using machine learning.
The company evaluates employees based on:

Number of projects

Average monthly working hours

Years in the company

Promotions in the last 5 years

Salary level

Satisfaction level

Last evaluation score

The HR Department uses this data to predict employee churn and understand why employees leave.

✅ Project Objectives

As the ML Developer, the tasks include:

Data quality checks — identify missing or inconsistent values

Exploratory Data Analysis (EDA) — find key factors contributing to turnover

Clustering employees who left based on satisfaction & evaluation

Handling class imbalance using SMOTE

Model training with k-fold cross-validation

Model evaluation using metrics like Accuracy, Precision, Recall, F1-score, ROC-AUC

Selecting the best model

Recommending retention strategies

📂 Project Structure
employee-turnover-analytics/
│
├── data/
│   ├── hr_data.csv
│
├── docs/
│   ├── problem-statement.docx
│
├── notebooks/
│   ├── employee-turnover-analysis.ipynb
│
└── README.md

🔍 Exploratory Data Analysis

Key insights:

Employees with low satisfaction had the highest turnover

High workloads strongly correlated with leaving

Salary level & promotion history impacted retention

Correlation heatmaps revealed relationships between evaluation, satisfaction, and churn

⚙️ Machine Learning Workflow
1. Preprocessing

Categorical encoding

Feature scaling

SMOTE for class imbalance

2. Models Used

Logistic Regression

Random Forest

Gradient Boosting

3. Evaluation Metrics

Accuracy

Precision

Recall

F1-score

ROC-AUC

4. Best Model

Random Forest or Gradient Boosting typically performs best for predicting at-risk employees.

🎯 Business Recommendations

Improve job satisfaction through engagement programs

Balance workload to prevent burnout

Provide promotion pathways for long-tenure employees

Salary adjustments for low-salary/high-churn groups

Offer skill-building programs

Conduct regular feedback sessions

🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Imbalanced-learn (SMOTE)

Jupyter Notebook

📌 Status

Project completed as part of a machine learning assignment for predicting employee turnover.