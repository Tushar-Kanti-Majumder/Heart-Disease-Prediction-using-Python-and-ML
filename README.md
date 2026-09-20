# 🫀 Heart Disease Prediction

This repository contains a machine learning project for predicting heart disease using clinical patient features.

## 📌 Project Overview
Heart disease remains one of the leading causes of mortality globally. Early detection through predictive modeling can assist medical professionals in identifying high-risk patients promptly. This project explores various clinical attributes to build a supervised classification model that predicts the presence or absence of heart disease.

## 🛠️ Tech Stack & Dependencies
* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 📊 Dataset Attributes
The dataset includes the following clinical attributes:

1. **Age:** Age in years
2. **Sex:** Gender (1 = Male, 0 = Female)
3. **Chest Pain Type (cp):**
   * 0: Typical Angina
   * 1: Atypical Angina
   * 2: Non-anginal Pain
   * 3: Asymptomatic
4. **Resting BP (trestbps):** Resting blood pressure (in mm Hg on admission to the hospital)
5. **Cholesterol (chol):** Serum cholesterol in mg/dl
6. **Fasting Blood Sugar (fbs):** Fasting blood sugar > 120 mg/dl (1 = True, 0 = False)
7. **Resting ECG (restecg):**
   * 0: Normal
   * 1: Having ST-T wave abnormality
   * 2: Showing probable or definite left ventricular hypertrophy
8. **Max Heart Rate (thalach):** Maximum heart rate achieved
9. **Exercise Induced Angina (exang):** (1 = Yes, 0 = No)
10. **ST Depression (oldpeak):** ST depression induced by exercise relative to rest
11. **Slope:** The slope of the peak exercise ST segment
12. **Major Vessels (ca):** Number of major vessels (0-3) colored by fluoroscopy
13. **Thalassemia (thal):** 1 = Normal, 2 = Fixed Defect, 3 = Reversible Defect
14. **Target:** 1 = Disease detected, 0 = Healthy

## ⚙️ Project Workflow
1. **Data Preprocessing:** Checking for null values, duplicates, and scaling numerical features.
2. **Exploratory Data Analysis (EDA):** Visualizing distributions, feature correlations, and target relationships.
3. **Model Selection & Training:** Evaluating classification models (Logistic Regression, Random Forest, Decision Trees, KNN, SVM).
4. **Evaluation:** Assessing performance using Accuracy, Precision, Recall, and F1-Score metrics.
