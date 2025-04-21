# Teleco-Customer-Churn-Analysis
This is an IBM generated Project
# 📉 Telco Customer Churn Prediction

Predicting customer churn using machine learning to help telecom companies improve retention strategies.

## 🧠 Project Overview

This project uses the Telco Customer Churn dataset provided by IBM to predict whether a customer will leave the company or not. The model helps identify high-risk customers so proactive steps can be taken to retain them.

**Key Objectives:**
- Perform Exploratory Data Analysis (EDA)
- Preprocess the data and engineer relevant features
- Train various machine learning models
- Evaluate and compare model performance
- Interpret the results using explainable AI techniques
- (Optional) Deploy the model via Streamlit or Flask

---

## 📁 Dataset Overview

- **Source:** [IBM Sample Data Sets](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)
- **Records:** Each row represents a customer
- **Target Variable:** `Churn` (Yes/No)

**Columns include:**
- **Demographics:** Gender, Senior Citizen, Partner, Dependents
- **Account Info:** Tenure, Contract, Payment Method, Paperless Billing, Monthly and Total Charges
- **Services:** Phone Service, Internet Service, Online Security, Streaming, etc.

Got it! Here's a single, complete README.md file that includes:

📌 Project summary

🗃️ Folder structure

⚙️ Setup instructions + requirements

🧠 Model description

🌐 Streamlit app usage

👨‍💻 Author section

📜 License

You can copy and paste this directly into GitHub, and you're done.

markdown
Copy
Edit
# 🔮 Telco Customer Churn Prediction

Predict customer churn using machine learning and provide an interactive web app for real-time predictions using Streamlit.

---

## 🚀 Project Overview

Churn prediction helps telecom companies retain valuable customers by identifying patterns in user behavior. In this project, we:

- Perform data analysis on the IBM Telco Customer dataset  
- Train a Gradient Boosting Classifier  
- Build a Streamlit app for business users to interact with the model  
- Enable real-time churn predictions based on customer attributes

---

## 🧾 Dataset

- **Source:** [IBM Telco Churn Dataset](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)
- Each row represents one customer
- Target variable: `Churn` (Yes or No)

**Key Features:**

- Demographics: gender, age, senior citizen, partner, dependents  
- Services signed up: phone, internet, online security, streaming  
- Account info: contract, billing, payment method, charges  
- Tenure & churn label

---

## 📁 Project Structure

📦 Telco-Churn-Prediction ├── Customer churn project.ipynb # Jupyter Notebook for analysis and modeling ├── app.py # Streamlit web app script ├── final_gb_classifier.pkl # Trained Gradient Boosting model ├── requirements.txt # Required Python packages ├── README.md # Project documentation (this file)

yaml
Copy
Edit

---

## 🧠 Model Info

- Model: `GradientBoostingClassifier` from scikit-learn  
- Preprocessing includes label encoding for categorical features  
- Evaluation metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- Saved using `joblib` for deployment

---

## 🖥️ Streamlit Web App

The app provides a simple UI to enter customer attributes and predict churn probability.

### 📌 How to Use

1. **Install dependencies**

```bash
pip install -r requirements.txt
Run the app

bash
Copy
Edit
streamlit run app.py
Interact with the app

Open the provided localhost URL (usually http://localhost:8501) in your browser.

✅ Inputs collected
Gender, Senior Citizen, Partner, Dependents

Phone & Internet Services

Security, Backup, Device Protection

Streaming, Billing, Payment Method

Monthly/Total Charges, Tenure

🔍 Output
🟢 "The customer is likely to stay."

🔴 "The customer is likely to churn."

📦 requirements.txt
nginx
Copy
Edit
streamlit
pandas
numpy
scikit-learn
joblib
📚 References
IBM Telco Customer Churn Dataset

Scikit-learn Documentation

Streamlit Documentation

Steven Macko IBM Blog

👨‍💻 Author
Your Name
LinkedIn • Portfolio • Email

📜 License
MIT License

sql
Copy
Edit
MIT License

Copyright (c) 2025 Pranideep Meka

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
See the full MIT license for details.

🌟 Highlights
✅ Complete end-to-end churn solution

✅ Real-world dataset

✅ Business-friendly web interface

✅ Ready for deployment


