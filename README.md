# Diabetes-Prediction-ML
End-to-end machine learning project for early diabetes prediction using patient health metrics, featuring data preprocessing, model comparison, and cross-validation.
# 🩺 Diabetes Prediction using Machine Learning

## 📖 Overview
This project aims to predict whether a patient is diabetic based on medical health metrics using machine learning techniques. The model helps in early-stage diabetes detection and supports preventive healthcare decisions.

## 📊 Dataset
- PIMA Indians Diabetes Dataset
- Features include:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- Target:
  - Outcome (0 = Non-Diabetic, 1 = Diabetic)

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🔍 Project Workflow
1. Data loading and understanding
2. Data cleaning and preprocessing (handling invalid zero values)
3. Exploratory Data Analysis (EDA)
4. Feature scaling using StandardScaler
5. Train-test split
6. Model training:
   - Logistic Regression
   - Random Forest Classifier
7. Model evaluation using accuracy, precision, recall, F1-score
8. Cross-validation for robustness
9. Feature importance analysis

## 📈 Results
- Achieved approximately **90% accuracy**
- Random Forest performed better than Logistic Regression
- Glucose and BMI were identified as the most influential features

## 🧠 Key Learnings
- Importance of preprocessing medical data
- Handling imbalanced healthcare outcomes
- Evaluating models beyond accuracy
- Building an end-to-end ML pipeline


