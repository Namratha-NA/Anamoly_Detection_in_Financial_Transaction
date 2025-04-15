# Anomaly Detection in Financial Transactions using ML & Statistical Analysis

## Overview

This project presents a data-driven framework to detect anomalies and fraudulent transactions in financial systems using synthetic transaction data generated by the PaySim simulator. By combining statistical techniques, exploratory data analysis (EDA), and supervised machine learning, the solution demonstrates strong predictive performance for fraud detection in mobile money ecosystems.

## 📊 Dataset

- **Source:** [PaySim Financial Transactions Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)
- **Records:** 6 million+ simulated mobile money transactions
- **Attributes include:**
  - Transaction type (CASH-IN, CASH-OUT, etc.)
  - Transaction amount and balances
  - Fraud indicators: `isFraud` and `isFlaggedFraud`

## 🔍 Key Features

- **Exploratory Data Analysis (EDA)**
  - Summary statistics, skewness, and distribution plots
  - Visualizations: histograms, bar plots, pie charts, heatmaps
  - Correlation matrix and feature relationships

- **Statistical Testing**
  - Chi-square test for fraud-flag relationships
  - t-Test and ANOVA for comparing means between fraud classes
  - Kruskal-Wallis test for non-parametric distribution analysis

- **Machine Learning Models**
  - **Logistic Regression**
    - Achieved **94% accuracy**
    - Strong recall for identifying fraudulent transactions
  - **Feedforward Neural Network (FNN)**
    - Achieved **98% accuracy**
    - Outperformed baseline with high recall and precision
  - **Evaluation Metrics:**
    - Confusion matrix, classification report, ROC-AUC curves

## 🧠 Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras
- **ML Techniques:** Logistic Regression, Feedforward Neural Networks
- **Statistical Tools:** Chi-square, t-Test, ANOVA, Kruskal-Wallis
- **Visualization:** Seaborn heatmaps, ROC plots, confusion matrices

## 🚀 Highlights

- Balanced class representation using sampling strategies to handle imbalance in fraud labels
- Feature engineering and parameter estimation using MLE and RMSE
- ROC-AUC Score: **0.94** (LogReg) and **0.98** (FNN)
- Built with performance, interpretability, and fraud risk mitigation in mind

## 📈 Future Enhancements

- Deploy model into a real-time streaming pipeline
- Explore ensemble models (e.g., Random Forest, XGBoost)
- Integrate explainable AI for financial compliance
- Expand fraud detection use cases across domains
