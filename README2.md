# Customer Churn Prediction for GNB Bank

## Overview
This project focuses on predicting customer churn for GNB Bank, a prominent financial institution. Customer churn has significant implications for a bank's revenue and reputation, and the goal of this project is to develop an effective predictive model to identify customers at risk of churning. By identifying potential churners, the bank can take proactive measures to retain them and enhance customer satisfaction.

## Table of Contents
- [Background](#background)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Results and Recommendations](#results-and-recommendations)
- [Conclusion](#conclusion)

## Background
Customer churn, the phenomenon of customers leaving a service, can have serious repercussions for businesses. In this project, we address the challenge of predicting customer churn for GNB Bank and recommend strategies to mitigate it.

## Data
The project utilized a dataset containing customer information, including demographics, banking behavior, and historical churn data. The dataset required preprocessing to handle missing values and ensure its suitability for modeling.

## Data Preprocessing
- The dataset had missing values, which were handled through methods like dropping rows with minimal missing values and imputing mode values for specific columns.
- Irrelevant columns such as `RowNumber`, `CustomerId`, and `Surname` were dropped, as they had no impact on customer churn.
- Categorical variables like `Gender` and `Geography` were one-hot encoded for modeling.

## Exploratory Data Analysis (EDA)
- Explored the distribution of customer churn in the dataset, finding that about 20% of customers had exited.
- Investigated the impact of different variables on customer churn through univariate and bivariate analyses.
- Visualized relationships between categorical variables and customer churn using count plots.
- Observed that females and customers from Germany were more likely to churn.

## Modeling
- Utilized multiple machine learning models including Logistic Regression, Random Forest, Gradient Boosting, K Nearest Neighbors, and XGBoost.
- Performed hyperparameter tuning using GridSearchCV to optimize model performance.
- Applied Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance.
- Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC metrics.

## Results and Recommendations
- Achieved an accuracy of approximately 90.7% with the optimized XGBoost model after addressing class imbalance.
- Identified key factors contributing to customer churn.
- Provided actionable recommendations for GNB Bank, including targeted retention strategies, personalized customer experiences, and timely engagement.

## Conclusion
The project successfully developed a predictive model to identify customers at risk of churning for GNB Bank. By implementing the recommendations derived from the model's insights, the bank can proactively reduce customer churn, enhance customer loyalty, and improve its overall performance.

## Acknowledgments
