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



#### How to Run the Code
1. Download the repository or clone it using the following command:
   ```bash
   git clone https://github.com/<your-username>/MLP_CreditRisk_Tutorial.git
   cd MLP_CreditRisk_Tutorial

Open the Jupyter Notebook file (creditrisk_nn.ipynb) in your preferred environment, such as:
Jupyter Notebook
VSCode
Google Colab
Run the cells step-by-step to:
Load and preprocess the dataset.
Experiment with different architectures (depths and widths).
Visualize results and evaluate performance.

Replace `<your-username>` with your actual GitHub username before copying it into your `README.md`. Let me know if you need anything else! 😊
