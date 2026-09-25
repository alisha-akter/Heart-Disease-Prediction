# ❤️ Heart Disease Prediction

An interactive heart disease risk prediction application built with **Python, Pandas, Scikit-learn, Joblib, and Streamlit**.

The project analyzes patient health-related information and predicts whether the input indicates a **higher or lower risk of heart disease**.

## 📌 Project Overview

This project includes:

* Data preprocessing and exploration
* Feature encoding
* Train-test splitting
* Feature scaling using `StandardScaler`
* Multiple classification models
* Model evaluation using Accuracy and F1 Score
* Logistic Regression model for the final prediction
* Interactive Streamlit web application

## 🤖 Models Used

The following classification models were experimented with:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Naive Bayes
* Decision Tree
* Support Vector Machine (SVM)

The selected Logistic Regression model is used in the Streamlit application.

## 🩺 Input Features

The application takes the following information from the user:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope


## 📂 Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── app.py
├── Logistic_Heart.pkl
├── scaler.pkl
├── columns.pkl
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Heart-Disease-Prediction
```

### 2. Install the required packages


### 3. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy
* F1 Score

The complete experimentation and evaluation can be found in the Jupyter Notebook.

## ⚠️ Disclaimer

This project is created for **educational and demonstration purposes only**. The predictions should not be considered medical advice or used as a substitute for professional medical diagnosis.

## 👩‍💻 Author

**Alisha Akter**

CSE Student, Jahangirnagar University
