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

## 📁 Project Structure

```bash
Customer-Churn-App/
├── app.py                     # Main Streamlit application
├── retrain_model.py           # Script to retrain model (optional)
├── model.pkl                  # Trained ML model
├── scaler.pkl                 # StandardScaler object
├── label_encoder_gender.pkl   # Gender encoder
├── onehot_encoder_geo.pkl     # Geography encoder
├── requirements.txt           # Dependencies
├── README.md                  # Project documentation
└── LICENSE                    # License file
```

---

## ⚙️ Installation & Run (Local)

1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-app.git
cd customer-churn-app
```

2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate the environment:

Windows

```bash
venv\Scripts\activate
```

Mac/Linux

```bash
source venv/bin/activate
```

3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

4️⃣ Run the Streamlit App

```bash
streamlit run app.py
```

5️⃣ Access the Application

After running the command, Streamlit will automatically launch in your browser at:

```bash
http://localhost:8501
```

If it does not open automatically, copy the URL above into your browser.

---

## 🛠️ Tech Stack

### 🔹 Programming Language
- Python 3.10

### 🔹 Machine Learning
- Scikit-learn (MLPClassifier)
- NumPy
- Pandas

### 🔹 Data Preprocessing
- StandardScaler
- Label Encoding
- One-Hot Encoding

### 🔹 Web Framework
- Streamlit

### 🔹 Deployment
- Streamlit Cloud
- GitHub

### 🔹 Model Serialization
- Joblib

---

🖥️ 2️⃣ Application Screenshots Section

First, upload your screenshots to GitHub inside a folder:

Create a folder:

```bash
assets/
```

Upload your web app images there, for example:

```bash
assets/homepage.png
assets/prediction.png
```

Then add this section in README:

```bash
## 📸 Application Preview

### 🏠 Home Interface
![Home Interface](assets/homepage.png)

### 📊 Churn Prediction Result
![Prediction Output](assets/prediction.png)
```

That will automatically display images inside GitHub.

🚀 3️⃣ Future Scope

```bash
## 🔮 Future Scope

- 📈 Integration with CRM systems for automated retention workflows
- 📊 Advanced dashboard with churn trend analytics
- 🧠 Model explainability using SHAP values
- 📂 Batch customer prediction capability
- 🌐 REST API integration for enterprise applications
- 🔐 Role-based authentication system
- ☁️ Deployment using Docker & cloud infrastructure
```

📜 4️⃣ License Section

If you are using MIT License (recommended):

```bash
## 📄 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this software with proper attribution.
```

If you want it more corporate:

```bash
## 📄 License

This project is licensed under the MIT License.  
See the LICENSE file for more details.
```

🤝 5️⃣ Acknowledgement Section

Professional corporate tone:

```bash
## 🙏 Acknowledgements

- Scikit-learn community for machine learning framework
- Streamlit for rapid web application development
- Open-source contributors for continuous ecosystem improvements

Special thanks to mentors and peers for guidance during development.
```

If you want a slightly personal but still professional tone:

```bash
## 🙏 Acknowledgements

This project was developed as part of a machine learning deployment initiative.  
Gratitude to the open-source community and educational resources that made this project possible.
```
