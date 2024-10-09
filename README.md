# Predicting Diabetes Using Health Indicators

This project explores the use of various machine learning models to predict diabetes status (healthy, pre-diabetic, diabetic) based on health and lifestyle indicators. It aims to identify the most effective model for early diabetes detection, with potential applications in healthcare analytics and public health initiatives.

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Definition](#problem-definition)
3. [Data Sources](#data-sources)
4. [Data Description](#data-description)
5. [Data Exploration](#data-exploration)
6. [Machine Learning Models](#machine-learning-models)
7. [Performance Evaluation](#performance-evaluation)
8. [Project Results](#project-results)

## Introduction

Diabetes is a chronic disease affecting millions globally, with a high financial burden on healthcare systems. This project uses machine learning to analyze health indicators and predict diabetes status to facilitate early intervention.

## Problem Definition

The project aims to build and compare machine learning models that can classify individuals as diabetic, pre-diabetic, or healthy based on survey data. Key research questions include:
- Which health indicators are most predictive of diabetes?
- How do different machine learning models compare in predicting diabetes?
- Can model performance be improved by integrating various data or feature engineering?

## Data Sources

The data used in this project is sourced from:
- [CDC](https://www.cdc.gov/pcd/issues/2019/19_0109.htm)
- [Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset/data)

This dataset comprises demographic information, health behaviors, chronic conditions, and healthcare access indicators for over 253,000 individuals.

## Data Description

The dataset includes the following key variables:
- **Health Indicators**: BMI, high blood pressure, cholesterol levels, etc.
- **Behavioral Factors**: Smoking, physical activity, fruit/vegetable consumption.
- **Demographic Information**: Age, sex, income, education level.

## Data Exploration

Data visualization techniques were used to understand the distribution and correlation of different variables with diabetes status. Key insights include:
- **Correlation Heatmap**: Shows the strength of relationships between health indicators.
- **Boxplots and Bar Plots**: Visualize trends and patterns for BMI, age, income, and other factors.

## Machine Learning Models

The following models were implemented and compared:
- **Decision Trees**
- **Random Forest Classifier**
- **Naive Bayes Classifier**
- **Principal Component Analysis (PCA)**
- **Neural Networks**

Python libraries such as Scikit-learn and TensorFlow were used to build and evaluate these models.

## Performance Evaluation

Models were evaluated using metrics such as accuracy, precision, recall, and F1-score. Key findings include:
- **Neural Network**: Best performance with high recall and F1-score, making it highly reliable for predicting diabetes.
- **PCA**: Excellent recall but with a slightly lower precision.
- **Random Forest**: Balanced performance, reliable in minimizing false positives.

## Project Results

The Neural Network model emerged as the top performer, showcasing strong prediction capabilities. This model can help inform healthcare strategies for early diabetes detection and prevention.
