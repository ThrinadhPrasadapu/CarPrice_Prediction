# 🚗 Used Car Price Prediction – KaggleX Competition

This project was developed as part of the **KaggleX 2024 competition**, where the goal was to build a machine learning model to predict used car prices based on various vehicle attributes.

---

## 📌 Problem Statement

Predict the selling price of a used car using features such as:

- Brand / Model  
- Year of manufacture  
- Fuel type  
- Transmission  
- Mileage  
- Engine specifications  
- Other vehicle attributes  

The task is formulated as a **regression problem**.

---

## 🛠 Technologies Used

- Python  
- AutoGluon (AutoML)  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## ⚙️ Approach

- Data preprocessing and cleaning  
- Feature analysis and basic feature engineering  
- Used **AutoGluon AutoML framework** for:
  - Automated model selection
  - Hyperparameter tuning
  - Ensemble learning
- Trained multiple models and combined them using **ensemble techniques** to improve prediction performance.

---

## 📊 Model

The AutoML framework automatically evaluated several models including:

- Gradient Boosting models  
- Random Forest  
- Neural Networks  
- Ensemble models  

The final prediction is generated using **stacked ensemble models** to improve robustness and accuracy.


