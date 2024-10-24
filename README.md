# Semiconductor Manufacturing Outcome Prediction

This project focuses on predicting the success or failure of semiconductor manufacturing processes using sensor data. The data includes several features collected during the manufacturing process, and the target variable indicates whether the process was successful or not.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Dependencies](#dependencies)
- [License](#license)

## Overview
The goal of this project is to predict whether a semiconductor manufacturing process will result in a pass or fail. The dataset contains features from sensors that track different stages of the process. Data preprocessing, feature selection, and multiple machine learning algorithms are applied to build a predictive model.

## Dataset
The dataset contains 590 features representing sensor readings and the target column:
- **Pass/Fail**: Binary outcome of the semiconductor manufacturing process (1 = Pass, -1 = Fail)

## Project Workflow
1. **Data Loading**: Load the sensor data from a CSV file.
2. **Data Preprocessing**: Handle missing values, drop unnecessary columns, and normalize the data.
3. **Exploratory Data Analysis (EDA)**: Analyze and visualize the distribution of features and the target variable.
4. **Feature Selection**: Identify the most important features that influence the target variable.
5. **Modeling**: Train multiple machine learning models including:
   - Random Forest Classifier
   - Naive Bayes Classifier
   - Support Vector Machine (SVM)
6. **Evaluation**: Evaluate model performance using accuracy, precision, recall, and F1-score.
7. **Prediction**: Use the best model to predict future outcomes of semiconductor processes.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/semiconductor-outcome-prediction.git
