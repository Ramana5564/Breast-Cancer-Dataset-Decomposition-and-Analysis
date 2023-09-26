# Breast-Cancer-Dataset-Decomposition-and-Analysis

This repository contains code and analysis for decomposing and analyzing the Breast Cancer dataset using Linear Discriminant Analysis (LDA) in a Jupyter Notebook. LDA is a technique used for dimensionality reduction and improving the separation between classes in classification problems.

## Dataset

The analysis is performed on the [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29) from the UCI Machine Learning Repository. This dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass and is used for binary classification to diagnose breast cancer.

## Overview

This repository contains a Jupyter Notebook that demonstrates how to perform dimensionality reduction and analysis on the Breast Cancer dataset using Jupyter Notebook. The following steps are performed in the notebook:

1.The dataset is standardized using StandardScaler.

2.The data is compressed into 2 Principal Components (PC1, PC2) using PCA.

3.The explained variance for each principal component is printed.

4.A scatter plot for PC2 vs PC1 is generated.

5.The data is compressed into 3 Principal Components (PC1, PC2, PC3) using PCA.

6.The explained variance for each principal component is printed.

7.An interactive 3D scatter plot for PC3 vs PC2 vs PC1 is generated using Plotly.

8.The data is compressed into 2 dimensions using Linear Discriminant Analysis (LDA).

9.A scatter plot for the compressed dimensions is generated.

## Required Libraries

Before running the Jupyter Notebook, make sure you have the following Python libraries installed:

- `scikit-learn`
- `pandas`
- `matplotlib`
- `seaborn`

You can install these libraries using pip:
```bash
pip install scikit-learn pandas matplotlib seaborn
