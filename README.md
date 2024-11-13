# DataPredict

This project explores predictive modeling through the application of machine learning algorithms on two datasets: water potability and wine quality. It demonstrates data preprocessing, exploratory data analysis (EDA), and the implementation of multiple classification models to achieve reliable predictions.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Datasets](#datasets)
4. [Machine Learning Models](#machine-learning-models)
5. [Metrics Used](#metrics-used)
6. [Results](#results)
7. [Installation and Setup](#installation-and-setup)

---

## Project Overview

The project utilizes two datasets:
1. **Water Potability Dataset:** Predicts whether water is potable or not.
2. **Wine Quality Dataset:** Predicts wine quality on a scale from 1 to 10.

Various preprocessing techniques are applied, including handling missing values, managing outliers, balancing datasets using SMOTE, and scaling features. Models like Support Vector Machines (SVM), Neural Networks (NN), and Random Forest are implemented and evaluated.

---

## Key Features

- **Comprehensive EDA:** Includes data visualization, correlation analysis, and insights on feature distributions.
- **Data Preprocessing:** Techniques such as missing value imputation, outlier handling, and oversampling for class imbalance.
- **Multi-Model Approach:** Implements SVM, Neural Networks, and Random Forest for comparison.
- **Metrics Evaluation:** Evaluates models using accuracy, F1-score, and recall to gauge performance.
- **Scalable Framework:** The project supports integration with other datasets and classification models.

---

## Datasets

1. **Water Potability Dataset:**
   - Contains 10 features, including pH, hardness, solids, and potability (target variable: potable or not potable).
   - Challenges: Missing values and imbalanced data distribution.

2. **Wine Quality Dataset:**
   - Includes 12 features such as acidity, sugar, alcohol, and wine quality (target variable: scale of 1–10).
   - Challenges: Highly imbalanced data and inter-feature correlations.

---

## Machine Learning Models

1. **Support Vector Machines (SVM):**
   - Optimized using hyperparameters like regularization (`C`) and kernel types (`linear` and `rbf`).
   - Handles oversampling and feature scaling for better performance.

2. **Neural Networks (NN):**
   - Implements different architectures with hyperparameters like hidden layer sizes and maximum iterations.
   - Employs PCA for dimensionality reduction in some scenarios.

3. **Random Forest:**
   - Tunes hyperparameters such as tree depth, split criteria (`gini` and `entropy`), and class weights.
   - Outperforms other models in most cases due to its robustness to overfitting.

---

## Metrics Used

1. **Accuracy:** Measures the percentage of correct predictions.
2. **F1-Score:** Balances precision and recall to evaluate the model’s reliability.
3. **Recall:** Evaluates the ability to correctly identify true positive instances.

---

## Results

### Water Potability Dataset
| **Model**          | **Accuracy** | **F1-Score** | **Recall** |
|---------------------|--------------|--------------|------------|
| SVM (Oversampling)  | 66%          | 66%          | 67%        |
| Neural Network      | 64%          | 64%          | 64%        |
| Random Forest       | 76%          | 70%          | 68%        |

### Wine Quality Dataset
| **Model**          | **Accuracy** | **F1-Score** | **Recall** |
|---------------------|--------------|--------------|------------|
| SVM (PCA)           | 81%          | 80%          | 81%        |
| Neural Network      | 79%          | 79%          | 79%        |
| Random Forest       | 87%          | 87%          | 87%        |

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/andreecunha/Data-Insights.git
