# Medication-Demand-Prediction-System
Machine Learning system for medication demand forecasting and stock replenishment recommendation using Gradient Boosting and FastAPI.
Medication Demand Prediction using Machine Learning
Project Overview

This project predicts future demand for pharmaceutical products using Machine Learning techniques.

The objective is to help pharmacies and healthcare organizations anticipate medication demand and improve inventory management.

Dataset

The dataset contains daily sales of several pharmaceutical products:

m01ab
m01ae
n02ba
n02be
n05b
n05c
r03
r06

Period:

2014 – 2019

Features Engineering

The following features were created:


temperature
atc_class_enc
lag_1
lag_7
lag_30
rolling_7
rolling_30
day_of_week
month
Machine Learning Models

Several models were tested:

Gradient Boosting Regressor
Random Forest Regressor
XGBoost Regressor

The best model selected was Gradient Boosting.

Evaluation Metrics

The following metrics were used:

MAE
RMSE
MAPE
API

A REST API was developed using FastAPI.

Available endpoints:

POST /predict
GET /recommend
GET /metrics
Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
FastAPI
Matplotlib
Author

Karima Driouch
Imane Bokkour
