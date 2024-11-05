# Breast Cancer Classification

This project uses machine learning techniques to classify breast cancer as malignant or benign. Using data preprocessing, normalization, and a selection of classification models (Logistic Regression, K-Nearest Neighbors, and Random Forest), the project aims to identify the most effective model based on accuracy.

## Table of Contents
1. [Features](#features)
2. [Dataset](#dataset)

## Features
- **Data Preprocessing**: Removes unnecessary columns, encodes categorical labels, and scales features.
- **Statistical Analysis**: Conducts normality tests (Shapiro-Wilk) to assess data distribution.
- **Classification Models**: Compares Logistic Regression, K-Nearest Neighbors, and Random Forest classifiers.
- **Performance Evaluation**: Uses accuracy scores on both training and testing data to evaluate models.

## Dataset
- The dataset used is a breast cancer dataset (`BREAST_CANCER.csv`) which contains attributes like diagnosis results, cell characteristics, etc.
- Columns "id" and "Unnamed: 32" are removed as they are not essential for classification.
