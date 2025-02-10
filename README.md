# Breast Cancer Detection using Machine Learning

## Overview

Breast cancer is one of the leading causes of death among women worldwide. Early detection and accurate diagnosis are critical for improving survival rates. This project leverages machine learning algorithms to predict whether a breast cancer tumor is malignant or benign based on diagnostic data. By applying advanced data analysis techniques, we aim to assist healthcare professionals in making quicker and more reliable decisions.

This project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which contains various attributes related to cell nuclei present in breast cancer biopsies. The dataset is analyzed using various machine learning models to provide predictions and insights into the classification of tumors.

## Key Features

- **Binary Classification**: The task is to predict whether a tumor is **malignant (M)** or **benign (B)**.
- **Multiple Models**: A variety of machine learning algorithms, including Logistic Regression, Decision Trees, Random Forest, SVM, and KNN, are applied to predict the outcome.
- **Performance Evaluation**: Models are evaluated based on accuracy, precision, recall, and F1-score to ensure robust results.

## Dataset

The dataset used for this project is the **Breast Cancer Wisconsin (Diagnostic) Dataset** from the UCI Machine Learning Repository. It includes the following attributes extracted from breast cancer cell images:

- **Radius**: Mean of distances from the center to points on the perimeter.
- **Texture**: Standard deviation of gray-scale values.
- **Perimeter**: Length of the boundary of the tumor.
- **Area**: Total number of pixels within the boundary.
- **Smoothness**: Local variation in radius lengths.
- **Compactness**: Perimeter^2 / Area - 1.0
- **Concavity**: Severity of concave portions of the contour.
- **Concave Points**: Number of concave portions of the contour.
- **Symmetry**: Symmetry of the tumor.
- **Fractal Dimension**: Coastline approximation - 1.

### Target Variable:
- **Malignant (M)**: 1
- **Benign (B)**: 0

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/BrijeshRakhasiya/Breast-Cancer-Using-Machine-Learning.git
cd Breast-Cancer-Using-Machine-Learning
pip install -r requirements.txt
```
