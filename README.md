# Laptop Clustering: KMeans and PCA Explanation

![joshua-woroniecki-lzh3hPtJz9c-unsplash](https://github.com/fernandasubekti/Laptop-Clustering-KMeans-PCA/assets/116712020/29746b4a-e486-4bd2-bcd1-516262d0fada)

Source image by Joshua Woroniecki


Check my website for better for a better view:

https://fernandasubekti.me/pca-kmeans-and-laptop-clustering-simplified-explanation-and-visualization

Check my Kaggle notebook on:

https://www.kaggle.com/code/fernandasubekti/laptop-clustering-kmeans-pca


## PCA
PCA stands for Principal Component Analysis. It's a statistical technique used to simplify the complexity in high-dimensional data while retaining trends and patterns.
The process of PCA are:
1. First, we make sure the data is adjusted so that its average is at zero, which helps with further analysis.
2. Then, we standardize the data by dividing each adjusted value by how much it typically varies from the average. This makes it easier to compare different variables.
3. After that, we look for special directions and values in the data that reveal its underlying structure. These special directions are called eigenvectors, and the most important one is called the principal component, showing the most variation in the data. These eigenvectors help define important spaces in the data.
4. Finally, we take each data point and see where it falls in these important spaces, giving us a simpler way to understand the original data in fewer dimensions.

## K-Means
K-means is a popular clustering algorithm used in unsupervised machine learning. Its primary goal is to partition a dataset into a pre-defined number of clusters, where each data point belongs to the cluster with the nearest mean (centroid). One of the technique to get the number of clusters is the elbow method. The elbow method is a technique used to determine the optimal number of clusters (k) in a K-means clustering algorithm. It involves plotting the within-cluster sum of squares (inertia) against the number of clusters and looking for the "elbow" point in the graph.
