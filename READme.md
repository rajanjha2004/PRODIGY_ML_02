Task:
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

Task Overview:
The goal of this project is to group customers of a retail store based on their purchase history, specifically focusing on their Annual Income and Spending Score. We use the K-Means Clustering Algorithm to segment customers into different clusters for better business insights and marketing strategies.

Steps Taken to Satisfy the Task:

1. Data Loading:
The dataset was loaded from a CSV file, containing customer data such as Age, Gender, Annual Income, and Spending Score.
Feature Selection:

2. Two important features were selected for clustering:
Annual Income: The yearly income of the customer.
Spending Score: A score assigned to the customer based on their shopping behavior and spending patterns.

3. Data Preprocessing:
We checked for missing values, but no missing data was found in the selected features.

4. Optimal Number of Clusters:
To find the ideal number of clusters, we used the Elbow Method, which calculates the Within-Cluster Sum of Squares (WCSS) for different cluster numbers (ranging from 1 to 10).
The Elbow Point was identified as 5 clusters, where the WCSS significantly reduces.

5. K-Means Clustering:
The K-Means Algorithm was applied with 5 clusters. Each customer was assigned to one of the clusters based on their income and spending patterns.

6. Cluster Visualization:
The clusters were visualized in a scatter plot, with customers in each cluster represented by a different color.
The centroids of the clusters were also plotted to show the center of each group.

Conclusion:
The clustering successfully grouped customers into 5 distinct segments based on their Annual Income and Spending Score. These clusters provide insights into customer behavior, helping the retail store tailor marketing strategies and offers to specific customer groups.