This project is a machine learning-based web application that predicts whether a person is likely to have diabetes, using medical attributes as inputs. The model is trained on the Pima Indians Diabetes Dataset and deployed via a simple web interface using Streamlit.

📂 Project Structure
bash
Copy
Edit
.
├── app.py                    # Streamlit web app script
├── Diabetes Prediction.ipynb # Jupyter notebook for data analysis and model training
├── diabetes.csv             # Dataset used for training and testing
└── README.md                # Project documentation

🚀 Features
User-friendly interface to input medical data

Predicts diabetes based on model trained on 768 real cases

Built using Python, Pandas, Scikit-learn, and Streamlit

Clean visualizations and interactive form for input

📊 Dataset
The dataset (diabetes.csv) consists of the following medical parameters:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Outcome (0: No diabetes, 1: Diabetes)
