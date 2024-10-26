# Insurance Claims Analysis Project

## Overview
This project aims to analyze insurance claims data and build predictive models to understand and predict the factors influencing claims filing. With the rising costs of insurance fraud and the increasing complexity of claims, this analysis is crucial for insurance companies to improve their risk assessment and operational efficiency.

## Objective
To analyze insurance claims data to identify key factors affecting claims and develop predictive models that can accurately assess the likelihood of a claim being filed. This project aims to help insurance companies optimize their processes and minimize losses from fraudulent claims.

## Importance of the Project
The insurance industry faces significant challenges, including fraud detection, risk assessment, and customer satisfaction. By leveraging data analytics and machine learning, this project seeks to:

- Enhance the accuracy of claim predictions, leading to more efficient claim processing.
- Identify trends and patterns in claims data that can inform underwriting practices.
- Reduce the financial impact of fraudulent claims, benefiting both insurers and policyholders.
- Improve decision-making processes through data-driven insights.

## Dataset
The dataset used in this project is sourced from Kaggle. It includes various features related to insurance claims, such as customer demographics, claim details, and incident characteristics.

## Methodology
Data Cleaning: Replaced missing values represented by '?' with NaN. Filled missing categorical variables with the mode.
Feature Selection: Dropped unnecessary columns for prediction. Conducted correlation analysis and removed highly correlated features.
Feature Scaling: Standardized numerical features using standardscalar scaling.
Data Visualization: Created bar charts, histograms, and boxplots to explore data distributions.
Model Implementation:
Implemented various machine learning algorithms, including:
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Decision Tree
- Random Forest
- AdaBoost
- XGBoost
  
## Results:
The Decision Tree, AdaBoost, and XGBoost models achieved the highest test accuracy of 81.2%.
