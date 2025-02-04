# Breast Cancer Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2.2-green)
![License](https://img.shields.io/badge/License-MIT-orange)

## 📌 Overview  
Early and accurate detection of breast cancer significantly improves patient outcomes. This project leverages a **publicly available breast cancer dataset** to build an AI-driven classification model that predicts tumor malignancy (malignant/benign). Through exploratory data analysis (EDA), feature engineering, and machine learning, the project aims to provide healthcare professionals with a reliable decision-support tool.

## 🎯 Key Features  
- **Exploratory Data Analysis (EDA)**:  
  - Analyzed feature distributions, correlations, and class imbalance.  
  - Visualized insights using heatmaps, pairplots, and boxplots.  
- **Data Preprocessing**:  
  - Dropped irrelevant columns (`id`).  
  - Mapped categorical `diagnosis` labels (M/B) to numerical values (1/0).  
  - Handled missing values and scaled features using `StandardScaler`.  
- **Dimensionality Reduction**: Applied **PCA** to reduce noise and improve model efficiency.  
- **Machine Learning Model**: Trained a **Random Forest Classifier** with hyperparameter tuning for optimal performance.  
- **Model Evaluation**: Reported accuracy, precision, recall, and visualized results via confusion matrices and ROC curves.  

## 📂 Dataset  
**Source**: [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))  
- **569 samples** with **32 features**, including:  
  - Target: `diagnosis` (Malignant "M" / Benign "B").  
  - Key Measurements: `radius_mean`, `texture_mean`, `perimeter_mean`, `area_mean`, etc.  

## 🛠️ Technologies Used  
- **Python** (Pandas, NumPy) for data manipulation.  
- **Matplotlib** and **Seaborn** for visualization.  
- **Scikit-Learn** for PCA, Random Forest, and model evaluation.  
- **Jupyter Notebook** for interactive analysis.  
