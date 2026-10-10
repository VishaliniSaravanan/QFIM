# QFIM-Based Variational Quantum Classifier

This project contains a research notebook exploring information-geometric diagnostics of variational quantum classifiers (VQCs) using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset.

## Overview

The notebook evaluates a QFIM-based variational quantum classifier and compares it against classical and quantum baselines, including:

- Logistic Regression
- SVM with RBF kernel
- Random Forest
- Gradient Boosting
- Quantum Kernel SVM
- Quantum Convolutional Neural Network (QCNN)

It also studies optimization behavior, effective dimension, noise effects, and diagnostic measures based on the Quantum Fisher Information Matrix (QFIM).

## Files

- `qfim-ver-2.ipynb` — main analysis notebook
- `QFIM_VQC_Results_v2/` — generated outputs, figures, metrics, and saved experiment artifacts

## Requirements

The notebook installs the required Python packages automatically, including:

- Qiskit
- Qiskit Aer
- Qiskit Machine Learning
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenPyXL
- TQDM

## Run locally

1. Open the notebook in Jupyter or VS Code.
2. Run all cells from the top.
3. If using Google Colab, the notebook will mount Google Drive and save results there automatically.

## Notes

- The project is intended for research and reproducibility.
- Generated result directories may be large and are best excluded from version control.


