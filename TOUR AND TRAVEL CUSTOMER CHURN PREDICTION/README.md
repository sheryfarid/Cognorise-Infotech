# Tour & Travels Customer Churn Prediction

## Overview
This project focuses on predicting customer churn in the travel industry using machine learning techniques. The analysis utilizes the **Tour & Travels Customer Churn Prediction dataset**, which contains various customer indicators that help understand their likelihood of churning.

## Problem Statement
In the competitive landscape of the travel industry, customer retention is vital for sustaining revenue and ensuring long-term success. The **Tour & Travels Customer Churn Prediction dataset** provides an opportunity to analyze and predict customer behavior, specifically focusing on churn. This project aims to build predictive models that can accurately forecast customer churn, enabling targeted retention strategies.

## Dataset
The dataset includes the following features:
- **Age**: The age of the customers.
- **FrequentFlyer**: Indicates whether the customer is a frequent flyer.
- **AnnualIncomeClass**: Classification of customers based on their income levels.
- **ServicesOpted**: The number of services utilized by the customer.
- **AccountSyncedToSocialMedia**: Whether the customer's account is linked to social media platforms.
- **BookedHotelOrNot**: A binary indicator showing whether the customer has booked a hotel.
- **Target**: The binary target variable (1 for churn, 0 for no churn).

## Exploratory Data Analysis (EDA)
The EDA process involved:
- Visualizing the distribution of age and income classes.
- Analyzing the impact of frequent flyer status on churn rates.
- Investigating service usage patterns and their correlation with churn.
- Examining the relationship between social media synchronization and customer retention.

## Modeling
Several machine learning models were applied to predict customer churn, including:
- Logistic Regression (LR)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier (DTC)
- Random Forest (RF)
- Support Vector Machine (SVM)
- Gradient Boosting Classifier (GBC)

Each model was evaluated using various metrics to determine its effectiveness in predicting churn.

## Model Results
| Model                           | Accuracy | Precision | Recall  | F1 Score | ROC AUC |
|---------------------------------|----------|-----------|---------|----------|---------|
| Logistic Regression (LR)       | 0.8111   | 0.5000    | 0.4118  | 0.4516   | 0.7168  |
| K-Nearest Neighbors (KNN)      | 0.8444   | 0.5789    | 0.6471  | 0.6111   | 0.8550  |
| Decision Tree Classifier (DTC) | 0.8667   | 0.6087    | 0.8235  | 0.7000   | 0.8489  |
| Random Forest (RF)             | 0.8222   | 0.5238    | 0.6471  | 0.5789   | 0.8807  |
| Support Vector Machine (SVM)   | 0.7889   | 0.4444    | 0.4706  | 0.4571   | 0.8239  |
| Gradient Boosting Classifier (GBC) | 0.9222   | 0.7500    | 0.8824  | 0.8108   | 0.9617  |

