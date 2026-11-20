# Breast Cancer AI

A supervised/ unsupervised machine learning project that predicts breast cancer diagnosis from the Breast Cancer Wisconsin dataset.

## Project Overview

The project explores:
- Logistic Regression
- Random Forest
- Neural Network (MLP)
- PCA dimensionality reduction
- K-Means clustering
- Precision-recall threshold tuning

## Dataset

The data is stored in `data/data.csv`. 
The target variable is `diagnosis`:

`M` = Malignant
`B` = Benign

The dataset is split into 80% training and 20% testing data using a stratified split.

## Models

Logistic Regression is used as the baseline. Random Forest provides a nonlinear ensemble comparison, while MLP is used as a neural network model. Classification thresholds are tuned to prioritize malignant case recall.

## Results

Logistic Regression achieved approximately 98% test accuracy. Random Forest results are reported directly in the notebook. The MLP threshold is adjustable to balance malignant recall against false-positive benign classifications.

## Setup

```bash
python -m pip install -r requirements
jupyter lab
```

Choose `notebooks/BreastCancer.ipynb` and run all cells from top to bottom.

## Repository Structure

```text
Breast-Cancer-AI/
├── data/
├── docs/
├── models/
├── notebooks/
├── outputs/
├── src/
├── tests/
├── README.md
└── requirements
```

## Note

This project is for educational research for machine and deep learning only and is not a substitute for professional medical diagnosis.
