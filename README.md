
# Perceptive Modelling and Machine Learning in 2D — Project 1 (Machine Learning)

### Machine Learning Course — MEEC FEUP, 2025

This repository contains **Project 1** from the *Machine Learning* course at **FEUP**. The project applies **machine learning techniques** to **2D sensor data**, specifically using **LiDAR measurements** to model and predict trajectory data. The project explores regression models like **Ridge** and **LASSO regression**, focusing on the following objectives:

- **2D state estimation** using **Kalman Filter**
- **Polynomial regression** techniques:
  - **Ridge Regression**: Regularized regression for robust fitting
  - **LASSO Regression**: L1 regularized regression to enforce sparsity and feature selection
- **Evaluation of models** using **Mean Squared Error (MSE)**
- **Data visualization** of predictions and model fits

This project is intended to demonstrate the application of machine learning algorithms to predict movement in a 2D space, using sensor data for trajectory estimation.

## Overview
In this project, the following steps were performed:
1. **Data Loading and Preprocessing**: The dataset, which includes position and velocity measurements along with LiDAR data, was preprocessed.
2. **Modeling and Regression**: Applied **Ridge** and **LASSO regression** to model the data.
3. **Evaluation**: The performance of both models was evaluated using **Mean Squared Error (MSE)**, comparing the predicted trajectories to the ground truth.
4. **Visualization**: Visualized the predicted and actual trajectories, as well as the fit of both models.

## Project Grade
We received a grade of **20/20** for this project, demonstrating the successful implementation and evaluation of the machine learning models.

## 📈 Results
The models were evaluated using **Mean Squared Error (MSE)**, and the following results were obtained:

- **Testing MSE (Ridge Model)**: `0.464`
- **Testing MSE (LASSO Model)**: `0.476`

These values indicate the performance of both models in terms of error between the predicted and actual trajectories.

The project relies on the following libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`


## Authors
This project was developed as part of **Machine Learning Project 1** at **FEUP** (2025).

* *Afonso Mateus*  afonso.tomas.mateus@gmail.com
* *David Brás*  davidfsbras@gmail.com

---

### *Perceptive Modelling and Machine Learning in 2D — Project 1, FEUP MEEC Machine Learning Course, 2025.*
