# Anomaly Detection Project

This is a code walkthrough file for the Anomaly Detection Project.

## Project Outline

This document outlines the steps involved in tackling the anomaly detection problem:

### Data Exploration and Visualization

- Imported libraries and loaded the dataset.
- Analyzed the data for understanding features, class imbalance, and relationships.
- Performed correlation analysis and explored its impact on feature selection.
- Created visualizations to gain insights into the data distribution.

### Data Preprocessing and Cleaning

- Identified and handled missing values, outliers, and skewed data.
- Applied feature engineering techniques like normalization or standardization.
- Justified the chosen techniques and explored feature importance methods.

### Model Building

- Splitting the data into training and testing sets, discussing the rationale behind the split ratio.
- Explored k-fold cross-validation for robust model evaluation.
- Implemented two suitable anomaly detection models, with justification.
- Investigated regularization techniques and incorporated them if relevant.
- Compared model performance with and without regularization, explaining the findings.

### Performance Evaluation

- Predicting on the test data and calculate relevant evaluation metrics.
- Choosing the best performing model with justification.
- Analyzing the model for potential underfitting, overfitting, or optimal performance.

### Model Deployment

- Used Ngrok for deploying machine learning models.
- Selected a deployment method and persisted the chosen model.
- Implementing the deployment solution to accept new data points via HTTP requests, running predictions with the saved model, and returning the results.
