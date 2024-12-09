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
```
## Usage
### How to Run the Code
1. Download the repository or clone it using the following command:
```bash
git clone https://github.com/<Cynthiaudoye>/MLP_CreditRisk_Tutorial.git
cd MLP_CreditRisk_Tutorial
```
2. Open the Jupyter Notebook file (creditrisk_nn.ipynb) in your preferred environment, such as Jupyter Notebook, VSCode, or Google Colab.
3. Run the cells step-by-step to:
- Load and preprocess the dataset.
- Experiment with different architectures (depths and widths).
- Visualize results and evaluate performance.

## Outputs

Running the notebook generates:

- **Heatmaps** showing:
  - AUC-ROC scores for various depth-width configurations.
  - Validation accuracy across architectures.
  - Validation loss across architectures.
- **Line Plot**:
  - AUC-ROC trends for different neuron counts (widths) across each depth.
- **Confusion Matrix**:
  - Visualizing classification performance on the test set.
- **Performance Metrics**:
  - A comprehensive summary including precision, recall, F1-score, and accuracy.

### Example Plots
Some of the key visualizations include:

- **Heatmaps**:
  - AUC-ROC across depths and widths.
  - Validation accuracy and loss for different architectures.
- **Confusion Matrix**:
  - Highlights how well the model distinguishes between "Good" and "Bad" credit risks.

---

### Files Included
- **`creditrisk_nn.ipynb`**: Jupyter Notebook containing the full implementation of the project, including visualizations (heatmaps, line plots, and confusion matrix).
- **`Images`**:
  - Visualization plots: Heatmap showing AUC-ROC scores for various configurations, Heatmap of validation accuracy, Confusion matrix visualizing classification performance
- **`LICENSE`**: File containing the project's license information.

---

### Key Results
The best-performing model architecture had:
- **Depth**: 4 layers
- **Width**: 64 neurons per layer
- **AUC-ROC**: 0.80
- Class weights significantly improved recall for the minority class ("Bad" credit risks).

---

## References

Datacamp, n.d., Multilayer perceptrons in machine learning. Available at: [https://www.datacamp.com/tutorial/multilayer-perceptrons-in-machine-learning](https://www.datacamp.com/tutorial/multilayer-perceptrons-in-machine-learning) [Accessed 9 Dec. 2024].

Dua, D. & Graff, C., 2019. UCI Machine Learning Repository. Irvine, CA: University of California, School of Information and Computer Science. Available at: [https://www.openml.org/d/31](https://www.openml.org/d/31) [Accessed 9 Dec. 2024].

LeCun, Y., Bengio, Y. & Hinton, G., 2015. Deep Learning. *Nature*, 521(7553), pp.436–444. Available at: [https://doi.org/10.1038/nature14539](https://doi.org/10.1038/nature14539).

Srivastava, N., Hinton, G., Krizhevsky, A., Sutskever, I. & Salakhutdinov, R., 2014. Dropout: A Simple Way to Prevent Neural Networks from Overfitting. *Journal of Machine Learning Research*, 15(1), pp.1929–1958. Available at: [http://jmlr.org/papers/v15/srivastava14a.html](http://jmlr.org/papers/v15/srivastava14a.html).

Hinton, G., Srivastava, N. & Krizhevsky, A., 2012. Improving Neural Networks by Preventing Co-Adaptation of Feature Detectors. *arXiv preprint*, arXiv:1207.0580. Available at: [https://arxiv.org/abs/1207.0580](https://arxiv.org/abs/1207.0580).

He, H. & Garcia, E.A., 2009. Learning from Imbalanced Data. *IEEE Transactions on Knowledge and Data Engineering*, 21(9), pp.1263–1284. Available at: [https://doi.org/10.1109/TKDE.2008.239](https://doi.org/10.1109/TKDE.2008.239).

Goodfellow, I., Bengio, Y. & Courville, A., 2016. *Deep Learning*. Cambridge, MA: MIT Press. Available at: [https://www.deeplearningbook.org](https://www.deeplearningbook.org) [Accessed 9 Dec. 2024].

---

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contact
For questions or collaborations, feel free to reach out:

- **Name**: Cynthia Chinenye Udoye
- **Email**: [cindymary621@gmail.com]
- **GitHub**: [https://github.com/Cynthiaudoye]
- - **LinkedIn**: [https://github.com/Cynthiaudoye](https://www.linkedin.com/in/chinenye-cynthia-udoye-data-scientist/)]
