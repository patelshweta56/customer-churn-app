# 📊 Customer Churn Prediction App

A machine learning powered web application that predicts whether a customer is likely to churn based on financial and demographic attributes. Built using **Streamlit** and **Scikit-learn**, this project demonstrates how AI can assist businesses in reducing customer attrition and improving retention strategies.

---

## 🚀 Overview

Customer churn is a major challenge for subscription-based and banking businesses.  
This application allows users to input customer details and instantly receive:

- 📈 Churn probability score
- ⚠️ Risk classification (Likely to churn / Not likely to churn)
- 📊 AI-driven prediction using trained neural network model

---

## 🧠 Features

- 🔹 Interactive web interface using Streamlit  
- 🔹 Real-time churn probability prediction  
- 🔹 Pre-trained Neural Network (MLPClassifier)  
- 🔹 Scaled and encoded input preprocessing  
- 🔹 Clean deployment on Streamlit Cloud  

---

## 📂 Project Structure

Customer-Churn-App/
│
├── app.py # Main Streamlit application
├── retrain_model.py # Script to retrain model (optional)
├── model.pkl # Trained ML model
├── scaler.pkl # StandardScaler object
├── label_encoder_gender.pkl # Gender encoder
├── onehot_encoder_geo.pkl # Geography encoder
├── requirements.txt # Dependencies
├── README.md # Project documentation
└── LICENSE # License file


---

## ⚙️ Installation & Run (Local)

1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-app.git
cd customer-churn-app
```

2️⃣ Create Virtual Environment (Recommended)

python -m venv venv

Activate the environment:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the Streamlit App

streamlit run app.py

5️⃣ Access the Application

After running the command, Streamlit will automatically launch in your browser at:

http://localhost:8501

If it does not open automatically, copy the URL above into your browser.
