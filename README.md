# Customer Segmentation using K-Means

## Overview
This project focuses on performing customer segmentation on the Mall Customers dataset using the K-Means clustering algorithm. The aim is to group customers into distinct clusters based on their behavior, which can help businesses design targeted marketing strategies.

## Dataset
The dataset used is the **Mall Customers dataset**, which contains customer information such as:
- CustomerID  
- Gender  
- Age  
- Annual Income  
- Spending Score  

## Steps Followed
1. **Data Cleaning & Preparation**  
   - Removed unnecessary columns (CustomerID).  
   - Checked for missing values (none were found).  

2. **Feature Selection**  
   - Selected **Age** and **Spending Score** for clustering.  

3. **Finding Optimal Clusters**  
   - Used the **Elbow Method** to identify the optimal number of clusters.  

4. **Model Training**  
   - Applied **K-Means Clustering** with the chosen number of clusters.  

5. **Cluster Visualization**  
   - Visualized customer groups on a 2D scatter plot for better understanding.  

## Silhouette Score
After clustering, we calculated the **Silhouette Score** to evaluate clustering performance.

- **Definition:** The score measures how well data points fit within their cluster compared to other clusters.  
- **Range:** From -1 to +1  
  - Close to +1 → Clusters are well separated.  
  - Around 0 → Clusters overlap.  
  - Negative → Clustering is likely wrong.  

In our project, the **Silhouette Score = 0.445**, which indicates that the clusters are reasonably well-formed and the segmentation is meaningful.  

## Conclusion
We performed customer segmentation using the Mall Customers dataset.

- Chosen features: **Age** and **Spending Score**  
- The analysis grouped customers into meaningful clusters, which can assist in creating targeted marketing strategies.  

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
