# sleep_disorder_prediction_ml
A machine learning project for predicting sleep disorders using lifestyle and health data. Built using Python, Flask, QDA, and GBC models.

Sleep Disorder Prediction Using Machine Learning

This project predicts sleep disorders—Healthy, Insomnia, Sleep Apnea—using machine learning models trained on lifestyle and health-related features.
It includes full model development, evaluation, and deployment using a Flask web application.

Project Overview

Sleep disorders are increasing due to stress, irregular routines, and unhealthy lifestyles. This project aims to build a fast, affordable, and accessible system that predicts sleep disorder categories using simple user inputs.

Two machine learning models were developed and evaluated:

Gradient Boosting Classifier (GBC)

Quadratic Discriminant Analysis (QDA)

The best-performing model (GBC) is integrated into a web app where users can enter their details and receive instant predictions.

├── app.py
├── model/
│   ├── sleep_boost.pkl
│   └── sleep_quadra.pkl
├── static/
│   ├── images
│   └── css files
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── upload.html
│   ├── prediction.html
│   └── performance.html
├── test_data/
│   └── test_dataset.csv
├── upload.csv
├── requirements.txt
└── README.md

Machine Learning Models Used
🔹 Gradient Boosting Classifier (GBC)

Best performing model

High accuracy

Low misclassification

Used for final deployment

🔹 Quadratic Discriminant Analysis (QDA)

Lightweight and interpretable

Used for comparison

📊 Model Performance Summary
GBC Results
Class	Recall	Precision	F1 Score
Healthy	0.93	0.95	0.96
Insomnia	0.95	0.96	0.96
Sleep Apnea	0.97	0.95	0.94
QDA Results
Class	Recall	Precision	F1 Score
Healthy	0.95	0.92	0.89
Insomnia	0.89	0.91	0.94
Sleep Apnea	0.92	0.93	0.93
🌐 Web Application Features

✔ Login System
✔ Upload Dataset
✔ Real-time Prediction
✔ Model Comparison
✔ Performance Metrics
✔ Confusion Matrix Visualisation

🛠️ Technologies Used
🔹 Frontend

HTML
CSS
JavaScript

🔹 Backend

Python

Flask Framework

🔹 Machine Learning

Scikit-learn
Pandas
NumPy
Matplotlib

🚀 How to Run the Project
1️⃣ Install Dependencies
pip install -r requirements.txt

2️⃣ Run the Flask App
python app.py

3️⃣ Open in Browser
http://127.0.0.1:5000/

📁 Dataset Used

Sleep Health and Lifestyle Dataset
(~15,000 entries, 13 features)

Features include:
Age
Gender
Occupation
Sleep Duration
Stress Level
Blood Pressure
Heart Rate
BMI Category
Daily Steps
Sleep Disorder label

🔮 Future Enhancements

Integration with wearable sensors
Real-time sleep tracking
Cloud-based deployment
Personalized health recommendations
Deep learning model integration

👩‍💻 Developed By

Prathiksha A.H, Kusuma.C, Priya.P
Department of Computer Science
ACS College of Engineering
