# Support Vector Regression (SVR) from Scratch

## Overview

This repository contains an implementation of **Support Vector Regression (SVR)** using **Quadratic Programming (QP)** and the **Radial Basis Function (RBF) kernel**. The model is built from scratch using **cvxopt** for optimization and allows for hyperparameter tuning (**C, epsilon, sigma**). It is designed for regression tasks where the goal is to predict continuous values.

## Features

- Implements **SVR from scratch** without external ML libraries.
- Uses **Quadratic Programming (QP)** to solve the optimization problem.
- Supports **RBF kernel** for non-linear regression.
- Allows customization of **C (regularization), epsilon (margin), and sigma (kernel width)**.
- Identifies **support vectors** for improved prediction accuracy.
- Provides **visualizations** for data analysis.

## Dataset

The dataset consists of input features **X1 and X2** along with the target variable **y**. The model aims to find a regression function that best fits the data using SVR.

## Visualizations

Below are the generated plots to analyze the relationship between features and the target variable:

### 1. X1 vs y
![image](https://github.com/user-attachments/assets/8d90c543-63f6-420f-bcd8-ea356a5c281b)


### 2. X2 vs y
![image](https://github.com/user-attachments/assets/1cda6fd1-d52e-4a35-9158-78de45105c6e)


### 3. X1 and X2 vs y
![image](https://github.com/user-attachments/assets/29fb4c9c-074f-4282-af68-48e0e61c9f03)

## Results
- Got an MSE of 3.926274961597056e-05

## Dependencies

To run this project, install the required Python libraries:

```bash
pip install numpy matplotlib cvxopt
