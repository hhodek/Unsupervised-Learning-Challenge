# Unsupervised-Learning-Challenge

## Description
For this challenge the goal was to perform cryptocurrency clustering using K-means and Principal Component Analysis (PCA). Cryptocurrency clustering is essential for understanding market trends and identifying groups of cryptocurrencies with similar price behaviors.

## Summary
The cryptocurrency clustering challenge involved several key steps:

1. Found the Best Value for k by Using the Original Data
* Implemented the elbow method algorithm to determine the optimal number of clusters (k) for the original data.
* Visualized the inertia values to identify the best value for k.
* Answered the question: "What's the best value for k?"

2. Cluster the Cryptocurrencies with K-Means by Using the Original Data
* Initialized the K-means model with the best k.
* Fit the K-means model using the original data.
* Predicted and stored cluster labels for each cryptocurrency.
* Created a scatter plot to visualize the clusters based on price changes.
* Optimized the Clusters with Principal Component Analysis (PCA)

3. Apply PCA to reduce the dimensionality of the data.
* Calculated and analyzed explained variances of principal components.
* Created a new DataFrame with PCA data.
* Found the Best Value for k by using the PCA Data

4. Repeated the elbow method analysis using PCA data.
* Visualized and identified the optimal k for PCA data.
* Compared the best k from original and PCA data.
* Clustered the Cryptocurrencies with K-means by Using the PCA Data

5. Initialize and fit K-means with PCA data.
* Predicted and stored cluster labels for cryptocurrencies.
* Visualized clusters based on PCA components.
* Visualized and compared the Results

6. Compared elbow curves and cluster results between original and PCA data.
* Created composite layouts of graphs for side-by-side comparisons
* Analyzed the impact of using fewer features for clustering.

### Credits
- Referenced class materials as well as ChatGPT
