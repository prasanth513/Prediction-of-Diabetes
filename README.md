# Prediction of Diabetes using Machine Learning

A machine learning classification project that predicts whether a patient has diabetes based on diagnostic measurements.

## 📌 Overview
Early detection of diabetes is critical for effective management and treatment. This project analyzes medical predictor variables—such as glucose levels, BMI, insulin, and age—to build and evaluate predictive classification models.

## 📊 Dataset
This project uses the **Pima Indians Diabetes Dataset** (or a similar clinical dataset), which includes the following features:
* **Pregnancies:** Number of times pregnant
* **Glucose:** Plasma glucose concentration (2 hours in an oral glucose tolerance test)
* **BloodPressure:** Diastolic blood pressure (mm Hg)
* **SkinThickness:** Triceps skin fold thickness (mm)
* **Insulin:** 2-Hour serum insulin (mu U/ml)
* **BMI:** Body mass index (weight in kg/(height in m)^2)
* **DiabetesPedigreeFunction:** Diabetes pedigree function (genetic influence score)
* **Age:** Age in years
* **Outcome:** Class variable (`0` = Non-Diabetic, `1` = Diabetic)

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## ⚙️ Workflow & Methodology
1. **Data Preprocessing:** Handling missing or zero values in medical columns (e.g., Glucose, Blood Pressure, BMI) and applying feature scaling (`StandardScaler`).
2. **Exploratory Data Analysis (EDA):** Visualizing feature distributions, correlation heatmaps, and class balance.
3. **Model Training:** Training and comparing classification algorithms such as:
   * Logistic Regression
   * Support Vector Machine (SVM)
   * Random Forest Classifier
   * K-Nearest Neighbors (KNN)
   * Decision Tree / XGBoost
4. **Evaluation:** Assessing model performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn