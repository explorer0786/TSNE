# t-Distributed Stochastic Neighbor Embedding (t-SNE) in Machine Learning

## Overview
t-Distributed Stochastic Neighbor Embedding (**t-SNE**) is a non-linear dimensionality reduction technique primarily used for **visualizing** high-dimensional data in a lower-dimensional space (typically 2D or 3D). It preserves local structures by placing similar data points close together.

## Key Concepts

- **Dimensionality Reduction**: t-SNE reduces high-dimensional data into 2D or 3D for better visualization.
- **Local Structure Preservation**: Unlike PCA, t-SNE focuses on maintaining local relationships between data points.
- **Probability Distributions**: t-SNE models pairwise similarities in high and low-dimensional space using probability distributions.
- **Applications**: Commonly used in:
  - Data exploration
  - Clustering visualization
  - Feature analysis in machine learning
- **Unsupervised Learning**: t-SNE is an **unsupervised learning** technique and does not require labeled data.

## How t-SNE Works

1. **Pairwise Similarities**: Computes probabilities representing similarities between points in high-dimensional space.
2. **Low-Dimensional Mapping**: Assigns corresponding probabilities in low-dimensional space.
3. **Kullback-Leibler Divergence Optimization**: Minimizes the difference between high and low-dimensional distributions using gradient descent.
4. **Iterative Refinement**: Adjusts points iteratively to form meaningful clusters.

## Considerations

- **Computational Cost**: t-SNE is slower than PCA, especially for large datasets.
- **Hyperparameters**:
  - **Perplexity**: Controls balance between local and global structure.
  - **Learning Rate**: Affects convergence speed.
- **Interpretation**: The distances between clusters are not always meaningful in t-SNE.

---
