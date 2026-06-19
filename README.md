# 🐧 Penguin Clustering Project

## Overview
This project applies unsupervised machine learning to a dataset of penguin measurements collected in Antarctica. The goal is to discover natural groupings in the data without using species labels.

We use **K-Means clustering** to group penguins based on physical characteristics and then visualize the clusters using **PCA (Principal Component Analysis)**.

---

## Dataset
The dataset contains measurements of penguins:

- Culmen length (mm)
- Culmen depth (mm)
- Flipper length (mm)
- Body mass (g)
- Sex

---

## Methods Used

### 1. Data Preprocessing
- Handled categorical variable (`sex`) using one-hot encoding
- Standardized features using `StandardScaler`

### 2. Finding Optimal Clusters
- Used the **Elbow Method**
- Tested K values from 1 to 10
- Selected K = 4 based on inertia plot

### 3. K-Means Clustering
- Applied K-Means algorithm to group penguins
- Assigned cluster labels to each data point

### 4. Cluster Analysis
- Computed mean feature values per cluster
- Interpreted clusters based on biological characteristics

### 5. Visualization
- Reduced dimensions using **PCA (2D)**
- Visualized clusters in a scatter plot

---

## Key Insight
The clustering reveals natural groupings in penguin physical characteristics that likely correspond to real species differences, even though species labels were not used during training.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
