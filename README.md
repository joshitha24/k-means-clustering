Customer Segmentation with K‑Means

Project Overview

An end-to-end pipeline for segmenting retail customers using K‑Means clustering is needed.

Features: Age, Annual Income (k$), and Spending Score (1‑100).

Goal: Group similar customers for targeted marketing and personalized offers.

Data Source

Dataset: Mall Customer Segmentation Data from Kaggle

Filename: data/mall_customers.csv

Methodology

Data Cleaning:

Check for missing values.

Remove duplicates.

Verify and correct data types.

Exploratory Data Analysis:

Plot histograms to understand feature distributions.

Identify and assess outliers.

Feature Scaling:

Standardize features to zero mean and unit variance.

Dimensionality Reduction:

Apply PCA (n_components=2) for 2D visualization.

Cluster Evaluation:

Use the Elbow Method (inertia vs. K) to find potential K values.

Perform Silhouette Analysis (score vs. K) to assess cluster quality.

Final Clustering:

Fit K‑Means with the optimal number of clusters.

Assign cluster labels to each customer record.

Profile Analysis:

Inverse-transform centroids to original feature units.

Create a summary table of average Age, Income, and Spending Score per cluster.

Results

Visualization: Scatter plot of clusters in PCA space.

Cluster Profiles: Table showing average metrics for each cluster.

Business Insights: Brief descriptions (e.g., “Cluster 0: Young high spenders”).

