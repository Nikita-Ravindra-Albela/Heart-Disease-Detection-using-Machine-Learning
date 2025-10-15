# Heart-Disease-Detection-using-Machine-Learning
This project aims to build a predictive model that can detect the likelihood of heart disease based on key clinical and lifestyle attributes.
Using data-driven insights, it empowers healthcare professionals to make early and accurate decisions, ultimately improving patient outcomes.

# Objective

To analyze patient data and develop a machine learning model that predicts whether an individual is at risk of heart disease.

# Key Questions Answered


Can we predict heart disease with high accuracy using ML algorithms?

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
- Checked the data for anamolies
- Checked the structure and information of the data.
- Split the data for training and testing purpose using supervised machine learning.
- Trained the model by splitting it as per train test algorithm.
- predicted the value and checked the accuracy score -81% (Good to move ahead with the predictive model)
- Added dummy values for prediction and changed the datatype to array. 
- Performed the prediction to further predict if the patient is healthy or needs to consult to a doctor.

# Model Building

Implemented and evaluated train test split:

Logistic Regression


# Results Summary

# Author

Nikita Ravindra Albela
Data Analyst | Machine Learning Enthusiast | Healthcare Analytics Researcher
# nikitaalbela31@gmail.com
# https://github.com/Nikita-Ravindra-Albela
