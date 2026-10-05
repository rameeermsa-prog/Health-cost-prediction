# 🏥 Healthcare Cost Prediction

Healthcare Cost Prediction is a Machine Learning project that predicts the estimated healthcare cost of a patient based on medical, lifestyle, and demographic factors.

## 📌 Project Overview

The project uses a dataset containing **100,000 patient records**. It considers factors such as age, sex, BMI, children, smoking status, region, exercise level, chronic conditions, blood pressure, cholesterol, and annual income to predict healthcare costs.

A **Random Forest Regressor** is used for prediction, and **GridSearchCV** is applied to find the best model parameters. The trained model is integrated with a **Gradio interface** for interactive predictions.

## 🎯 Objectives

* Predict estimated healthcare costs.
* Analyze factors affecting healthcare expenses.
* Apply data preprocessing and feature engineering.
* Optimize the Random Forest model using Grid Search.
* Evaluate model performance using MAE, RMSE, and R².
* Provide an easy-to-use Gradio prediction interface.

## 📊 Dataset

The dataset contains **100,000 records and 13 columns**.

### Main Features

* Age
* Sex
* BMI
* Children
* Smoker
* Region
* Exercise Level
* Chronic Conditions
* Blood Pressure
* Cholesterol
* Annual Income

**Target:** `healthcare_cost`

## 🤖 Machine Learning Model

**Random Forest Regressor**

Grid Search is used to optimize:

* Number of estimators
* Maximum depth
* Minimum samples split
* Minimum samples leaf

The best model achieved a **CV R² score of approximatel**

