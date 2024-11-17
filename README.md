# Image Clustering using PCA and Hierarchical Clustering

This project demonstrates the use of **Principal Component Analysis (PCA)** for dimensionality reduction followed by **Hierarchical Clustering** (using the Ward method) to group similar images from the **Fashion MNIST** dataset into 10 clusters. The goal is to analyze the distribution of image labels within each cluster and visualize the results.

## Project Overview

In this project:
1. **PCA** is applied to the Fashion MNIST dataset to reduce the dimensionality while preserving 90% of the variance in the data.
2. **Agglomerative Hierarchical Clustering** is then used to group the data into 10 clusters based on the reduced dimensions.
3. The distribution of true labels in each cluster is visualized through histograms.
4. The results are displayed in a grid format with each cluster's label distribution shown separately.

## Requirements

- **Python 3.x**
- **Libraries**:
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `scipy`
  - `pandas` (if needed for data manipulation)

You can install the necessary libraries by running:

```bash
pip install numpy matplotlib seaborn scikit-learn scipy pandas
