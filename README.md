# Unsupervised Machine Learning - Iris Dataset Clustering

## Project Overview
This project was completed as part of an internship task with The Sparks Foundation. The primary objective was to apply unsupervised machine learning techniques to the well-known Iris dataset to predict the optimum number of clusters and represent the results visually.

## Dataset
The Iris dataset consists of 150 samples of iris flowers, with three distinct species:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

The goal is to use these features to cluster the dataset into groups that correspond to the three species.

## Objective
The main objective of this project was to predict the optimum number of clusters in the Iris dataset using K-Means Clustering and represent the clustered data visually.

## Methodology
1. Data Preprocessing:
  * Loaded the Iris dataset and performed any necessary data cleaning (if required).
  * Visualized the data to understand its structure and distribution.
2. Determining the Optimum Number of Clusters:
  * Applied the Elbow Method to determine the optimal number of clusters for the K-Means algorithm.
  * Used the Within-Cluster Sum of Squares (WCSS) to identify the "elbow point," which suggests the best number of clusters.
3. K-Means Clustering:
  * Implemented the K-Means clustering algorithm using the determined optimal number of clusters.
  * Fitted the model to the Iris dataset and predicted cluster labels for each data point.
4. Visualization:
  * Visualized the clustered data points using 2D scatter plots.
  * Marked the centroids of the clusters to indicate the center of each group.

## Results
* The K-Means clustering algorithm successfully clustered the data into the optimum number of clusters.
* The visual representation shows how the data points are grouped into clusters, with centroids indicating the center of each cluster.
* The results closely correspond to the actual species in the Iris dataset, demonstrating the effectiveness of K-Means for this task.

## Technologies Used
* Python
* Pandas for data manipulation
* Matplotlib and Seaborn for data visualization
* Scikit-Learn for implementing the K-Means clustering algorithm

## Conclusion
This project successfully demonstrates the application of unsupervised machine learning, specifically K-Means clustering, to the Iris dataset. The results provide insight into how the dataset can be grouped into clusters that correspond to the actual species, validating the effectiveness of the clustering approach.
