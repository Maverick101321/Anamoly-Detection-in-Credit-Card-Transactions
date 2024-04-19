# Credit Card Fraud Detection Project
## Overview
#### Credit card fraud is a pervasive issue in the financial industry, leading to significant financial losses for both consumers and businesses. Traditional rule-based systems for fraud detection often struggle to keep pace with the evolving tactics of fraudsters. Therefore, machine learning approaches, particularly supervised learning algorithms, have gained popularity for identifying fraudulent activity in credit card transactions.

#### This repository contains the code and documentation for a project aimed at exploring the effectiveness of various machine learning models in detecting anomalies in credit card transactions. The project evaluates a range of algorithms, including traditional models like Logistic Regression and Decision Trees, ensemble methods like Random Forests and Gradient Boosting, and deep learning approaches such as Artificial Neural Networks (ANNs).

## Project Motivation
#### The main aim of this project is to address the limitations of conventional machine learning models used for anomaly detection, particularly in the context of credit card fraud detection. Conventional models often struggle with two key challenges:

#### Low Accuracy: Traditional machine learning models, such as Logistic Regression and Decision Trees, may achieve suboptimal accuracy in detecting fraudulent transactions due to the complexity and variability of fraudulent patterns.
#### Imbalanced Dataset: The heavily unbalanced nature of fraudulent transactions compared to legitimate transactions presents a significant challenge. In most datasets, fraudulent transactions represent only a small fraction of the total number of transactions, leading to class imbalance issues that can bias model predictions and accuracy metrics.
## Solution Approach
#### To overcome the limitations of conventional machine learning models, we leverage the capabilities of Artificial Neural Networks (ANNs). ANNs offer several advantages over traditional models:

#### Nonlinearity: ANNs can capture complex nonlinear relationships in the data, allowing them to learn intricate patterns and anomalies that may be difficult for linear models to detect.
#### Automatic Feature Learning: ANNs automatically learn features from the raw input data, eliminating the need for manual feature engineering and preprocessing steps.
#### Robustness to Imbalance: Unlike traditional models, ANNs are less sensitive to class imbalance issues. They can effectively learn from imbalanced datasets without the need for specialized techniques such as oversampling or undersampling.
## Results
#### The project results demonstrate the effectiveness of ANNs in improving both accuracy and robustness in credit card fraud detection. By systematically evaluating different machine learning models and techniques, we have shown that ANNs outperform traditional models in terms of detection accuracy while mitigating the effects of class imbalance.
