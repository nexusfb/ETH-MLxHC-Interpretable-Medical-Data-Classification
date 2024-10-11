# Machine Learning for Health Care - ETH Zurich 
# Project 1 - Group72
# Interpretable-Medical-Data-Classification

This repository contains interpretable and explainable classification models for medical data, focusing on two tasks:
1. Predicting heart disease using various machine learning models, including Logistic Lasso Regression, Multi-Layer Perceptrons (MLPs), and Neural Additive Models (NAMs).
2. Detecting pneumonia in chest X-ray images using Convolutional Neural Networks (CNNs) and interpretability techniques like Integrated Gradients and Grad-CAM.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [Models](#models)
- [Results](#results)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction
This project develops interpretable models for heart disease prediction and pneumonia detection, aiming to make medical data more transparent and understandable through post-hoc interpretability methods such as SHAP, Integrated Gradients, and Grad-CAM.

## Project Structure
├── data/ # Contains the processed datasets for heart disease and pneumonia 
├── models/ # Machine learning and deep learning model implementations 
├── results/ # Model performance metrics and plots 
├── notebooks/ # Jupyter notebooks for exploration and analysis 
└── README.md # This file


## Datasets
- **Heart Disease Dataset**: Contains patient health data for predicting heart disease outcomes.
- **Pneumonia Dataset**: Contains labeled chest X-ray images for classifying pneumonia cases.

## Models
1. **Logistic Lasso Regression**: Provides feature selection and interpretable coefficients for heart disease prediction.
2. **MLP and NAM Models**: Explore more complex patterns with SHAP-based interpretability.
3. **CNN for Pneumonia Detection**: Uses deep learning with post-hoc methods like Integrated Gradients and Grad-CAM for visual interpretability.

## Results
| Model                            | Accuracy  |
|----------------------------------|-----------|
| Logistic Lasso Regression         | 87%       |
| MLP Classifier (Heart Disease)    | 82.61%    |
| CNN Classifier (Pneumonia)        | 84%       |

## Usage
1. **Clone the Repository**: 

   ```bash
   git clone https://github.com/ilboglions/Project1_ML4HC_Group72
   cd Project1_MLHC_Group72
   ```

2. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   This command will install all the required Python packages specified in the `requirements.txt` file.

3. **Execute jupyter notebooks**


## Contributors
- Federica Bruni
- Mateo Boglioni
- Paula Momo Cabrera
