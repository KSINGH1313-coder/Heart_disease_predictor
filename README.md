# ❤️ Heart Disease Prediction System

The **Heart Disease Prediction System** is a machine learning web application that predicts whether a person is likely to have heart disease based on medical attributes. The system helps in early diagnosis and preventive healthcare by analyzing key indicators like age, blood pressure, cholesterol, and more.

## 🚀 Features

- Predicts the presence of heart disease (Yes/No)
- Simple and interactive web interface built with Flask
- Uses machine learning models like **Logistic Regression**, **Random Forest**, and **XGBoost**
- Fast, lightweight, and user-friendly application
- Takes real medical input parameters (based on UCI dataset)

## 🧠 ML Model Overview

Trained on the **UCI Heart Disease Dataset**, the model uses these input parameters:

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Serum Cholesterol  
- Fasting Blood Sugar  
- Resting ECG Results  
- Max Heart Rate Achieved  
- Exercise Induced Angina  
- ST Depression  
- Slope of ST Segment  
- Number of Major Vessels  
- Thalassemia

The models output a binary prediction: `0` (No heart disease) or `1` (At risk of heart disease).

## 🖥️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Flask
- **ML Libraries**: Scikit-learn, XGBoost, Pandas, NumPy
- **Deployment**: Localhost / Render / Heroku (Optional)
