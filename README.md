# BMI_AND_METABOLIC_RATE_PREDICTION_SYSTEM
WE PREDICT THE BMI AND THE BMR OF THE PERSON BY GIVING INPUT SUCH AS WEIGTH , HEIGTH , AGE. 
# 🩺 Nexus AI – Health & Metabolic Analysis System

An AI-powered health analysis platform that predicts a user's BMI category, estimates Basal Metabolic Rate (BMR), and provides personalized diet and fitness recommendations using Machine Learning.

---

## 📌 Project Overview

Nexus AI is a machine learning-based healthcare application developed to help users understand their health status through BMI prediction and metabolic analysis.

The application uses a trained Random Forest Classifier to classify BMI into different categories based on height and weight. It also calculates BMR and generates AI-based nutrition and exercise recommendations.

---

## ✨ Features

- 🔐 User Login & Registration
- 🤖 Machine Learning-based BMI Prediction
- 📊 BMI Category Classification
- 🔥 BMR (Basal Metabolic Rate) Estimation
- 🥗 Personalized Diet Plan
- 💪 Exercise Recommendation
- 📈 Macronutrient Distribution
- ⚡ Fast Prediction using Random Forest
- 🎨 Modern Responsive UI

---

## 🛠 Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- FastAPI (API)
- SQLite Database

### Machine Learning
- Scikit-learn
- Random Forest Classifier
- MinMaxScaler
- Pandas
- NumPy
- Joblib

---

## 📂 Project Structure

```
Nexus-AI/
│
├── index.html              # Main Dashboard
├── login.html              # Login/Register Page
├── train_model.py          # Model Training Script
├── bmi.csv                 # BMI Dataset
├── BMR2.csv                # BMR Dataset
├── bmi_model.pkl           # Trained ML Model
├── scaler.pkl              # Feature Scaler
├── nexus_health.db         # SQLite Database
├── README.md
```

---

## ⚙️ Machine Learning Model

Algorithm Used:

- Random Forest Classifier

Input Features:

- Height
- Weight

Target:

- BMI Index Category

Data Preprocessing:

- Missing value removal
- Feature Scaling using MinMaxScaler
- Train-Test Split (75:25)

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Nexus-AI.git
```

Move into project directory

```bash
cd Nexus-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the backend

```bash
uvicorn main:app --reload
```

Open

```
http://127.0.0.1:8000
```

---

## 📥 User Inputs

- Gender
- Age
- Height (cm)
- Weight (kg)

---

## 📤 Outputs

- BMI Category
- BMI Index
- Confidence Score
- BMR
- Daily Calorie Requirement
- Macronutrient Breakdown
- Personalized Diet Goal
- Exercise Recommendation

---

## 🧠 Working Flow

1. User logs into the application.
2. User enters health details.
3. Data is sent to FastAPI.
4. Features are normalized using MinMaxScaler.
5. Random Forest predicts BMI category.
6. BMR is calculated.
7. Diet and exercise recommendations are generated.
8. Results are displayed on the dashboard.

---

## 📊 Model Used

- Random Forest Classifier
- Feature Scaling: MinMaxScaler
- Model Serialization: Joblib

---

## 📸 Screens

- Login Page
- AI Dashboard
- Health Report
- Diet Recommendation
- Fitness Recommendation

(Add screenshots here)

---

## 🎯 Future Improvements

- User Profile Management
- Medical History Tracking
- AI Chat Health Assistant
- Disease Risk Prediction
- Health Progress Graphs
- Wearable Device Integration
- Cloud Deployment
- Multi-language Support

---

## 👨‍💻 Developed By

Ananya Gupta

B.Tech Computer Science Engineering

---

## 📜 License

This project is developed for educational and academic purposes.

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.
