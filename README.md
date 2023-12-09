# Jupyter Notebook Analysis: "Titanic In-Depth Analysis and KNN from Scratch"
#### Mirror from Kaggle: [Titanic In-Depth Analysis and KNN from Scratch](https://www.kaggle.com/code/jbfriedli/titanic-in-depth-analysis-and-knn-from-scratch)
#### Focus: K-Nearest Neighbors (KNN) Algorithm from Scratch

## Overview

This Jupyter Notebook provides an in-depth analysis of the Titanic dataset and demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm from scratch. It includes data loading, exploration, visualization, preprocessing, model building, and submission.

### 🛬 Import Section
- Libraries: `sqrt` (math), `numpy`, `pandas`, `os`, `matplotlib.pyplot`, `seaborn`, `wordcloud`, `sklearn`, `scipy`.
- Purposes: Data manipulation, statistical analysis, visualization, machine learning, and distance calculations.

### 💾 Load Data
- Data Source: Kaggle's Titanic dataset.
- Files: `train.csv`, `test.csv`, `gender_submission.csv`.
- Dataframes: `df_train` and `df_test`.

### 👀 Data Exploration
- Examining data structure, types, and initial insights.
- Key observations on features like `Pclass`, `Sex`, `Ticket`, `Cabin`, `Embarked`, etc.

### 📝 Key Observations
- Analysis of features' value ranges, uniqueness, and potential transformations.
- Categorical feature handling: Mapping and one-hot encoding.

### 📊 Data Visualization
- Exploratory visualizations for features like `Survived`, `Sex`, `Pclass`, `Age`, `SibSp`, `Parch`, `Fare`, and `Embarked`.
- Correlation matrix to understand feature relationships.

### ⚙️ Pre Processing
- Imputing missing values and handling NaNs.
- Normalizing and scaling numeric data.
- One-hot encoding of categorical data.
- Preparing train and test datasets for the model.

### 🧰 Model: K-Nearest Neighbors (KNN)
- Custom implementation of KNN algorithm.
- Euclidean distance calculation.
- Vectorized approach for performance optimization.
- Finding the best `k` value through brute force.

### 📨 Submission
- Preparing the submission file based on the KNN model predictions.
