# Diabetes Prediction Project Readme

## Introduction

Hello, everyone! In this readme file, I will provide an overview of the project, the dataset, the steps I took, and the results obtained.

## Project Overview

### Dataset
The dataset contains information related to diabetes and includes the following columns:

0. Pregnancies
1. Glucose
2. BloodPressure
3. SkinThickness
4. Insulin
5. BMI
6. DiabetesPedigreeFunction
7. Age
8. Outcome

### Objective
The primary goal of this project is to predict whether a person has diabetes (labeled as 1) or not (labeled as 0) based on various health-related features. I employed data cleaning, preprocessing techniques, and utilized different classification models for this task.

## Project Steps

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
3. Modeling
4. Evaluation

## Model Evaluation

Evaluated each model using the following metrics:

- Decision Tree Classifier
- Bagging Classifier
- Random Forest Classifier
- K-Nearest Neighbors Classifier
- Logistic Regression

Metrics:
- Accuracy
- **Classification Report:** Precision, Recall, F1-Score.

## Conclusion

After extensive evaluation, the K-Nearest Neighbors Classifier (n_neighbors=8) emerged as the best-performing model. Here are the key findings:

- **Accuracy Scores:**
  - Train score: 78%
  - Test score: 78%

- **F1 Scores:**
  - Positive class (1): 0.84
  - Negative class (0): 0.68

- **Area Under the ROC Curve (AUC):**
  - AUC: 0.77

These results indicate that the K-Nearest Neighbors model is suitable for predicting diabetes status from the given features.

## Running the Project

To run this project on your own, follow these steps:
1. Load the dataset from the provided link.
2. Execute each cell in the notebook sequentially.
3. Make sure to install any required packages if prompted.
4. Review the results and explore visualizations in the notebook.

## Python Packages Used

- pandas
- numpy
- seaborn
- scikit-learn
- imbalanced-learn

Ensure you have these packages installed before running the notebook. You can install them using this command:
```bash
pip install pandas numpy seaborn scikit-learn imbalanced-learn
