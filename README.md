# Assignment05---Parameter-Optimization-of-SVM
# SVM Optimization on UCI Letter Recognition Dataset

## Overview

This project involves optimizing a Support Vector Machine (SVM) classifier on a multi-class dataset from the UCI Machine Learning Repository using different random train-test splits.

## Dataset

- **Name**: Letter Recognition
- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Letter+Recognition)
- **Samples**: ~20,000 instances
- **Classes**: 26 (A-Z)

## Steps

1. The dataset was split into 10 random samples (70% training, 30% testing).
2. Each sample was trained with `NuSVC` using 100 random parameter combinations.
3. The best parameters and accuracy for each sample were recorded.
4. A convergence graph was plotted for the sample with the highest accuracy.

## Results

Results are saved in:
- `optimized_svm_results.csv` — table of best accuracies and parameters.
- `convergence_plot.png` — convergence graph for best sample.

## Requirements

```bash
pip install scikit-learn pandas matplotlib
