# Human Activity Recognition using Unsupervised Machine Learning

## Overview

This project applies unsupervised machine learning techniques to identify patterns in human activity data. The workflow includes data preprocessing, removal of highly correlated features, and comparison of multiple clustering algorithms to evaluate their ability to group similar activities. Principal Component Analysis (PCA) is then used to visualize the resulting clusters in two dimensions.

---

## Objectives

- Preprocess and clean the dataset
- Remove redundant, highly correlated features
- Determine the optimal number of clusters
- Compare multiple clustering algorithms
- Evaluate clustering performance
- Visualize clusters using PCA
- Identify potential anomalies within clusters

---

## Machine Learning Pipeline

- Data preprocessing (handling missing values and removing zero-variance columns)
- Feature scaling using StandardScaler
- Removal of highly correlated features (correlation > 0.95)
- Elbow Method
- Silhouette Analysis
- Clustering model comparison
- PCA for 2D cluster visualization
- Anomaly detection based on distance to cluster centroids

---

## Algorithms

- K-Means
- Gaussian Mixture Model (GMM)
- BIRCH
- Hierarchical Clustering (Agglomerative)

---

## Technologies

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## Repository Structure

```text
├── dataset/
│   └── human_activity_master.csv
├── Human_Activity_Recognition.ipynb
├── requirements.txt
└── README.md
```

---

## Results

The project compares multiple clustering algorithms using silhouette scores and visualizations to identify the most effective approach for grouping human activity data. PCA provides a clear two-dimensional representation of the resulting clusters, while anomaly detection highlights observations that deviate significantly from their assigned cluster.

---

## Author

**Yassin Zaki**
