# Heart Disease Prediction using Machine Learning

## Project Overview
This project leverages machine learning techniques to predict the presence or absence of heart disease based on clinical features such as age, cholesterol levels, blood pressure, and other health indicators. The goal of the project is to build a model that can help in early detection of heart disease.

## Dataset
The dataset used for this project contains clinical data for heart disease prediction, with features including:
- Age
- Sex
- ChestPainType
- Resting Blood Pressure (RestingBP)
- Cholesterol Levels
- Fasting Blood Sugar (FastingBS)
- Maximum Heart Rate (MaxHR)
- Exercise-Induced Angina (ExerciseAngina)
- Oldpeak (Depression in ST segment)
- ST Slope

## Key Features
- Data Preprocessing: Cleaned and encoded categorical variables.
- Modeling: Multiple machine learning models were trained, including Random Forest.
- Evaluation: The performance was evaluated using accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.
- Visualization: The project includes various visualizations like feature importance, confusion matrix, and ROC curve.

## Objective
The model predicts the likelihood of heart disease based on clinical data. The goal is to help healthcare professionals make informed decisions and provide early interventions.

## Model Performance
- Accuracy: 86.4%
- Precision: 0.82 (Class 0), 0.89 (Class 1)
- Recall: 0.84 (Class 0), 0.87 (Class 1)
- F1-Score: 0.83 (Class 0), 0.88 (Class 1)

### Confusion Matrix
The confusion matrix shows how well the model distinguishes between heart disease and no heart disease.

### ROC Curve and AUC
The ROC curve indicates the model's ability to differentiate between the two classes, with a high Area Under the Curve (AUC).

## Future Work
- Further hyperparameter tuning to improve the model’s performance.
- Experimenting with different machine learning algorithms such as Support Vector Machines and Gradient Boosting.
- Deploying the model as a web application for real-time predictions.

## Getting Started
To run this project locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/Biruk34/Healthcare-diabetics.git
