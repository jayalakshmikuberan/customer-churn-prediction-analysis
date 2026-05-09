# Customer Retention Analysis — Churn Prediction

## Overview
This project analyzes customer behavior data to predict churn — identifying customers who are likely to stop using a service. Built using Python and Machine Learning on the IBM Telco Customer Churn dataset.

## Problem Statement
Businesses lose revenue when customers leave (churn). The goal of this project is to build a predictive model that identifies at-risk customers early, so the business can take action to retain them.

## Dataset
- **Source:** IBM Telco Customer Churn Dataset
- **Size:** 7,043 customers, 21 features
- **Target variable:** Churn (Yes/No)
- **Features include:** Tenure, Monthly Charges, Contract Type, Internet Service, Payment Method, and more

## Tools & Technologies
- Python
- Pandas — data cleaning and manipulation
- Scikit-learn — Logistic Regression model
- Matplotlib & Seaborn — data visualization
- Google Colab — development environment

## Project Steps
1. **Data Cleaning** — handled missing values, converted data types, removed irrelevant columns
2. **Exploratory Data Analysis (EDA)** — analyzed churn distribution and feature correlations
3. **Feature Engineering** — encoded categorical variables using Label Encoding
4. **Model Building** — trained a Logistic Regression classifier (80/20 train-test split)
5. **Model Evaluation** — measured accuracy, precision, recall using classification report
6. **Visualization** — plotted confusion matrix, correlation heatmap, and churn distribution

## Results
| Metric | Value |
|--------|-------|
| Model Accuracy | **78.54%** |
| Algorithm | Logistic Regression |
| Train/Test Split | 80% / 20% |

## Key Findings
- **High inactivity** is the strongest predictor of customer churn
- Customers on **month-to-month contracts** churn significantly more than those on annual contracts
- **Higher monthly charges** correlate strongly with increased churn probability
- Customers with **shorter tenure** (less than 12 months) are at highest risk of churning

## How to Run
1. Open the notebook in Google Colab
2. Run all cells (Runtime → Run all)
3. The model will train and print accuracy automatically

## Connect
- LinkedIn: linkedin.com/in/jayalakshmi-kuberan-92452b2a5
- GitHub: github.com/jayalakshmikuberan
