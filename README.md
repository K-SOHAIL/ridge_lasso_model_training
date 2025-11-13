# 🩺 Diabetes Regression Predictor – Ridge & Lasso ML WebApp

**Author:** Kamran Sohail

---

## 🚀 Project Overview

A modern, colorful, and fully responsive Streamlit web application that predicts diabetes progression using Ridge and Lasso regression. All predictions and user inputs are securely logged in a MongoDB Atlas cloud database. Optimized for mobile, tablet, and desktop.

---

## 🌈 Key Features

- **Intuitive, modern UI:** Colorful headers, icons, emojis, responsive two-column layout.
- **Works everywhere:** Auto-adjusts for phone, tablet, and PC.
- **Easy model selection:** Choose between Ridge and Lasso regression with a single click.
- **Data persistence:** Each prediction (along with all user-input features) is logged to a MongoDB Atlas database for future reference.
- **Recent analytics:** View the latest 5 predictions instantly inside the app.
- **One-click deployment:** Runs from GitHub with Streamlit Cloud, no manual hosting needed.

---

## ⚙️ Tech Stack

- **Frontend/UI:** [Streamlit](https://streamlit.io/)
- **ML Models:** Scikit-learn (`ridge_diabetes_model.pkl`, `lasso_diabetes_model.pkl`)
- **Database:** MongoDB Atlas (cloud NoSQL)
- **Deployment:** GitHub + Streamlit Cloud
- **Python Packages:** `streamlit`, `scikit-learn`, `numpy`, `pandas`, `pymongo`

---

## 📋 Usage

1. **Clone or fork this repo to your own GitHub account.**
2. Place your `ridge_diabetes_model.pkl` and `lasso_diabetes_model.pkl` files in the root directory.
3. Make sure your `requirements.txt` includes:
streamlit
scikit-learn
numpy
pandas
pymongo

text
4. Connect to your MongoDB Atlas cluster by setting your URI in the code.
5. Deploy directly from GitHub via [Streamlit Cloud](https://share.streamlit.io/).

**To use the app:**
- Open the deployed webapp on your PC, phone, or tablet.
- Enter your health data (10 features: age, sex, bmi, bp, s1, s2, s3, s4, s5, s6).
- Select Ridge or Lasso regression, then click **Predict**.
- Instantly view your diabetes score and see a summary of recent logs.

---

## 📱 Mobile & Desktop-Ready

- Layout automatically adapts for the best experience on any device.
- All controls are touch-friendly and visible on small screens.
- Clean data tables and easy navigation on mobile, PC and tablet.

---

## 💾 Data Flow & Security

- User input and model predictions are **automatically saved** to your secure MongoDB collection.
- No user data is stored locally on any device.

---

## 🛠️ Example Directory Structure

project-root/
├── app.py
├── ridge_diabetes_model.pkl
├── lasso_diabetes_model.pkl
├── requirements.txt
└── README.md

text

---

## 🔗 Deployment & Credits

- **Deployed with:** GitHub + Streamlit Cloud  
- **Database:** MongoDB Atlas  
- **Author:** Kamran Sohail

Built with 🩺, 🚀 and ❤️.  
For questions or suggestions, create an Issue or fork the repo!
