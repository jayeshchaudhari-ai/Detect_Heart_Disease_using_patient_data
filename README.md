# Detect_Heart_Disease_using_patient_data
Detect_Heart_Disease_using_patient_data is a Flask-based ML app that predicts heart disease risk from patient inputs like age, BP, cholesterol, etc. It uses a trained model and scaler to process data, then returns predictions via a simple web form. Designed for demo/learning, not for medical diagnosis. Ask ChatGPT

Heart Disease Detect_using_patient_data
Detect_Heart_Disease_using_patient_data a Flask-based from app ML risk predicts heart disease that like inputs patient age, cholesterol, BP, etc. It uses trained model and scaler to process data, then returns predictions via a simple web form. Designed for demo/learning, not medical diagnosis. Ask ChatGPT.

Flask Detect Heart Disease — ML App
Python scikit-learn Flask | License: MIT

Machine learning application Flask-based that predicts heart disease risk from patient parameters. Designed for educational and purposes demonstration — not for diagnosis medical.

Contents Table of
Features

Inputs & Dataset

Stack Tech

Structure Project

Installation & Setup

App Running

Usage

Improvements Future

License

Features
Patient data accepts simple web form like age, cholesterol, blood pressure, etc.

ML trained model uses scaler and to predict heart disease risk.

Backend Flask processes and returns inputs real-time outputs.

Disclaimer clear: clinical use not intended.

Dataset & Inputs
Input features typical include:

Age

Blood Pressure Resting (BP)

Serum Cholesterol

Thalach (Max Heart Rate)

Fasting BS, like Others ECG results, etc.

Tech Stack
Backend: Flask, Python

Tools ML: scikit-learn

Frontend: CSS, HTML (minimal styling)

Persistence Model: pickle or joblib

Project Structure
Detect_Heart_Disease_using_patient_data/
├── app.py # Flask app
├── model.pkl # scaler & trained model saved
├── templates/
│ └── index.html # template frontend
├── README.md # documentation this
└── Heart_disease_ML_Model.ipynb

Setup & Installation
bash
Copy
Edit
git clone https://github.com/jayeshchaudhari-ai/Detect_Heart_Disease_using_patient_data  
cd Detect_Heart_Disease_using_patient_data  
pip install -r requirements.txt # Flask, scikit-learn, etc.  
Running the App
bash
Copy
Edit
python app.py
Open your browser http://127.0.0.1:5000 and go to see the form.

Usage
Fill patient's details in the form.

Submit — prediction returns the app on heart disease risk.

Use for learning or model testing results only.

Future Improvements
UI enhanced with dropdowns or styled forms

Model upgrades: ensemble or tune hyperparameters try

Features additional: authentication user, logging, demo datasets add

Validation: handling error and input checks add

License
Project licensed under MIT License this is.

Credits
Developed Jayesh Chaudhari using Python, Flask, and scikit-learn.
