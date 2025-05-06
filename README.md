# Task 8: Clustering with K-Means

This repository contains the eighth task of my internship at **Elevate Labs**, focused on unsupervised learning using **K-Means Clustering** for customer segmentation.

## 📌 Objective

The objective of this task was to apply K-Means clustering to segment customers based on their attributes, determine the optimal number of clusters using the Elbow Method, visualize the clusters using PCA, and evaluate clustering performance using Silhouette Score.

## 🛠️ Tools Used

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 🔍 Steps Performed

1. **Dataset**  
   Used the *Mall Customers* dataset, which includes customer information like age, annual income, and spending score.

2. **Preprocessing**  
   - Removed non-numeric columns (`CustomerID`, `Gender`) for clustering  
   - Standardized the numerical features for better clustering performance

3. **K-Means Clustering**  
   - Applied K-Means clustering to the dataset  
   - Used the **Elbow Method** to find the optimal number of clusters (K=5)

4. **Dimensionality Reduction**  
   - Applied **PCA** to reduce feature space to 2D for visualization

5. **Visualization**  
   - Plotted the 2D clusters using PCA components and color-coded by cluster labels

6. **Evaluation**  
   - Evaluated the clustering using **Silhouette Score** to measure how well-separated the clusters are

## 📁 Files

- `task8.ipynb` - Notebook with full K-Means implementation
- `Mall_Customers.csv` - Dataset used for clustering
- `README.md` - Documentation for this task

## 📊 Dataset

Dataset: *Mall Customers*  
- 200 entries  
- Features used: `Age`, `Annual Income (k$)`, `Spending Score (1-100)`

## 📈 Evaluation Metrics

- **Elbow Method** for selecting K  
- **Silhouette Score** for evaluating cluster quality
