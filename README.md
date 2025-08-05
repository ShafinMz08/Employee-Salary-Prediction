# 💼 Employee Salary Prediction App

![GitHub repo size](https://img.shields.io/github/repo-size/your-username/employee-salary-prediction)
![Python version](https://img.shields.io/badge/python-3.8%2B-blue)
![Streamlit](https://img.shields.io/badge/streamlit-powered-red?logo=streamlit)

## 🧠 Project Overview

**Employee Salary Prediction** is a machine learning-powered web app designed to estimate an employee's salary based on workplace factors such as **years at the company**, **job satisfaction level**, and **average monthly hours**. The app provides **instant predictions** using a trained model and offers **interactive visualizations** to help users understand their input profile.

Built as part of my **Capstone Project**, this application showcases the integration of **data preprocessing**, **model deployment**, and **interactive front-end development** using **Streamlit**.

---

## 🚀 Live Demo

<img src="https://media.giphy.com/media/bolghismAzrpisoqut/giphy.gif" width="700"/>

🎯 Try it out: _[ http://localhost:8501]_  


---

## 📸 Screenshots

### 🎯 Prediction Page
![Prediction UI](https://github.com/ShafinMz08/Employee-Salary-Prediction/blob/main/images/Prediction.png)

### 📊 Visualized Input
![Bar Chart](https://github.com/ShafinMz08/Employee-Salary-Prediction/blob/main/images/Graph.png)

> _(Replace above URLs with your own screenshots hosted on Imgur, GitHub, or Streamlit assets)_

---

## 🛠 Features

- 🔢 Input sliders for dynamic data entry
- 🧠 Salary prediction using trained ML model (`model.pkl`)
- 📏 Data preprocessing via saved Scaler (`scaler.pkl`)
- 📊 Interactive bar chart using Plotly
- 🎈 Animated visuals with balloons and gifs
- 🔐 Clean modular code structure (`app.py`, `model.pkl`, `scaler.pkl`)

---

## ⚙️ How It Works

1. **Input Collection**:
   - Years at Company (0-20)
   - Satisfaction Level (0.0 - 1.0)
   - Average Monthly Hours (129 - 318)

2. **Preprocessing**:
   - Inputs are scaled using a previously fitted `StandardScaler`.

3. **Prediction**:
   - A trained regression model predicts the salary based on processed inputs.

4. **Output**:
   - Predicted salary is displayed with formatting.
   - Inputs are visualized as a bar chart for better user understanding.

---

## 🧪 Machine Learning Model

- **Model Type**: [e.g., Linear Regression / Random Forest / XGBoost]
- **Training Dataset**: [Brief info about dataset used]
- **Performance**:
  - Accuracy: XX.XX%
  - RMSE / MAE: XX.XX

> *(Add or edit this section based on your model)*

---

## 🧰 Tech Stack

| Layer       | Tools Used                         |
|-------------|------------------------------------|
| Frontend    | Streamlit, Plotly                  |
| Backend     | Python, NumPy, Pandas              |
| ML Model    | Scikit-learn, Joblib               |
| Deployment  | Streamlit Cloud (or Localhost)     |

---

## 📦 Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/employee-salary-prediction.git
cd employee-salary-prediction
pip install -r requirements.txt
