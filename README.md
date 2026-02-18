# Task 3: Heart Disease Prediction (Binary Classification)

## 📌 Project Objective
The goal of this project is to build a machine learning model to predict whether a person is at risk of heart disease based on their medical health data. This is a binary classification task where the model predicts '1' for heart disease presence and '0' for no disease.

## 📊 Dataset Overview
The dataset used is the **Heart Disease UCI Dataset**. It contains 303 patient records with 14 medical features, including:
* **Age**: Age of the patient.
* **Sex**: Gender (1 = male; 0 = female).
* **CP**: Chest pain type.
* **Trestbps**: Resting blood pressure.
* **Chol**: Serum cholesterol in mg/dl.
* **Target**: Diagnosis of heart disease (1 = Yes, 0 = No).

## 🛠️ Models and Methodology
* **Data Cleaning**: Handled the dataset by checking for missing values (No missing values found).
* **Exploratory Data Analysis (EDA)**: Performed trends analysis using Correlation Matrix, Histograms, and Scatter plots.
* **Feature Scaling**: Used `StandardScaler` to normalize features for better model performance.
* **Algorithm**: Implemented **Logistic Regression** as the primary classification model.

## 📈 Key Results and Findings
* **Model Accuracy**: Achieved a high accuracy of **85.25%** on the test set.
* **ROC-AUC Score**: The model showed excellent discriminative ability with an AUC of **0.93**.
* **Top Features**: The analysis revealed that **Chest Pain Type (cp)**, **Maximum Heart Rate (thalach)**, and **Slope** are the most significant predictors of heart disease.

## 🚀 How to Run
1. Open the Jupyter Notebook/Google Colab.
2. Install dependencies: `pip install pandas seaborn scikit-learn`.
3. Run the cells sequentially to see the data analysis and model performance.
