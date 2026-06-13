# Customer Churn Prediction & Customer Lifetime Value Analysis

## Project Overview
This project focuses on analyzing customer behavior, predicting customer churn, and understanding customer lifetime value using data analytics and machine learning techniques. The goal is to help businesses identify customers who are likely to leave and improve customer retention strategies.

## Objectives
- Analyze customer demographics and service usage patterns.
- Identify key factors affecting customer churn.
- Perform data cleaning and preprocessing.
- Build a machine learning model for churn prediction.
- Generate insights to support business decision-making.

## Dataset
The dataset contains customer information including:
- Demographics
- Service subscriptions
- Contract details
- Monthly and total charges
- Customer churn status

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Collection & Understanding
- Imported required libraries.
- Loaded the customer churn dataset.
- Explored dataset structure, features, and statistics.

### 2. Data Cleaning & Preprocessing
- Handled missing values.
- Converted data types where necessary.
- Removed unnecessary columns.
- Encoded categorical variables for analysis.

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer churn distribution.
- Examined customer demographics and service usage.
- Studied the relationship between tenure, charges, and churn.
- Performed correlation analysis to identify important features.

### 4. Feature Engineering
- Created new features to improve predictive performance.
- Prepared data for machine learning models.

### 5. Model Building
- Split data into training and testing sets.
- Applied feature scaling.
- Trained a Logistic Regression model for churn prediction.

### 6. Model Evaluation
- Evaluated model performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

## Key Insights
- Contract type significantly influences customer churn.
- Customers with lower tenure are more likely to leave.
- Monthly charges impact customer retention behavior.
- Feature engineering helps improve prediction performance.

## Future Improvements
- Implement advanced machine learning models.
- Perform hyperparameter tuning.
- Deploy the model using Flask or Streamlit.
- Create an interactive dashboard for business insights.
