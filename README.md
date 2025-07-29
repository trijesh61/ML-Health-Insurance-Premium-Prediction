
# 🏥 Health Insurance Premium Prediction using Machine Learning

[![Streamlit App](https://img.shields.io/badge/Live%20App-Click%20Here-brightgreen?style=for-the-badge&logo=streamlit)](https://health-insurance-premium-prediction-ml.streamlit.app/)



This project predicts the **health insurance premium cost** based on user-input features using a trained machine learning model. It demonstrates a complete ML pipeline — from data preprocessing to model deployment using Streamlit.

---

## 🚀 Project Overview

Health insurance premiums can vary greatly depending on individual demographics and lifestyle. This project uses a **regression model** to predict the expected premium amount based on the following inputs:

- Gender
- Marital Status
- Age
- BMI Category
- Smoking Status
- Number of Children
- Employment Status
- Income Level
- Medical History
- Insurance Plan

The model is deployed as a **Streamlit web app**, providing an easy-to-use interface for users to test predictions.

---

## 🛠️ Tech Stack

| Tool/Library     | Purpose                             |
|------------------|--------------------------------------|
| Python           | Core Programming Language            |
| Pandas, NumPy    | Data Manipulation                    |
| Scikit-learn     | Machine Learning Model Training      |
| Streamlit        | Web App Deployment                   |
| Matplotlib, Seaborn | Exploratory Data Analysis (EDA)  |
| joblib           | Model Serialization                  |

---

## 📊 Dataset

The dataset used in this project was synthetically generated for educational purposes and includes various user attributes and their corresponding insurance premiums.

---

## 📈 ML Workflow

1. **Data Cleaning & EDA**
2. **Feature Engineering**
3. **Encoding Categorical Variables**
4. **Model Training** (Linear Regression, Ridge, Lasso tested)
5. **Model Evaluation**
6. **Model Saving**
7. **Streamlit App Development**

---

## 🎯 Features

- ✅ Real-time prediction based on form inputs
- ✅ User-friendly UI via Streamlit
- ✅ Modular code structure
- ✅ Clean separation of ML logic and UI components

---

## 📦 Directory Structure

```
ML-Health-Insurance-Premium-Prediction/
├── App/
│   ├── app.py                 # Streamlit app
│   ├── model/
│   │   └── model.pkl          # Trained model
│   ├── artifacts/
│   │   └── encoders, transformers, etc.
├── data/
│   └── insurance.csv          # Dataset
├── notebooks/
│   └── EDA_and_Modeling.ipynb # Exploratory analysis and training
├── requirements.txt           # Dependencies
├── README.md                  # You're reading it!
```

---

## 💻 How to Run Locally

1. **Clone the repo**

```bash
git clone https://github.com/trijesh61/ML-Health-Insurance-Premium-Prediction.git
cd ML-Health-Insurance-Premium-Prediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Streamlit app**

```bash
streamlit run App/app.py
```

---

## 🌐 Live App

Click here to try it live:  
👉 [Health Insurance Premium Predictor](https://health-insurance-premium-prediction-ml.streamlit.app/)

---

## 🙌 Author

**Trijesh Kondapuram**  
📌 Emerging Data Scientist | AI Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/trijesh-k/) • 🌐 [GitHub](https://github.com/trijesh61)

---

## ⭐ Feedback & Contributions

If you like this project, don’t forget to ⭐ the repo!  
Feel free to raise issues or open pull requests for improvements.
