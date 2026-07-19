# 💳 Credit Card Approval Prediction

A Machine Learning-based web application that predicts whether a credit card application will be approved or rejected based on applicant details. The project is built using Python, Flask, and Machine Learning with a simple and user-friendly web interface.

---

## 📌 Project Overview

The Credit Card Approval Prediction System helps automate the credit card approval process. Users enter applicant details through a web application, and the trained machine learning model predicts whether the application is approved or rejected.

---

## ✨ Features

- Predicts credit card approval using Machine Learning
- Simple and responsive web interface
- Fast prediction results
- User-friendly design
- Data preprocessing and model training
- Database integration using MySQL

---

## 🛠️ Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- MySQL

---

## 📂 Project Structure

```text
skillwallet/
│
├── app.py                    # Flask application
├── train.py                  # Model training script
├── model.pkl                 # Trained machine learning model
├── encoders.pkl              # Saved label encoders
├── requirements.txt          # Python dependencies
├── Procfile                  # Deployment configuration
├── render.yaml               # Render deployment settings
├── .gitignore
├── .python-version
│
├── data/
│   └── .gitkeep
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_model_training.ipynb
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── assets/
│       └── eda/
│           ├── correlation_heatmap.png
│           ├── cm_decision_tree.png
│           ├── cm_logistic_regression.png
│           ├── cm_random_forest.png
│           ├── cm_xgboost.png
│           └── ...
│
├── templates/
│   ├── home.html
│   ├── index.html
│   └── result.html
│
└── README.md
```

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/chandanasri-17/Credit-Card-Approval-Prediction.git
```

2. Open the project folder

```bash
cd Credit-Card-Approval-Prediction
```

3. Install the required packages

```bash
pip install -r requirements.txt
```

4. Configure the MySQL database.

5. Run the application

```bash
python app.py
```

6. Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 📊 Dataset

**Kaggle:** Credit Card Approval Prediction

https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Login Page
- Dashboard
- Prediction Form
- Prediction Result

---

## 👥 Team Members

- Chandana Sri Pamulapati(Team Lead)
- Hannah Kurapati
- Pathan Neelofer
- K. Nandu Priya

---

## 🎯 Future Improvements

- Improve model accuracy
- Add user authentication
- Deploy the application to the cloud
- Integrate with banking systems

---

## 📜 License

This project is developed for academic and learning purposes.
