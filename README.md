🔥 CalorieAI — AI-Powered Calorie Burn Prediction System

An end-to-end Machine Learning project that predicts calories burned during exercise using physiological and workout-related features such as age, heart rate, duration, body metrics, etc.

🚀 Project Overview

CalorieAI is a complete ML pipeline + interactive web application that:

📊 Performs Exploratory Data Analysis (EDA)
🤖 Trains multiple ML models
🏆 Selects the best-performing model
📈 Visualizes model performance
🌐 Deploys an interactive UI using Streamlit
🧠 Problem Statement

Accurately estimating calories burned is important for:

Fitness tracking 🏋️‍♀️
Weight management ⚖️
Health monitoring ❤️

This project uses machine learning to predict calorie expenditure based on user inputs.

📂 Dataset
~15,000 records
Features include:
Age
Gender
Height & Weight
Duration of exercise
Heart Rate
Body Temperature

⚙️ Features & Pipeline
🔍 1. Exploratory Data Analysis (EDA)
Distribution of calories burned
Relationship between:
Duration vs Calories
Heart Rate vs Calories
Age vs Calories
Correlation heatmap
🛠️ 2. Feature Engineering
BMI calculation
Derived physiological features
Data preprocessing & encoding
🤖 3. Models Trained
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
📊 4. Model Evaluation

Metrics used:

R² Score
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
Cross-validation (5-fold)

🏆 Best model is automatically selected based on performance.

📈 5. Visualization
Actual vs Predicted comparison
Model performance comparison
Feature importance analysis
🌐 Streamlit Web App

An interactive UI where users can:

✅ Predict Calories

Input:

Age, Gender
Height, Weight
Exercise Duration
Heart Rate
Body Temperature

Output:

🔥 Calories burned
📊 Intensity level
💪 BMI & Heart Rate Zone
📉 Feature importance
📊 Additional Features
EDA Dashboard
Model Performance Dashboard
Batch Prediction via CSV upload
Prediction History tracking

📦 Tech Stack
Python 🐍
Pandas & NumPy
Scikit-learn
XGBoost
Matplotlib & Seaborn
Streamlit

📌 Key Highlights
End-to-end ML pipeline
Multiple model comparison
Real-time prediction UI
Feature engineering + EDA
Clean and production-ready structure

💡 Future Improvements
Deploy on cloud (AWS / GCP / Azure)
Add wearable device integration
Use Deep Learning models
Personalized fitness recommendations
