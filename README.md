# Diabetes Risk Prediction System using Machine Learning

A robust, end-to-end Machine Learning pipeline utilizing a **Support Vector Machine (SVM)** classifier to predict whether a patient has diabetes based on diagnostic measurements. 

## 📋 Project Overview
Early detection of chronic conditions like diabetes is crucial for healthcare intervention. This project implements a binary classification model that achieves high accuracy by properly handling data preparation, feature engineering (standardization), and model evaluation.

## 📊 Dataset Description
The model is trained on the classic **PIMA Diabetes Dataset** from the National Institute of Diabetes and Digestive and Kidney Diseases. The dataset consists of 768 patient records with 8 medical predictor features and 1 target variable (`Outcome`):

* **Pregnancies:** Number of times pregnant
* **Glucose:** Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* **BloodPressure:** Diastolic blood pressure (mm Hg)
* **SkinThickness:** Triceps skin fold thickness (mm)
* **Insulin:** 2-Hour serum insulin (mu U/ml)
* **BMI:** Body mass index (weight in kg/(height in m)^2)
* **DiabetesPedigreeFunction:** Diabetes pedigree function (genetic score)
* **Age:** Age (years)
* **Outcome:** Class variable (0 = Non-diabetic, 1 = Diabetic)

## 🛠️ Tech Stack & Methodology
* **Language:** Python 3.x
* **Libraries:** `Pandas`, `NumPy`, `Scikit-Learn`
* **Data Preprocessing:** Handled scale variance across biomedical features using `StandardScaler` to ensure optimal performance for the distance-based classifier.
* **Model:** Support Vector Machine (SVM) Classifier with a Linear Kernel.
* **Evaluation:** Stratified 80/20 train-test split evaluated using standard Classification Accuracy.

## 🚀 How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/EshitaG05/Diabetes-Risk-Prediction-System.git](https://github.com/EshitaG05/Diabetes-Risk-Prediction-System.git)
