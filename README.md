<<<<<<< HEAD
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
=======
"# Diabetes_prediction" 
# Diabetes Prediction Using Support Vector Machine

## Project Overview
This project implements a machine learning model to predict whether a person is diabetic or non-diabetic based on medical attributes.  
The model is built using a Support Vector Machine (SVM) and evaluated using accuracy score.

---

## Dataset
- Name: Pima Indians Diabetes Dataset
- Source: Kaggle
- Target Variable:
  - 0 – Non-diabetic
  - 1 – Diabetic

### Features
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## Machine Learning Workflow
1. Data loading
2. Data preprocessing and cleaning
3. Feature scaling using StandardScaler
4. Train-test split
5. Model training using Support Vector Machine
6. Model evaluation using accuracy score
7. Prediction

---

## Model Used
Support Vector Machine (SVM)

SVM is a supervised learning algorithm that finds an optimal hyperplane to separate classes with maximum margin, making it suitable for binary classification problems.

---

## Data Preprocessing
- Handled invalid zero values
- Applied feature scaling
- Used fit() on training data
- Used transform() on test data to avoid data leakage

---

## Model Evaluation
The model performance is evaluated using:
- Accuracy Score

---

## How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/guvvalakarthik/Diabetes_prediction.git
>>>>>>> 7857a34cc23469876f7c6ed276b167d445c3bef4
