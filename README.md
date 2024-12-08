# Exploring Depth and Width in Multi-Layer Perceptron for Credit Risk Prediction

## Overview
This project investigates how the architecture of Multi-Layer Perceptrons (MLPs) impacts their performance in predicting credit risk. Using the imbalanced "Credit-G" dataset from OpenML, the tutorial focuses on exploring the effects of varying the depth (number of layers) and width (neurons per layer) on model performance.

The analysis includes:
- Addressing class imbalance with class weights.
- Evaluating key metrics such as AUC-ROC, accuracy, precision, recall, and F1-score.
- Visualizing results using heatmaps and line plots to demonstrate trade-offs in model design.

## Features
- Detailed implementation of MLPs with varying architectures.
- Class imbalance handling through class weights.
- Reproducible results with code and visualizations for performance metrics.
- Practical insights for applying neural networks to financial data.

---

## Installation
To replicate this project, ensure you have the following dependencies installed:

### Required Libraries
- `tensorflow`
- `scikit-learn`
- `pandas`
- `matplotlib`
- `seaborn`

### Install Dependencies
Run the following command to install all necessary packages:
```bash
pip install tensorflow scikit-learn pandas matplotlib seaborn
