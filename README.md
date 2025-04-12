# ❤️ Heart Disease Prediction Using Machine Learning

This project predicts the presence of heart disease in patients using clinical parameters. It leverages two powerful machine learning models — **Random Forest** and **XGBoost** — optimized for performance and interpretability.

---

## 🧠 Overview

This notebook-based application predicts whether a patient is likely to develop heart disease based on various health indicators like age, cholesterol, chest pain type, etc. The model is trained on a preprocessed dataset and handles class imbalance using **SMOTE**.

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- imbalanced-learn (SMOTE)  
- XGBoost  
- ipywidgets (for interactive UI in Jupyter/Colab)  

---

## 📂 Dataset

The dataset used for training and testing was sourced from **Kaggle**:

🔗 **[Heart Disease UCI Dataset on Kaggle](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)**

It contains patient records with the following features:
- age
- sex
- chest_pain_type
- resting_blood_pressure
- cholestoral
- fasting_blood_sugar
- rest_ecg
- Max_heart_rate
- exercise_induced_angina
- oldpeak
- slope
- vessels_colored_by_flourosopy
- thalassemia
- **target** (0 = No Heart Disease, 1 = Heart Disease)

---

## ✨ Features

- 📊 **Exploratory Data Analysis** and preprocessing
- 🔍 **Label Encoding** of categorical variables
- ⚖️ **Class Balancing** using SMOTE
- 🧪 Model Training:
  - **Random Forest** (with hyperparameter tuning to avoid overfitting)
  - **XGBoost** (with regularization)
- ✅ **Cross-validation** for generalization check
- 🧠 **Feature Importance** plot for interpretability
- 🔵 **Interactive User Input Interface** using `ipywidgets` in notebooks

---

## 📈 Model Evaluation

### 🔹 Random Forest
- Training Accuracy: High
- Testing Accuracy: Good generalization
- Classification Report, Confusion Matrix included

### 🔹 XGBoost
- Testing Accuracy: Competitive with RF
- Cross-validation used for both models

---

## 🖥️ User Interface

A simple input form is created using `ipywidgets`, allowing users to:
- Enter patient details (age, sex, cholesterol, etc.)
- Click **"Check Heart Disease"**
- Get real-time prediction (🟢 or 🔴)

---

## ▶️ How to Run

1. Download the dataset from Kaggle and place it in your environment (e.g., Google Drive or local).
2. Open the notebook in **Google Colab** or **Jupyter Notebook**.
3. Run all cells in order.
4. Enter patient details in the widget-based interface.
5. Click the button to get prediction.

---

