# Child Labour Risk Detection Using Machine Learning

A predictive system to identify children or regions at risk of child labour using **socioeconomic, educational, and census data**. Built with **Python** and **Machine Learning**, this project aims to support early intervention, targeted resource allocation, and transparent community support.

---

## 📝 Project Overview
Child labour remains a critical issue worldwide, deeply linked to poverty, lack of education, and other socioeconomic vulnerabilities. 

This project leverages **machine learning** to:
- Predict risk levels (High, At Risk, Low).
- Identify key risk factors.
- Provide interpretable predictions for NGOs and policymakers.
- Offer a donation module to support at-risk cases.

---

## 🎯 Objectives
- Develop a Python-based ML model for child labour risk prediction.
- Identify key factors from socioeconomic and educational datasets.
- Build a user-friendly interface (CLI/Streamlit) for risk assessment.
- Ensure explainable predictions using SHAP or similar tools.
- Incorporate a transparent donation module for community support.

---

## 🛠 Methodology

### **1. Data Preparation**
- Collect socioeconomic, educational, and census data.
- Preprocess: Handle missing values, encode categorical data, normalize features.

### **2. Feature Engineering**
- Analyze feature importance.
- Create composite indicators (e.g., Household Vulnerability Index).

### **3. Model Development**
- Train models: Logistic Regression, Random Forest, XGBoost.
- Use cross-validation for hyperparameter tuning.
- Evaluate with Accuracy, Precision, Recall, F1-Score, ROC-AUC.

### **4. Interpretability**
- Use SHAP to explain predictions and visualize risk factors.

### **5. Deployment**
- Build a prototype interface using **Streamlit** or **CLI**.
- Enable users to input data and get live risk predictions.

---

## 📊 Dataset
- **Primary Data:** Government census, educational records, socioeconomic surveys.
- **Prototype Data:** Simulated/mock datasets (if real datasets unavailable).
- **Features:** Age, gender, family income, parental education, school attendance, location, etc.

---

## 🛠 Tech Stack & Libraries
- **Python**
- **Pandas, NumPy** – Data processing
- **Scikit-learn** – Machine Learning
- **Matplotlib, Seaborn** – Visualization
- **SHAP** – Model interpretability
- **Streamlit/Flask** – Interface (optional)
- **Jupyter Notebook** – Development & documentation

---

## 🚀 Expected Outcomes
- A high-accuracy ML model for child labour risk detection.
- Actionable insights on major risk factors.
- Usable prototype application with interpretability.
- Transparent donation feature to support identified cases.

---

## 👥 Contributors
- **Muskan**  
- **Zainab Tanweer**

---

## 📜 License
This project is intended for research and educational purposes only.  
(Include license type  – MIT, Apache 2.0, etc.)

