# Breast Cancer Classification using Machine Learning

## Overview

This project investigates the use of machine learning algorithms for breast cancer classification using the Breast Cancer Wisconsin dataset.

The project includes custom implementations of k-Nearest Neighbours (k-NN) and Gaussian Naive Bayes, alongside comparisons with scikit-learn implementations to evaluate classification performance.

---

## Project Objectives

- Implement k-Nearest Neighbours from scratch.
- Implement Gaussian Naive Bayes from scratch.
- Compare custom implementations with scikit-learn models.
- Evaluate model performance using cross-validation.
- Analyse classification accuracy across different algorithms.

---

## Dataset

This project uses the **Breast Cancer Wisconsin Dataset**, a widely used benchmark dataset for binary classification in medical diagnosis.

Dataset Source:

https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

---

## Machine Learning Models

- k-Nearest Neighbours (Custom)
- Gaussian Naive Bayes (Custom)
- Decision Tree
- Scikit-learn Implementations

---

## Evaluation

Models are evaluated using:

- Classification Accuracy
- 5-Fold Cross Validation
- Model Comparison

---

## Technologies Used

- Python
- NumPy
- Pandas
- SciPy
- Scikit-learn
- Matplotlib

---

## Repository Structure

```text
breast-cancer-classification/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── breast-cancer-classification.ipynb
│
└── images/
    ├── confusion-matrix.png
    ├── validation-curve.png
    └── pca.png
```

---

## How to Run

Install the required packages.

```bash
pip install -r requirements.txt
```

Open the notebook.

```bash
jupyter notebook breast-cancer-classification.ipynb
```

Run all cells to reproduce the experiments.

---

## Future Improvements

Potential future enhancements include:

- Support Vector Machines
- Random Forest
- XGBoost
- Neural Networks
- Hyperparameter optimisation

---

## Author

**Li Ching**
