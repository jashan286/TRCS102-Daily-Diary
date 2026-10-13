# Session 23: Hierarchical Clustering

## Topics Covered
- Introduction to Hierarchical Clustering
- Agglomerative and Divisive Clustering
- Dendrograms
- Distance Measures and Linkage Methods
- Applications of Hierarchical Clustering

## Key Learnings

### 1. Introduction
Hierarchical Clustering is an unsupervised machine learning algorithm used to group similar data points into clusters. It creates a hierarchy of clusters that can be represented using a tree-like diagram called a dendrogram.

### 2. Types of Hierarchical Clustering
- **Agglomerative Clustering:** Starts with each data point as a separate cluster and repeatedly merges the closest clusters.
- **Divisive Clustering:** Starts with all data points in one cluster and repeatedly splits them into smaller clusters.

### 3. Dendrogram
A dendrogram is a tree-like diagram that shows how clusters are formed or merged at different distances. By cutting the dendrogram at a particular height, we can decide the number of clusters.

### 4. Linkage Methods
Linkage methods determine the distance between two clusters:
- **Single Linkage:** Uses the minimum distance between points in two clusters.
- **Complete Linkage:** Uses the maximum distance between points in two clusters.
- **Average Linkage:** Uses the average distance between points in two clusters.
- **Ward's Linkage:** Merges clusters to minimize the increase in within-cluster variance.

### 5. Advantages and Limitations
**Advantages:**
- Does not always require the number of clusters in advance.
- Helps visualize relationships between clusters.
- Can reveal nested groups in data.

**Limitations:**
- Can be computationally expensive for large datasets.
- Early merging or splitting decisions are generally not reversed.

## Common Python Tools
Using Python's `scikit-learn` library:
- `AgglomerativeClustering()` – Creates a hierarchical clustering model.
- `fit()` – Learns clusters from the dataset.
- `fit_predict()` – Fits the model and returns cluster labels.
- `scipy.cluster.hierarchy.dendrogram()` – Displays a dendrogram.
- `scipy.cluster.hierarchy.linkage()` – Calculates hierarchical clustering relationships.

## Key Takeaways
- Hierarchical Clustering is an unsupervised learning technique.
- Agglomerative clustering follows a bottom-up approach.
- Divisive clustering follows a top-down approach.
- A dendrogram helps visualize cluster relationships.
- Linkage methods affect how clusters are combined.

## Summary
In this session, I learned how Hierarchical Clustering groups similar data points into a hierarchy. I studied its two types, different linkage methods, and the role of dendrograms in selecting clusters. I also explored Python tools used to implement and visualize hierarchical clustering.
