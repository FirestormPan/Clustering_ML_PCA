# PCA evaluation with Clustering algorithms 
This project evaluates the impact of Principal Component Analysis (PCA) on the performance of several clustering algorithms, with popular metrics.

The project uses the well known Fashion-mnist dataset. PCA reduces the dimensionality of the dataset, which can significantly decrease training time. However, this reduction may also remove useful variance from the data and negatively affect clustering performance. The goal of this project is to train the models MiniBatch K-Means, K-Means and Agglomerative with and without PCA. After the training is complete, I evaluate how much worse the results are when using PCA and if the metrics' results are acceptable. The metrics used are Silhouette coefficient, Calinski-Harabasz Index, Davies–Bouldin index and homogeneity. 

The accompanying project report (written in Greek) contains a detailed analysis of the experiments and results.
