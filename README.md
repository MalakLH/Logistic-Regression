# Heart Failure Prediction using Logistic Regression

## Project Overview

This project implements a Logistic Regression classifier to predict heart failure outcomes using the Heart Failure Clinical Records dataset from Kaggle. The goal is to build an accurate predictive model by applying various data preprocessing and model optimization techniques.

## Dataset

The dataset used is the **Heart Failure Clinical Records Dataset** from Kaggle, containing medical records with various clinical features that may indicate heart failure.

## Techniques Implemented

### Data Preprocessing
- **Encoding Data**: Converted categorical variables into numerical format
- **Standardization**: Applied feature scaling using StandardScaler to normalize features

### Model Optimization
- **Number of Iterations**: Tuned the maximum number of iterations for convergence
- **Penalty (Regularization)**: Experimented with L1 (Lasso) and L2 (Ridge) regularization
- **Class Weight**: Addressed class imbalance using balanced class weights
- **C Parameter**: Optimized the inverse regularization strength parameter
- **Cross-Validation**: Used k-fold cross-validation for robust evaluation

### Model Evaluation
- **Confusion Matrix**: Generated to visualize and verify model performance
- **Multiple Metrics**: Evaluated using accuracy, precision, recall, and F1-score
