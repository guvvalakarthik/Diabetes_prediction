# Diabetes Prediction System 🩺

This project is a Machine Learning–based Diabetes Prediction system that predicts whether a person is diabetic based on medical parameters.  
The model is trained using a Support Vector Machine (SVM) algorithm and deployed as a web application using Streamlit.

---

## 📌 Project Overview
- Dataset collected from Kaggle using Kaggle API
- Data preprocessing and standardization performed
- Machine learning model trained using SVM
- Model saved using Pickle (`.sav`)
- Web application built using Streamlit

---

## 🧠 Machine Learning Model
- **Algorithm:** Support Vector Machine (SVM)
- **Preprocessing:** StandardScaler
- **Model Saving Format:** `.sav` (Pickle)

---

## 📊 Dataset
- **Source:** Kaggle
- **Features Used:**
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target Variable:** Outcome (0 → Non-Diabetic, 1 → Diabetic)

---

## ⚙️ Preprocessing Steps
- Checked for missing values
- Feature-target separation
- Feature scaling using `StandardScaler`
- Train-test split for model training and evaluation

---

## 🌐 Deployment
The trained SVM model is deployed using **Streamlit**, allowing users to input medical details and get real-time predictions.

---

## ▶️ How to Run the Project Locally

### 1️⃣ Clone the repository
```bash
git clone <your-github-repo-link>
cd diabetes_prediction_project

##Install dependencies
pip install -r requirements.txt
##run streamlit app 
streamlit run app.py
