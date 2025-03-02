# Customer_Segmentation
Classifying the customers on the basis of various factors involving behavior patterns etc.
Customer Segmentation using K-Means Clustering This project aims to perform customer segmentation based on their annual income and spending score using K-Means Clustering. By identifying distinct customer groups, businesses can optimize their marketing strategies, enhance customer targeting, and improve overall profitability.

Project Overview:

Data Collection & Preprocessing:

The dataset contains customer demographic information including Customer ID, Gender, Age, Annual Income (k$), and Spending Score (1-100). No missing values in the dataset.

Feature Selection: For simplicity, only the Annual Income and Spending Score columns are used for clustering.

K-Means Clustering:

The Elbow Method is used to determine the optimal number of clusters. After analyzing the WCSS (Within Cluster Sum of Squares), the optimum number of clusters is set to 5.

Model Training:

K-Means clustering is applied to segment customers into 5 distinct clusters. Each cluster represents a group of customers with similar income and spending habits.

Visualization: The clusters are visualized on a 2D plot, where each cluster is color-coded, and the centroids are highlighted.

Key Dependencies:

Python Libraries: numpy, pandas: For data manipulation and analysis. matplotlib, seaborn: For data visualization. scikit-learn: For implementing the K-Means clustering algorithm.

How to Use: Install the required libraries. Run the notebook/script to load the dataset and perform clustering. Visualize the customer groups to identify patterns in spending and income.

Results: The K-Means model segments the customer base into 5 clusters based on their annual income and spending score. Visual insights are provided, which can be used for targeted marketing and better customer management.

Future Improvements: Incorporating additional features like age and gender for more granular clustering. Experimenting with different clustering techniques like hierarchical clustering.
