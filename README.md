# K_Means
This Python script performs a K-Means clustering analysis on a dataset representing various branches of an organization. It uses machine learning and data visualization techniques to categorize branches based on their performance metrics. The script is ideal for business analysts, data scientists, and decision-makers who want to understand the performance patterns of different branches and make data-driven decisions.


**Key Features**
1. Data Preparation: The script creates a DataFrame with data related to branch performance, including employee count, location quality, investment, expenses, and sales.
2. Data Standardization: Numerical data is standardized using StandardScaler from the sklearn.preprocessing module to ensure uniformity for clustering.
3. Dimensionality Reduction: Applies Principal Component Analysis (PCA) to reduce the dimensionality of the data, facilitating visualization in 2D space.
4. Optimal Cluster Determination: Utilizes the Elbow Method to determine the optimal number of clusters for K-Means clustering.
5. Clustering with K-Means: Implements the K-Means clustering algorithm from sklearn.cluster to categorize branches into clusters based on their performance metrics.
6. Visualization:
Visualizes the Elbow Method results to aid in selecting the appropriate number of clusters.
Presents the clustering results in a 2D scatter plot using PCA components.
7. Cluster Assignment: The final DataFrame is displayed with each branch's ID and its corresponding cluster assignment.

**Usage**
Input: Modify the 'data' dictionary in the script to reflect your specific dataset.
Output: The script outputs visualizations for the Elbow Method and PCA-based clustering, and prints a DataFrame showing the cluster assignment for each branch.

**Requirements**
The following Python libraries are needed to run this script:
pandas: For data manipulation and analysis.
matplotlib: For creating visualizations.
sklearn: For machine learning tools, including scaling, PCA, and K-Means clustering.
