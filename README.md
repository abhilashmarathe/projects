📊 Client Revenue Analytics & High-Value Project Prediction
🚀 Overview

This project analyzes client project data for a digital agency to uncover revenue trends and predict high-value projects using Machine Learning.

The system performs end-to-end data analysis including:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Monthly revenue trend analysis

Growth rate calculation

Classification modeling

Model comparison (Logistic Regression vs Random Forest)

Feature importance analysis

🎯 Business Problem

As a digital agency, understanding:

Which project types generate higher revenue

Which industries bring high-ticket clients

Which cities show strong revenue potential

How to predict high-value projects

helps improve pricing strategy, lead targeting, and revenue forecasting.

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Google Colab

📂 Dataset Description

The dataset contains simulated client project data with the following features:

client_id

client_name

industry

project_type

project_cost

start_date

payment_status

city

A target variable was engineered:

high_value_project (1 if project_cost > 80,000 INR, else 0)

📈 Exploratory Data Analysis (EDA)

The analysis included:

Revenue distribution across industries

Revenue by project type

Revenue by city

Monthly revenue trend analysis

Month-over-month growth rate calculation

These insights helped understand business performance patterns.

🤖 Machine Learning Approach
Target Variable:

High-value project classification

Models Implemented:

Logistic Regression

Random Forest Classifier

Evaluation Metrics:

Accuracy Score

Classification Report

Confusion Matrix

Random Forest demonstrated stronger performance by capturing non-linear relationships in the dataset.

📊 Key Insights

E-commerce and Business Website projects generated higher revenue.

Certain industries showed greater probability of high-value projects.

City-level segmentation revealed revenue concentration patterns.

Tree-based models performed better than linear models for this dataset.

📁 Project Structure

client-revenue-analytics-ml/
│
├── eda_and_model.ipynb
├── client_data.csv
├── requirements.txt
└── README.md

🔮 Future Improvements

Hyperparameter tuning

Cross-validation

Revenue prediction using regression models

Integration with SQL database

Deployment as a Django-based analytics dashboard

Power BI visualization layer

👨‍💻 Author

Abhilash R. Marathe
Computer Science Engineer | Data Analytics & ML Enthusiast
Founder – WebQuicks Technologies

LinkedIn: https://www.linkedin.com/in/abhilash-marathe-aa4331140/
