# Machine Learning Notebooks — Classification · Clustering · Neural Networks

A collection of foundational machine learning notebooks from my B.Sc. and early M.Sc. coursework, organized by topic. These are learning-focused implementations of core techniques — for my larger, results-driven projects, see the [featured projects on my profile](https://github.com/danishmahmoodali).

## 📁 Structure

```
├── Classification/
│   └── Classification_Models.ipynb   # 5 classic classifiers compared with cross-validation
├── Clustering/
│   └── Clustering_Methods.ipynb      # K-Means & agglomerative clustering with silhouette analysis
└── Neural Networks/
    └── ...                           # Neural network fundamentals
```

<!-- TODO(Danish): adjust the Neural Networks line to name the actual notebooks in that folder -->

## 🔍 What's inside

### Classification
Side-by-side comparison of **Logistic Regression, Decision Tree, Random Forest, SVM, and Gaussian Naive Bayes** on a shared dataset, evaluated with cross-validation — the standard toolkit for tabular classification and the trade-offs between the models.

### Clustering
Unsupervised segmentation with **K-Means and agglomerative (hierarchical) clustering**, including **silhouette analysis** for choosing the number of clusters and comparing cluster quality between methods.

### Neural Networks
Fundamentals of neural network construction and training.
<!-- TODO(Danish): 1-2 accurate sentences about the notebooks actually in this folder -->

## 🛠️ Setup

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

Each notebook is self-contained and downloads or loads its own dataset — open any of them directly in Jupyter or Google Colab.
