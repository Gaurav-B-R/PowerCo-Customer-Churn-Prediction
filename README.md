# PowerCo Customer Churn Prediction

## Overview
This project focuses on predicting customer churn for **PowerCo**, a fictional energy provider, using machine learning techniques. The primary goal is to identify the factors contributing to customer churn and build a predictive model that helps the company implement strategies to improve customer retention.

### Project Objectives
- Develop a robust machine learning model to predict whether a customer will churn.
- Analyze and interpret key factors that drive customer churn.
- Provide actionable recommendations based on model findings.

## Dataset
The dataset used for this project includes the following:
- **Historical Customer Data**: Features such as energy usage, sign-up date, forecasted usage, and customer service interactions.
- **Historical Pricing Data**: Variable and fixed pricing data for different months.
- **Churn Indicator**: A binary target variable indicating whether each customer has churned.

## Project Workflow
1. **Data Cleaning and Preprocessing**:
   - Removed missing values and formatted columns for consistency.
   - Converted non-numeric columns to a suitable format for model training.
  
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed distributions, outliers, and relationships between features.
   - Visualized key metrics to gain insights into customer behavior.

3. **Feature Engineering**:
   - Created new features to capture seasonality and variations in energy prices.
   - Analyzed feature importance to determine which variables contribute most to churn.

4. **Model Building and Evaluation**:
   - Trained a **Random Forest Classifier** for churn prediction.
   - Evaluated the model using **Accuracy**, **Confusion Matrix**, and **ROC Curve**.

5. **Findings and Recommendations**:
   - Provided insights on how off-peak prices and customer service interactions are key drivers of churn.
   - Recommended strategies for PowerCo to improve customer retention and mitigate churn risk.

## Key Results
- **Model Accuracy**: 85%
- **AUC Score**: 0.87
- **Top Features Influencing Churn**:
  1. Off-peak prices in December and January.
  2. Forecasted energy usage.
  3. Customer service interaction frequency.
