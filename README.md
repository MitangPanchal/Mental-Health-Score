# 🧠 Mental Health Score Prediction

An end-to-end **Machine Learning web application** that predicts a mental health score based on user-provided information.

The project combines a **Machine Learning model + preprocessing pipeline + backend API + HTML/CSS/JavaScript frontend** to provide an interactive prediction experience.

---

## 📌 Project Overview

The goal of this project is to build a complete ML application that takes user inputs, processes them through a trained machine learning pipeline, and predicts a **Mental Health Score**.

### 🔄 Workflow

```text
User Input
    ↓
HTML / CSS / JavaScript UI
    ↓
Backend API
    ↓
Data Preprocessing Pipeline
    ↓
Trained ML Model
    ↓
Mental Health Score
    ↓
Result displayed on UI
```

---

## ✨ Features

* 🧠 Mental Health Score prediction
* 📊 Data preprocessing and feature engineering
* 🔄 End-to-end Scikit-learn pipeline
* ⚙️ Hyperparameter tuning using GridSearchCV
* 💾 Model and pipeline serialization using Joblib
* 🌐 Interactive frontend using HTML, CSS & JavaScript
* 🔗 Backend API for ML predictions
* 📱 User-friendly prediction interface

---

## 🛠️ Technologies Used

| Technology         | Purpose              |
| ------------------ | -------------------- |
| 🐍 Python          | ML & Backend         |
| 🐼 Pandas          | Data Processing      |
| 🔢 NumPy           | Numerical Operations |
| 🤖 Scikit-learn    | Machine Learning     |
| 💾 Joblib          | Model Serialization  |
| 🌐 HTML            | Frontend Structure   |
| 🎨 CSS             | Frontend Styling     |
| ⚡ JavaScript       | Frontend Interaction |
| 🔗 FastAPI | Backend API          |

---

---

## 🧪 Machine Learning Process

The project follows a complete ML workflow:

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA
      ↓
Feature Engineering
      ↓
Data Preprocessing
      ↓
Model Training
      ↓
Hyperparameter Tuning
      ↓
Model Evaluation
      ↓
Model & Pipeline Saving
      ↓
Web Application Integration
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MitangPanchal/Mental-Health-Score.git
```

### 2. Navigate to the Project

```bash
cd Mental-Health-Score
```

### 3. Create Virtual Environment

```bash
python -m venv .venv
```

### 4. Activate Virtual Environment

**Windows PowerShell:**

```bash
.\venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000
```

---

## 🖥️ User Interface

The application provides a simple web interface where users can enter the required information and receive the predicted Mental Health Score.

---

## 📊 Model

The trained machine learning model is saved using **Joblib** and loaded by the backend during prediction.

The input data is passed through the preprocessing pipeline before generating the final prediction.

---

## 🔌 API Workflow

The frontend sends user input to the backend API.

```text
Frontend
   ↓
POST Request
   ↓
Backend API
   ↓
Pipeline
   ↓
ML Model
   ↓
Prediction
   ↓
JSON Response
   ↓
Frontend
```

Example response:

```json
{
    "prediction": 72.5
}
```

---

## 📦 Requirements

Install all required Python packages using:

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Improvements

* Add user authentication
* Improve model performance with additional datasets
* Add model performance visualization
* Deploy the application to a cloud platform
* Add prediction history
* Improve UI/UX and mobile responsiveness

---

## ⚠️ Disclaimer

This project is created for **educational and demonstration purposes only**.

The predicted Mental Health Score should **not be considered a medical diagnosis or a substitute for professional mental health advice**.

---

## 👨‍💻 Author

### Mitang Panchal

🔗 **GitHub:**
https://github.com/MitangPanchal

---

⭐ If you found this project useful, consider giving the repository a **star**!

