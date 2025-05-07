Customer Segmentation with K‑Means:
--> Project Overview:
This repository demonstrates an end‑to‑end pipeline for segmenting retail customers based on Age, Annual Income (k$), and Spending Score (1‑100). By leveraging K‑Means clustering, we group similar customers together to enable targeted marketing, personalized offers, and deeper insights into customer behavior.
--> Data Source:
  Dataset: Mall Customer Segmentation Data from Kaggle
  Filename: data/mall_customers.csv
--> Methodology:
  Data Cleaning: Check for missing values, duplicates, and correct data types.
  Exploratory Data Analysis: Plot histograms to understand distributions and spot outliers.
  Feature Scaling: Standardize features to zero mean and unit variance for fair clustering.
  Dimensionality Reduction: Apply PCA (n_components=2) for 2D visualization.
  Cluster Evaluation: Use the Elbow Method (inertia) and Silhouette Analysis (score) to select the optimal K.
  Final Clustering: Fit K‑Means with chosen K, assign cluster labels.
  Profile Analysis: Inverse transform centroids and summarize cluster characteristics in real-world units.
--> Results:
The final output includes:
A scatter plot of clusters in PCA space.
A profile table showing average Age, Income, and Spending Score per cluster.
Insights for business use (e.g. “Cluster 0: Young high spenders”).
