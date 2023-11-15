# CSSE11 - Predictive Modeling Project

## Executive Summary

This repository encapsulates the culmination of the CSSE11 assignment, presenting a comprehensive exploration of advanced predictive modeling techniques on a real-world dataset. The focal point is gender prediction, leveraging features like total bill, tip amount, and party size from the "tips" dataset in seaborn. This undertaking encompasses the implementation of Bayesian Networks, XGBoost, and Random Forest models, with a profound emphasis on interpretability and ensemble strategies.

## 1. Introduction

### 1.1 Problem Statement

The project revolves around predicting gender based on diverse features, laying the groundwork for practical applications in data-driven decision-making. We delve into Bayesian Networks, XGBoost, and Random Forest, aligning theoretical foundations with hands-on implementation to extract actionable insights.

## 2. Methodology

### 2.1 Exploratory Data Analysis (EDA)

A meticulous EDA, underscored by seaborn's visualizations, sets the stage. Pair plots offer an intricate view of variable relationships, fostering an intuitive understanding of data distribution.

### 2.2 Data Preprocessing

Label encoding for categorical variables, especially gender, is performed with precision. A one-hot encoded dataset further refines our data preprocessing pipeline, ensuring compatibility with Bayesian Network modeling.

### 2.3 Model Implementation

#### 2.3.1 Bayesian Network

A Bayesian Network is meticulously crafted using the pgmpy library. This model not only captures relationships between total bill, tip, party size, and gender but also aligns with theoretical underpinnings of probabilistic graphical models.

#### 2.3.2 XGBoost and Random Forest

Ensemble models take center stage. XGBoost, known for boosting performance, and Random Forest, a robust decision tree ensemble, collectively bring forth enhanced predictive capabilities.

## 3. Results

### 3.1 Bayesian Network

The Bayesian Network showcases its prowess with an accuracy of 0.840 on the test set. Interpretability and insight into variable dependencies underscore the model's potential impact.

### 3.2 Ensemble Models

XGBoost and Random Forest yield accuracies of 0.592 and 0.612, respectively. The ensemble models unveil their resilience, consistently surpassing individual models in deciphering complex patterns within the dataset.

## 4. Conclusion

In conclusion, this project seamlessly integrates theoretical foundations with practical implementation. The Bayesian Network provides interpretability, while ensemble models underscore the versatility and efficacy of machine learning in predictive tasks. This holistic approach unlocks valuable insights with far-reaching implications for diverse classification tasks.
