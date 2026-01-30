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
