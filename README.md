# Mall_Customer_Segmentation_Using_Kmeans_clustering
📖 Project Overview

This project applies unsupervised machine learning (K-Means clustering) to segment customers based on their purchasing behavior. The goal is to identify distinct customer groups to help businesses improve marketing strategies.

📊 Dataset
Mall Customer Dataset
Features used:
Age
Annual Income (k$)
Spending Score (1–100)

🔍 Exploratory Data Analysis (EDA)
Used scatter plots to analyze relationships between features
Observed strong clustering patterns between:
Annual Income vs Spending Score
Weak relationship observed for:
Age vs Income

📈 Methodology
Data Preprocessing
Selected relevant numerical features
Removed non-numeric columns like CustomerID
Finding Optimal Clusters
Used Elbow Method (WCSS)
Identified optimal number of clusters: K = 5
Model Building
Applied K-Means clustering using Scikit-learn
Generated cluster labels for each customer
Visualization
Plotted clusters using Matplotlib
Highlighted cluster centers

🎯 Results & Insights

Identified 5 customer segments:

High Income – High Spending (Premium Customers)
High Income – Low Spending (Conservative Customers)
Low Income – High Spending (Impulsive Buyers)
Low Income – Low Spending (Low-Value Customers)
Average Income – Average Spending (Regular Customers)

🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
