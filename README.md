# End-to-End Machine Learning Project

This repository contains an end-to-end machine learning project based on the book [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) by Aurélien Géron. The project involves various stages of a typical machine learning workflow, including data visualization, data cleaning, data transformation, data preparation, transformation pipelines, model fine-tuning, and error analysis.

## Introduction

This project demonstrates a comprehensive approach to solving a machine-learning problem of predicting the Median House Value of Districts in California from start to finish. Inspired by the methodologies and practices described in Aurélien Géron's book, the project leverages popular Python libraries to explore, preprocess, and model data, followed by an in-depth analysis and fine-tuning of the models.

## Project Overview

### Data Visualization

Using libraries like Matplotlib and Seaborn, I performed extensive data visualization to understand the data distribution, identify patterns, and detect anomalies. Visualizations include histograms, scatter plots, correlation matrices, and maps.

### Data Cleaning

Various data cleaning techniques were applied to handle missing values, remove duplicates, and correct data types. This step ensures the data is in a suitable format for analysis and modelling.

### Data Transformation

Data transformation methods such as scaling, normalization, and encoding categorical variables were implemented to prepare the data for machine learning algorithms. Techniques such as StandardScaler and OneHotEncoder were utilized.

### Data Preparation

In this stage, I prepared the data by splitting it into training and testing sets. Techniques like stratified sampling were used to ensure representative splits.

### Transformation Pipelines

Transformation pipelines were created using Scikit-Learn's `Pipeline` and `ColumnTransformer` to streamline the preprocessing steps. This ensures reproducibility and cleaner code.

### Model Fine-Tuning

Several machine learning models were trained and fine-tuned using grid search, random search, and cross-validation. Models include linear regression, decision trees, random forests, and gradient boosting.

### Error Analysis

Different error metrics such as RMSE, MAE, and R^2 were calculated to evaluate model performance. Analysis was done to understand the types and sources of errors, and techniques like cross-validation helped in assessing the models' robustness.
