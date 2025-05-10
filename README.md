# AI-Powered Credit Card Fraud Detection System

## Overview

This project focuses on developing an AI-powered system to accurately detect and prevent fraudulent credit card transactions in real time. By analyzing user behavior and transaction patterns, this system aims to overcome the limitations of traditional fraud detection methods, which are often slow and inaccurate, leading to false alerts and a poor user experience.

## Problem Statement

Credit card fraud is an increasing threat in the realm of digital transactions, resulting in significant financial losses. Existing fraud detection systems often struggle with the evolving and complex nature of fraudulent activities. This project addresses this challenge by creating a more intelligent and adaptive system for real-time fraud detection.

## Abstract

The rapid expansion of digital payments has made credit card fraud a major concern for both financial institutions and consumers. Traditional fraud detection systems, relying on static rules and manual reviews, are proving insufficient against sophisticated fraudulent techniques. This project proposes an AI-driven solution utilizing machine learning algorithms to analyze transaction data, identify anomalous behavior, and detect potential fraud as it occurs. By learning from historical data and continuously updating its detection model, the system aims to significantly reduce false positives and enhance fraud prevention.

## Project Repository

[https://github.com/pyk-cre/phase-3-credit-card-detection.git](https://github.com/pyk-cre/phase-3-credit-card-detection.git)

## Technologies Used

The project utilizes the following Python libraries:

-   pandas
-   matplotlib.pyplot
-   seaborn
-   sklearn.model\_selection (train\_test\_split)
-   sklearn.preprocessing (StandardScaler, OneHotEncoder)
-   sklearn.compose (ColumnTransformer)
-   sklearn.pipeline (Pipeline)
-   sklearn.linear\_model (LogisticRegression)
-   sklearn.tree (DecisionTreeClassifier)
-   sklearn.ensemble (RandomForestClassifier)
-   sklearn.metrics (classification\_report, confusion\_matrix)
-   joblib
-   plotly.express

## Data Exploration and Preprocessing

The project includes steps for data cleaning and Exploratory Data Analysis (EDA) on a dataset named `Churn_Modelling.csv`.

**Data Cleaning:** Irrelevant columns such as `RowNumber`, `CustomerId`, and `Surname` are dropped.

**EDA:** Missing values are checked, and the churn distribution is visualized using a count plot.

**Feature Engineering:** Categorical features like `Geography` and `Gender` are encoded using one-hot encoding.

## Model Development

The project likely involves the development and training of machine learning models for fraud detection. The imported libraries suggest the use of models such as:

-   Logistic Regression
-   Decision Trees
-   Random Forest

The `sklearn.pipeline` indicates that preprocessing steps and model training are likely combined into efficient workflows. The `joblib` library suggests that trained models are saved for later use.

## Evaluation

The performance of the developed models is evaluated using metrics such as the classification report and confusion matrix.

## Future Scope

The project outlines several potential areas for future development:

1.  Real-time deep learning for dynamic fraud detection
2.  Federated learning for privacy-preserving training
3.  Adaptive models that learn new fraud patterns continuously
4.  Behavioral biometrics for enhanced user verification
5.  Graph analytics to detect fraud networks
6.  Explainable AI to build user trust
7.  Blockchain for secure, traceable transactions

## Team Members and Roles

-   Data cleaning - Trisha .M
-   EDA - Varuneesri.A
-   Feature engineering - Pavithra.S.Y
-   Model development - Sruthi.L
-   Documentation and reporting - Swetha .J and Priyanka .P

## Date of Submission

09/05/2025
