# Iris Flower Classification Project

## Overview
This project is a machine learning model designed to classify the species of Iris flowers based on their sepal and petal measurements. The dataset contains measurements for three species of Iris flowers: **Iris-setosa**, **Iris-versicolor**, and **Iris-virginica**. Using these measurements, the model predicts the species with high accuracy.

## Features
The dataset contains the following features:
- **Sepal Length (cm)**
- **Sepal Width (cm)**
- **Petal Length (cm)**
- **Petal Width (cm)**

## Objective
The objective of this project is to train a machine learning model that:
1. Understands the relationships between the features.
2. Accurately predicts the species of Iris flowers based on new data.

## Steps in the Project
1. **Data Preprocessing**
   - Cleaned and encoded the dataset.
   - Split the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between features using pair plots and heatmaps.

3. **Model Training**
   - Trained a **Random Forest Classifier** on the training data.

4. **Model Evaluation**
   - Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

5. **Hyperparameter Tuning**
   - Used grid search to optimize model parameters.

6. **Model Deployment**
   - Saved the trained model using `joblib` for later use.

## Technologies Used
- **Python**: Programming language.
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `seaborn` and `matplotlib` for data visualization.
  - `scikit-learn` for machine learning.
  - `joblib` for saving and loading the model.

