# bodyfat_pred
body fat prediction using regressor models done by jeevan ramesh
# Body Fat Prediction Project

This project aims to predict body fat percentages using various regression models. The dataset includes multiple features such as density, age, weight, height, and body measurements (e.g., neck, chest, abdomen).

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction
Body fat percentage is a key indicator of health. This project leverages machine learning techniques to develop and compare predictive models, enabling accurate estimation of body fat percentage from easily measurable features.

## Dataset
The dataset contains the following features:
- **Density**, **Age**, **Weight**, **Height**
- Measurements: **Neck**, **Chest**, **Abdomen**, **Hip**, **Thigh**, **Knee**, **Ankle**, **Biceps**, **Forearm**, **Wrist**

Missing values were handled by dropping incomplete rows.

## Models Used
The project evaluates the following regression models:
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Support Vector Regressor (SVR)**
4. **Lasso Regressor**
5. **Random Forest Regressor**

### Evaluation Metrics
- **Mean Squared Error (MSE)**
- **R² Score**

## Results
| Model                  | Mean Squared Error (MSE) | R² Score |
|------------------------|--------------------------|----------|
| **Linear Regression**  | 0.38                    | 0.992    |
| **Decision Tree**      | 1.97                    | 0.960    |
| **SVR**                | 0.02                    | 1.000    |
| **Lasso Regression**   | 0.26                    | 0.990    |
| **Random Forest**      | 0.05                    | 1.000    |

### Observations
- **SVR** and **Random Forest Regressor** achieved perfect R² Scores of 1.00, indicating exceptional predictive performance.
- The **Lasso Regressor** and **Linear Regression** also performed well, achieving R² Scores close to 1.00.
- The **Decision Tree Regressor** had the lowest performance with an MSE of 1.97 and an R² Score of 0.96.

## Installation
