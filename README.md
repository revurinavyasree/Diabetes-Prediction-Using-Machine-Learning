# Diabetes-Prediction-Using-Machine-Learning

## Project Overview

This project predicts whether a person is diabetic or not using Machine Learning. The model is trained on the Pima Indians Diabetes Dataset and uses various health-related features such as glucose level, blood pressure, BMI, insulin level, and age.

The objective of this project is to understand the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

---

## Dataset Features

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target Variable

* Outcome

  * 0 = Not Diabetic
  * 1 = Diabetic

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib

---

## Project Workflow

1. Data Loading
2. Data Exploration
3. Data Visualization
4. Feature Selection
5. Train-Test Split
6. Logistic Regression Model Training
7. Model Evaluation
8. Diabetes Prediction
9. Model Saving

---

## Visualizations

* Diabetes Distribution
* Glucose Level vs Diabetes
* Correlation Heatmap
* Confusion Matrix

---

## Model Performance

* Algorithm: Logistic Regression
* Accuracy Score: 74.6%

The model successfully classifies diabetic and non-diabetic patients based on medical attributes.

---

## Sample Prediction

Input:

* Pregnancies: 6
* Glucose: 148
* Blood Pressure: 72
* Skin Thickness: 35
* Insulin: 0
* BMI: 33.6
* Diabetes Pedigree Function: 0.627
* Age: 50

Prediction:

**Diabetic**

---

## Project Structure

Diabetes-Prediction-Using-Machine-Learning/

├── diabetes_prediction.ipynb

├── diabetes_model.pkl

├── README.md

├── requirements.txt

├── dataset/

│ └── diabetes.csv

└── screenshots/

---

## Future Improvements

* Random Forest Classifier
* XGBoost Classifier
* Hyperparameter Tuning
* Streamlit Web Application
* Model Deployment

---

## Author

Navya Sree Revuri
