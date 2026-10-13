# Session 22: K-Means Clustering

## Topics Covered
- Introduction to K-Means Clustering.
- Centroids and Cluster Formation.
- Steps of the K-Means Algorithm.
- Choosing the Number of Clusters.

## Key Learnings

- **K-Means:** An unsupervised Machine Learning algorithm that groups data points into K clusters.
- **Centroid:** The center point of a cluster, calculated as the mean of its data points.
- **Distance Calculation:** Euclidean distance is commonly used to assign data points to the nearest centroid.
- **Cluster Assignment:** Each data point is assigned to the cluster with the nearest centroid.
- **Centroid Update:** Centroids are recalculated until the algorithm converges or reaches a stopping condition.
- **Elbow Method:** Helps estimate a suitable number of clusters by examining the within-cluster sum of squares (WCSS).

## Steps of K-Means
1. Choose the number of clusters (K).
2. Initialize K centroids.
3. Assign each data point to its nearest centroid.
4. Recalculate the centroids.
5. Repeat until the assignments or centroids stabilize.

## Common Python Tools
- `KMeans()` – Creates a K-Means clustering model.
- `fit()` – Trains the clustering model.
- `predict()` – Assigns new data points to clusters.
- `fit_predict()` – Fits the model and returns cluster labels.
- `inertia_` – Returns the within-cluster sum of squares.

## Key Takeaways
- K-Means groups similar data points into clusters.
- The value of K must be selected before fitting the model.
- Feature scaling can improve clustering results.
- The Elbow Method helps choose an appropriate K.

## Summary
Learned how K-Means clustering works, including centroid initialization, cluster assignment, centroid updates, and selecting the number of clusters using the Elbow Method.
