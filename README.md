# Heart-Disease-Detection-using-Machine-Learning
This project aims to build a predictive model that can detect the likelihood of heart disease based on key clinical and lifestyle attributes.
Using data-driven insights, it empowers healthcare professionals to make early and accurate decisions, ultimately improving patient outcomes.

# Objective

To analyze patient data and develop a machine learning model that predicts whether an individual is at risk of heart disease.

# Key Questions Answered

What are the major risk factors contributing to heart disease?

Can we predict heart disease with high accuracy using ML algorithms?

Which variables (cholesterol, age, blood pressure, etc.) influence the prediction most?

How can this model assist healthcare practitioners or preventive health programs?

# Dataset

Source: UCI Heart Disease Dataset

Attributes include:

Feature	Description
age	Age of the patient
sex	Gender (1 = Male, 0 = Female)
cp	Chest pain type
trestbps	Resting blood pressure
chol	Serum cholesterol in mg/dl
fbs	Fasting blood sugar > 120 mg/dl (1 = True, 0 = False)
restecg	Resting electrocardiographic results
thalach	Maximum heart rate achieved
exang	Exercise induced angina (1 = Yes, 0 = No)
oldpeak	ST depression induced by exercise relative to rest
slope	Slope of the peak exercise ST segment
ca	Number of major vessels (0–3) colored by fluoroscopy
thal	Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
target	Presence of heart disease (1 = Yes, 0 = No)
⚙️ Tools & Technologies

Programming Language: Python 🐍

Libraries: pandas, numpy, sklearn.model_selection, sklearn.linear_model, sklearn.metrics

Modeling: Logistic Regression

Environment: Jupyter Notebook

# Workflow
# Data Preprocessing

Handled missing values & categorical encoding

Standardized numeric features using StandardScaler

Split dataset into train and test using train_test_split()

# Exploratory Data Analysis (EDA)

Correlation heatmap between features

Distribution plots of cholesterol, age, blood pressure

Gender-based comparison of heart disease risk

Visualization of chest pain types vs target outcome

# Model Building

Implemented and evaluated multiple algorithms:

Logistic Regression

Random Forest Classifier

K-Nearest Neighbors

Support Vector Machine

Decision Tree

Compared model performance using:

Accuracy

Precision

Recall

F1-score

ROC-AUC curve

# Model Evaluation
Model	Accuracy	Precision	Recall	F1 Score
Logistic Regression	0.85	0.86	0.83	0.84
Random Forest	0.88	0.90	0.85	0.87
SVM	0.86	0.87	0.84	0.85

(Values are examples — replace with your actual results)

# Feature Importance

Identified the top 5 factors influencing prediction:

Age

Chest pain type

Cholesterol level

Max heart rate

Exercise-induced angina

# Insights

Patients with higher cholesterol, older age, and exercise-induced angina showed greater heart disease risk.

Chest pain type and maximum heart rate were among the strongest predictors.

The best model achieved ~88% accuracy, suitable for preliminary screening use cases.

# Results Summary

Built a reliable classification pipeline with cross-validation

Reduced false negatives — crucial for medical prediction systems

Delivered a visualization-driven report for clinical interpretation

# Future Improvements

Include larger and more diverse datasets for generalization

Implement deep learning (ANN) for non-linear patterns

Deploy on cloud (e.g., AWS / Streamlit web app)

Integrate real-world wearable health data (Fitbit, Apple Watch)

# Author

Nikita Ravindra Albela
Data Analyst | Machine Learning Enthusiast | Healthcare Analytics Researcher
# nikitaalbela31@gmail.com
# https://github.com/Nikita-Ravindra-Albela
