# House Price Prediction Project

## Overview

Welcome to the House Price Prediction project! This project focuses on predicting house prices using advanced data analysis techniques. The primary steps involve Exploratory Data Analysis (EDA) to understand the dataset and feature selection methods such as correlation analysis, Variance Inflation Factor (VIF), and Recursive Feature Elimination (RFE) from scikit-learn.

## Table of Contents

- Project Description
- Exploratory Data Analysis (EDA)
- Feature Selection
  - Correlation Analysis
  - Variance Inflation Factor (VIF)
  - Recursive Feature Elimination (RFE)
- Getting Started
- Dependencies
- Installation

## Project Description

The goal of this project is to predict house prices using a dataset enriched with various features. The project is divided into two main phases: Exploratory Data Analysis (EDA) and Feature Selection. The EDA phase helps us understand the data distribution, identify outliers, and gain insights into potential correlations. The Feature Selection phase involves eliminating irrelevant or redundant features to enhance the predictive power of the model. For the dataset used in this project, refer to the [Kaggle House Price Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).

## Exploratory Data Analysis (EDA)

In this phase, we perform a thorough exploration of the dataset to gain insights into the data distribution, relationships between variables, and potential outliers. EDA is crucial for understanding the underlying patterns in the data before diving into the modeling phase.

## Feature Selection

### Correlation Analysis

Correlation analysis is employed to identify the relationships between different features and the target variable (house prices). By understanding the correlation coefficients, we can prioritize features that have a significant impact on the target variable.

### Variance Inflation Factor (VIF)

VIF is used to detect multicollinearity among the features. High multicollinearity can lead to inaccurate model estimates. Features with high VIF values are considered for elimination.

### Recursive Feature Elimination (RFE)

RFE is a feature selection method that recursively removes less important features. The process continues until the desired number of features is reached. This helps in creating a more efficient and accurate model.

### Analysis of Variance (ANOVA)

ANOVA is another powerful technique for feature selection, particularly when dealing with categorical variables. It assesses the statistical significance of different categorical features in explaining the variance in the target variable. Features with high F-statistics and low p-values are retained.

## Getting Started

To get started with the project, follow these instructions:

### Dependencies

Make sure you have the following dependencies installed:

- Python (>=3.6)
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

### Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/sumanbarman99/house-price-prediction.git
