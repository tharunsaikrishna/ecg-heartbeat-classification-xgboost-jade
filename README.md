# ECG Heartbeat Classification using Optimized XGBoost

This repository contains an implementation of the research paper:  
**"Optimizing machine learning for enhanced automated ECG analysis in cardiovascular healthcare"**  
It focuses on classifying ECG heartbeats using machine learning models with hyperparameter optimization via metaheuristic algorithms (JADE, OriginalJA, Enhanced AEO, LevyJA).

## 🧠 Project Overview

- Dataset: [Kaggle Heartbeat Dataset](https://www.kaggle.com/datasets/shayanfazeli/heartbeat)
- Preprocessing: PCA, Missing Value Imputation, Data Shuffling
- Models Used:
  - Support Vector Classifier (SVC)
  - RandomForest
  - XGBoost
  - LinearSVC
- Optimization Algorithms:
  - JADE
  - OriginalJA
  - LevyJA
  - Enhanced AEO

## 🚀 Highlights

- Achieved an F1-Score of **0.8742** with XGBoost + JADE
- PCA applied to reduce features to 30 dimensions
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score (macro)
