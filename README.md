# K-means-Clustering-AI-ML-Internship

K-Means Clustering Project

This repository contains multiple versions of K-Means Clustering implementations using the Mall Customers dataset, showcasing step-by-step improvements from a basic beginner-friendly version to a fully automatic clustering solution.

1️⃣ Beginner-Friendly Manual K-Means

Description:
A simple and easy-to-understand K-Means clustering implementation for beginners using the Mall Customers dataset. This version manually chooses K after checking the Elbow Method plot.

Key Features:

Loads dataset manually

Uses Annual Income & Spending Score as features

Finds optimal K via Elbow Method

Plots clusters and centroids

Calculates Silhouette Score for evaluation
<img width="800" height="200" alt="image" src="https://github.com/user-attachments/assets/e1f62f8c-934f-416d-a177-ad3382cb210a" />


Example Outputs:
Elbow Method:
https://github.com/lalit2244/K-means-Clustering-AI-ML-Internship/blob/c384cf27829119cf4b2207e2024310eb8e2eb409/pca_elbow_plot.png


Clusters Plot:


Silhouette Score:


2️⃣ Universal PCA Version

Description:
An advanced version that automatically works with any dataset. If the dataset has more than 2 features, PCA is used to reduce it to 2 dimensions for visualization.

Key Features:

Works with any CSV dataset containing numeric columns

Automatically scales features

Elbow Method for finding K

PCA-based visualization for datasets with >2 features

Saves clustered dataset to CSV

Example Outputs:
Elbow Method:


PCA Cluster Visualization:


3️⃣ Dual Metric K Selection (Elbow + Silhouette)

Description:
Version that plots both Elbow Method and Silhouette Score together, making it easier to choose the best number of clusters.

Key Features:

Shows WCSS (Elbow) & Silhouette Score in one figure

Auto-selects numeric columns

Scales features before clustering

PCA visualization included

Example Outputs:
Elbow + Silhouette Plot:


PCA Cluster Visualization:


4️⃣ Fully Automatic K Selection

Description:
No manual choice of K required. The best K is selected automatically based on the highest Silhouette Score.

Key Features:

Tests multiple K values

Picks K with highest silhouette score

Plots both metrics for confirmation

PCA 2D visualization of final clusters

Saves clustered dataset to CSV

Example Outputs:
Auto K Selection Plot:


PCA Cluster Visualization:


🛠 Tech Stack

Python

Pandas — Data handling

NumPy — Numerical operations

Matplotlib & Seaborn — Visualization

Scikit-learn — K-Means, PCA, Silhouette Score, Scaling

📂 Repository Structure
📁 KMeans-Clustering-Project
│── 📄 beginner_kmeans.ipynb
│── 📄 universal_pca_kmeans.ipynb
│── 📄 dual_metric_kmeans.ipynb
│── 📄 auto_kmeans.ipynb
│── 📁 screenshots
│    ├── elbow_plot.png
│    ├── clusters_plot.png
│    ├── silhouette_score.png
│    ├── pca_elbow_plot.png
│    ├── pca_clusters_plot.png
│    ├── dual_metric_plot.png
│    ├── dual_clusters_plot.png
│    ├── auto_k_plot.png
│    ├── auto_k_clusters.png
│── 📄 Mall_Customers.csv
│── 📄 README.md
