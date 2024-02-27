# Income Prediction Classification

This project addresses a classification problem aimed at predicting whether an individual's income is less than Rs.50,000 or more than Rs.50,000. Various machine learning models are explored, and feature selection techniques are applied to improve model performance. The final selected model is a xgboost model due to its accuracy and the random forest model is interpreted to gain insights into the data and the factors influencing income levels.

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Machine Learning Models](#machine-learning-models)
- [Feature Selection](#feature-selection)
- [Interpreting the Decision Tree Model](#interpreting-the-decision-tree-model)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

The ability to predict income levels is valuable for various applications, such as targeted marketing campaigns and financial planning. This project focuses on developing a classification model to predict whether an individual's income exceeds Rs.50,000 based on demographic and socioeconomic features.

## Problem Statement

The primary objective of this project is to build a machine learning model capable of classifying individuals into two income categories:

- **Income less than Rs.50,000**
- **Income more than Rs.50,000**

Accurate classification is essential for decision-making processes and resource allocation.

## Dataset

The dataset used in this project contains demographic and socioeconomic attributes of individuals, including age, education level, occupation, marital status, and capital gains, among others. The dataset is preprocessed to handle missing values and categorical variables.

## Machine Learning Models

Several machine learning models are evaluated for their ability to predict income levels, including:

- Logistic Regression
- Random Forest
- XG Boost
- Decision Tree

Each model is trained and evaluated using appropriate performance metrics to determine its effectiveness in classification tasks.

## Feature Selection

Feature selection techniques, such as correlation analysis are applied to identify the most relevant features for predicting income levels. Removing irrelevant or redundant features helps improve model efficiency and interpretability.

## Interpreting the Random Forest Model

The xgboost is selected as the final model due to its performance. But The random forest is visualized and interpreted which helps us gain insights into the factors influencing income levels. Understanding the decision rules can provide valuable insights for policymakers and stakeholders.


## Usage

To utilize the income prediction classification model:

1. Ensure that the dataset is available and properly formatted.
2. Train the selected machine learning model using the provided dataset.
3. Evaluate the model's performance using appropriate evaluation metrics.
4. Interpret the random forest to gain insights into the factors influencing income levels.
