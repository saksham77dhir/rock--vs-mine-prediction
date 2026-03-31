# 🪨 Rock vs Mine Prediction Web App

This project is a **Machine Learning-based web application** built using **Streamlit** that predicts whether an object is a **Rock** or a **Mine** based on sonar signal data.

---

## 📌 Overview

The application uses sonar data to classify objects under the sea as either:
- 🪨 Rock  
- 💣 Mine  

It takes multiple numerical inputs representing sonar signals and provides a real-time prediction.

---

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Streamlit  
- Pickle  

---

## 📊 Dataset Information

- Dataset: Sonar Dataset  
- Each data point contains **60 numerical features**  
- Target:
  - `R` → Rock  
  - `M` → Mine  

---

## 🧠 Machine Learning Model

- Model: Logistic Regression   
- No feature scaling required  

The trained model is saved as a `.pkl` file and used in the Streamlit app.

---

