# Exploring-Unsupervised-Learning-with-K-Means-and-PCA

Overview

➢ Implement the K-Means algorithm with 5 clusters

➢ Experiment with Different Cluster Values (K)

➢ Standardize the Dataset(synthetic dataset)

➢ Apply PCA for Dimensionality Reduction

➢ Compare Variance Explained by PCA Components

➢ Choosing the Optimal K (Elbow Method)

Project objective: 

To gain hands-on experience in applying K-Means 

clustering and Principal Component Analysis

(PCA) in Python while interpreting and visualizing the 

results
K-Means Clustering 

How different values of K affect 

clustering:

● When K is too small: Merges 

clusters, poor representation.

● When K is too large: Splits 

clusters, centroids might be close.

Dimensionality 

Reduction with PCA

1. It is observed that the clusters are 

still somewhat distinguishable in the 

2D PCA space.

➢ Indicates that the first two principal 

components capture a significant 

amount of the variance in the data 

that is relevant to the clustering 

structure

2. Explained Variance Ratio per 

Principal Component:

➢ Principal Component 1: 0.5446

➢ Principal Component 2: 0.4554

3. Total Variance Captured by the First 

2 Principal Components: 1.0000

Choosing the Optimal K (Elbow Method)

Findings

The point(50) is where the rate of decrease 

in WCSS starts to slow down significantly. It 

corresponds to the true number of clusters 

used to generate the data(i.e K=5)

Implications:

● After K=5, adding more clusters 

provides diminishing returns in terms 

of reducing WCSS.

● This suggests that we might be 

splitting meaningful clusters.
