# 🩸 Diabetes Type Identifier: EHR Phenotype Engine

![Status](https://img.shields.io/badge/Status-Active-success.svg)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-Ensemble_Classifier-blue.svg)
![Domain](https://img.shields.io/badge/Domain-HealthTech_&_Precision_Medicine-orange.svg)
![UI](https://img.shields.io/badge/UI-Interactive_Dashboard-purple.svg)

## 📌 Project Overview
The **Diabetes Type Identifier** is a clinical decision support dashboard designed to go beyond binary "diabetic/non-diabetic" predictions. Instead, it acts as a phenotype engine that classifies the *specific type* of diabetes (Type 1, Type 2, MODY, or Gestational) based on a patient's Electronic Health Record (EHR) data.

Powered by an ensemble machine learning classifier, this tool not only predicts the disease subtype but also provides **Explainable AI (XAI)** by displaying the exact feature importance that led to the model's conclusion.

## 📸 Dashboard Preview
![Diabetes Phenotype Engine UI](images/diabetes-identifier.png) *(Note: Create an `images` folder in your repo, upload your screenshot there, and update this link!)*

## ✨ Key Features
* **Multi-Class Phenotyping:** Predicts between Type 1, Type 2, MODY (Maturity-Onset Diabetes of the Young), and Gestational diabetes.
* **Probability Distribution:** Displays the model's confidence levels across all potential classifications to assist in nuanced clinical decisions.
* **Explainable AI (Feature Impact):** Real-time visualization of which clinical features (e.g., Medication, Family History, Age) drove the prediction.
* **Comprehensive Inputs:** Processes 6 key clinical features:
  * *Demographics:* Age at Onset, BMI
  * *Biomarkers:* Fasting Glucose (mg/dL), HbA1c (%)
  * *History:* Family History, Current Medication

## 🛠️ Technologies Used
* **Machine Learning:** [Python, Scikit-Learn, XGBoost/Random Forest (Ensemble Methods)]
* **Data Processing:** [Pandas, NumPy]
* **Frontend/UI:** [Streamlit / Dash / React]
* **Explainability:** [SHAP / Feature Importances]
