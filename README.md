
---

## 🟡 Project 1: Unsupervised Exploration

### Goal
Understand whether penguin measurements naturally form groups without using any labels.

### Methods
- K-Means clustering
- Elbow method (inertia vs K)
- PCA for 2D visualization

### Outcome
- Identified potential cluster structure in the data
- Observed natural separation patterns in penguin measurements

### Limitation
- No ground truth available to evaluate clustering quality

---

## 🟢 Project 2: Clustering Validation (Improved Version)

### Goal
Evaluate how well unsupervised clustering aligns with real penguin species.

### Methods
- Feature selection (culmen length, depth, flipper length, body mass)
- Missing value handling
- Standardization (StandardScaler)
- K-Means clustering (K = 3)
- Comparison with true species labels
- Cluster purity score
- PCA visualization

### Outcome
- Clusters strongly correspond to real species groups:
  - Adelie
  - Gentoo
  - Chinstrap
- Demonstrates that morphological features encode biological structure

---

## 📊 Key Insight

Even without labels, K-Means was able to recover meaningful biological groupings.

However, evaluation against true species shows:
- Some overlap between species exists
- Certain species are more easily separable than others

This highlights both the **power and limitations of unsupervised learning**.

---

## 📈 Example Visualizations

- PCA plot of K-Means clusters (unsupervised result)
- PCA plot of true species distribution (ground truth comparison)

---

## 🧠 Skills Demonstrated

- Data preprocessing (cleaning, missing values)
- Feature scaling
- Unsupervised learning (K-Means clustering)
- Model selection (Elbow method)
- Dimensionality reduction (PCA)
- Model evaluation using external labels
- Data visualization

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 Key Takeaway

This project demonstrates a full machine learning workflow:

> From discovering hidden structure in data → to validating it against real-world labels.

It shows how unsupervised learning can uncover meaningful patterns, but also how important evaluation is when ground truth becomes available.

---

## 👤 Author

Personal machine learning project exploring clustering, dimensionality reduction, and model validation using real biological data.
