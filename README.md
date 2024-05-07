# PRODIGY_ML_02

# K-Means Clustering on Mall Customers

## Introduction
This Python script performs K-Means clustering on a dataset of Mall Customers. It aims to segment customers based on their Annual Income and Spending Score to identify meaningful patterns and customer segments.

## Prerequisites
Before running the script, ensure you have the following:
- Python (version 3.x recommended)
- Necessary Python libraries (pandas, numpy, matplotlib, seaborn, scikit-learn)

## Usage
1. Clone the repository or download the Python script.
2. Ensure the dataset file 'Mall_Customers.csv' is in the same directory as the script.
3. Run the script in a Python environment.

## Script Overview
- The script begins by importing necessary libraries.
- It loads the dataset 'Mall_Customers.csv' containing customer information.
- Data exploration and preprocessing are performed, including checking for missing values, duplicates, and basic statistics.
- Visualizations such as boxplots and pairplots are generated to understand the data distribution and relationships between features.
- Unnecessary columns ('CustomerID', 'Gender') are dropped.
- The data is standardized using StandardScaler to ensure uniformity across features.
- The optimal number of clusters is determined using the Elbow Method and Silhouette Score.
- K-Means clustering is applied to the dataset with the chosen number of clusters.
- Finally, the clusters are visualized, and the Silhouette Score is calculated to evaluate the clustering performance.

## Outputs
- Elbow Method plot to visualize the optimal number of clusters.
- Silhouette Score plot for evaluating clustering performance.
- Scatter plot showing the clusters of customers based on Annual Income and Spending Score.
- Silhouette Score indicating the quality of clustering.

## Conclusion
The script provides insights into customer segmentation using K-Means clustering, which can be valuable for targeted marketing strategies and personalized customer experiences.
