# Credit Card Fraud Detection Notebook

## Introduction

This Jupyter notebook is dedicated to the detection of fraudulent transactions using a well-known dataset from Kaggle titled "Credit Card Fraud Detection". The dataset comprises transactions made by European cardholders in September 2013, showing a highly unbalanced nature with 492 frauds out of 284,807 transactions. This project is aimed at applying unsupervised learning techniques to identify patterns indicative of fraud without relying on labeled data.

The notebook and related resources are also available on GitHub: [Credit Card Fraud Detection Project](https://github.com/MedGhassen/DTSA-5510-Unsupervised-Learning-Final-Project-).

### Dataset Overview

The dataset includes transactions over a period of two days, with most features transformed using PCA for privacy reasons. Features include time (seconds elapsed between each transaction and the first transaction), amount (transaction amount), and class (indicating fraudulent or non-fraudulent transactions). The dataset highlights the challenge of working with highly unbalanced data, where fraudulent transactions represent only 0.172% of all transactions.

The dataset is available for download at [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

### Problem Statement

The unsupervised learning problem addressed in this notebook involves identifying fraudulent transactions without the aid of labeled data. Traditional supervised learning approaches are less effective due to the class imbalance; therefore, this project explores unsupervised methods such as clustering, anomaly detection, or dimensionality reduction to uncover suspicious activities indicative of fraud.

### Methodology and Insights

The notebook proceeds to apply various unsupervised learning techniques, thoroughly analyzing and visualizing the data, and assessing different models based on their ability to detect fraudulent transactions. Key sections include data preprocessing, feature engineering, model selection, evaluation, and interpretation of results.