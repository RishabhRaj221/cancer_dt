## Cancer Prediction App

This repository contains the code for a web application that predicts cancer diagnosis based on various input features.
https://hxywamtkcthssbt65debrf.streamlit.app/
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
The Cancer Prediction App is a machine learning application that predicts whether a patient has cancer based on input features such as age, gender, BMI, smoking status, genetic risk, physical activity, alcohol intake, and cancer history.

## Features
- Predict cancer diagnosis based on user input.
- Use machine learning model trained on a comprehensive dataset.
- Simple and intuitive user interface built with Streamlit.
- Deployed and accessible online.

.py

## Model Training

The model is trained using the following features:

- **Age**: Integer values representing the patient's age (20-80).
- **Gender**: Binary values (0: Male, 1: Female).
- **BMI**: Continuous values representing Body Mass Index (15-40).
- **Smoking**: Binary values indicating smoking status (0: No, 1: Yes).
- **Genetic Risk**: Categorical values for genetic risk levels (0: Low, 1: Medium, 2: High).
- **Physical Activity**: Continuous values for hours per week spent on physical activities (0-10).
- **Alcohol Intake**: Continuous values for alcohol units consumed per week (0-5).
- **Cancer History**: Binary values indicating personal history of cancer (0: No, 1: Yes).

# Training Script

The model training script (`train_model.py`) preprocesses the data, trains an `XGBClassifier` model, and saves the trained model to disk as `best_model.pkl`.


# Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

# License

This project is licensed under the MIT License.

# Contact

For any inquiries, please contact:

Rishabh Raj 
Email: rajrishabh659@gmail.com



