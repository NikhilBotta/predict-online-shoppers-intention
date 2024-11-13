## Project Name: Click2Cart - Predicting Online Shopper Purchase Intentions with SVM
## Project Overview
## This project aims to predict whether online shoppers will complete a purchase by analyzing their browsing behavior. Using an SVM model, feature engineering, and hyperparameter tuning, this model will help forecast the likelihood of a transaction based on user interactions with various types of web pages, traffic type, and session information. Given the dataset's imbalance, the F1 score is the chosen metric with a benchmark of 0.55.## 

# Problem Statement
E-commerce businesses face high volumes of browsing activity but not all users end in a purchase. By predicting purchase intent, businesses can better understand user behavior and tailor their strategies to improve conversion rates.

## Dataset Summary
Sessions: 12,330 sessions over a year, with each session representing a unique user.
Target Variable: Revenue (binary), indicating if a session resulted in a purchase.
Feature Highlights:
Page Interactions: Administrative, informational, and product-related pages and durations.
Engagement Metrics: Bounce rates, exit rates, and page values.
Session Details: Proximity to special days, month, operating systems, browser, region, traffic type, visitor type, and weekend indicator.
# Project Steps
# 1. Exploratory Data Analysis (EDA)
Analyzed distribution, skewness, and kurtosis of browsing behavior features, highlighting high variability.
Visualized distributions of categorical features (e.g., OS, browser, region) to uncover trends in user interactions.
# 2. Data Preprocessing and Feature Engineering
Encoding and Scaling: Converted categorical data, scaled numeric features.
Low Variance Filtering: Removed features with minimal variance to reduce noise and improve model generalization.
Outlier Handling: Addressed outliers in highly skewed features.
Data Splitting: Prepared balanced splits for training, validation, and testing.
# 3. Model Development
Model Selection: Trained a Support Vector Machine (SVM) model for its effectiveness with high-dimensional data.
Hyperparameter Tuning: Used grid search and cross-validation to optimize SVM parameters for maximum F1 score.
Class Imbalance: Applied class weighting to enhance SVM performance on minority classes.
# 4. Evaluation
Metric: F1 score to manage class imbalance.
Benchmark: The target F1 score is 0.55.
Results: Provided visualizations of model performance, confusion matrix, and a breakdown of feature importance.
