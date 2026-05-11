# Loan Approval System

An end-to-end Machine Learning project that predicts whether a loan application will be approved or rejected using applicant financial and demographic information.

This project demonstrates the complete Data Science workflow including:

- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Model Building
- Model Evaluation
- Classification Analysis

---

# Project Overview

Financial institutions receive thousands of loan applications daily. Manually evaluating each application is time-consuming and may introduce inconsistencies.

This project uses Machine Learning classification algorithms to automate the loan approval prediction process based on applicant details such as:

- Applicant Income
- Credit Score
- Employment Status
- Loan Amount
- Existing Debts
- Marital Status
- Education Level
- Loan Purpose
- Dependents
- Property Area

The goal is to build a predictive model that can determine whether a loan should be approved or rejected.

---

# Machine Learning Algorithms Used

The project compares multiple supervised learning algorithms:

## 1. Logistic Regression
- Linear classification algorithm
- Efficient for binary classification problems
- Interpretable and fast

## 2. K-Nearest Neighbors (KNN)
- Distance-based classification algorithm
- Classifies data based on neighboring samples
- Useful for pattern recognition

## 3. Naive Bayes
- Probabilistic classification algorithm
- Based on Bayes theorem
- Performs well on structured datasets

---

# Dataset Information

The dataset contains loan applicant information and the target variable:

## Target Variable

| Column | Description |
|---|---|
| Loan_Approved | Indicates whether the loan was approved or rejected |

## Features Used

- Applicant Income
- Loan Amount
- Credit Score
- Employment Status
- Marital Status
- Loan Purpose
- Dependents
- Existing Loans
- Property Area
- Education
- Other financial and demographic features

---

# Project Workflow

## 1. Data Collection
- Imported the loan approval dataset using Pandas.

## 2. Data Understanding
- Checked:
  - Dataset shape
  - Column types
  - Null values
  - Statistical summary

## 3. Data Cleaning
- Identified missing values
- Separated categorical and numerical columns
- Used `SimpleImputer` for handling missing values

### Strategies Used

| Data Type | Imputation Method |
|---|---|
| Categorical Columns | Most Frequent Value |
| Numerical Columns | Mean Value |

---

## 4. Exploratory Data Analysis (EDA)

Performed multiple visualizations using:

- Matplotlib
- Seaborn

### EDA Insights Included

- Loan approval distribution
- Class balance analysis
- Income vs Loan Amount analysis
- Credit score impact on approval
- Correlation between financial factors
- Distribution analysis of important variables

---

## 5. Data Preprocessing

Performed preprocessing steps such as:

- Encoding categorical variables
- Feature transformation
- Train-Test split
- Data preparation for ML models

---

## 6. Model Training

Trained multiple classification models:

- Logistic Regression
- KNN
- Naive Bayes

---

## 7. Model Evaluation

Evaluated models using:

- Accuracy Score
- Classification Metrics
- Confusion Matrix

---

# Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |

---
