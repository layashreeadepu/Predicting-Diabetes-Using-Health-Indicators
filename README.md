# Predicting Diabetes Using Health Indicators

## 🧠 Overview

This project investigates the application of various machine learning models to predict diabetes status (healthy, pre-diabetic, diabetic) based on individual health and lifestyle indicators. It aims to identify the most effective model for early detection, supporting healthcare analytics and public health initiatives.

## 💡 Business Problem

Diabetes is a chronic disease impacting millions globally and straining healthcare systems with significant financial costs. Early prediction of diabetes risk based on accessible health indicators can enable timely interventions, reducing long-term complications and treatment expenses.

## 📚 Data Sources

- [Centers for Disease Control and Prevention (CDC)](https://www.cdc.gov/pcd/issues/2019/19_0109.htm)
- [Kaggle Dataset - Diabetes Health Indicators](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)

The dataset includes demographic, behavioral, and clinical health information for over 253,000 individuals.

## 🗂️ Data Description

Key features from the dataset:
- **Health Indicators**: BMI, blood pressure, cholesterol levels, diabetes status.
- **Behavioral Factors**: Smoking habits, physical activity levels, dietary patterns.
- **Demographics**: Age, gender, income bracket, education level.

## 📊 Data Exploration

Exploratory Data Analysis (EDA) was conducted to uncover relationships and patterns:
- **Correlation Heatmaps** to identify strong predictors of diabetes.
- **Boxplots and Bar Charts** to visualize trends across BMI, age groups, and income levels.

## 🛠️ Methodology

A variety of machine learning models were implemented and compared to identify the optimal approach:
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Naive Bayes Classifier**
- **Principal Component Analysis (PCA)**
- **Neural Networks**

Feature engineering and scaling were applied to optimize model performance. Python libraries such as **Scikit-learn** and **TensorFlow** were utilized.

## 📏 Evaluation Metrics

Model performance was assessed based on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

Key observations:
- **Neural Networks** achieved the best recall and F1-score, making them highly reliable for early detection.
- **PCA** maintained excellent recall but slightly compromised on precision.
- **Random Forest** offered a balanced trade-off between precision and recall.

## 🚀 Results

The Neural Network model emerged as the most effective, demonstrating robust prediction capabilities across evaluation metrics. These insights have potential applications in healthcare systems aiming for early identification and preventive management of diabetes.
