##🛍️ Customer Segmentation using K-Means
#📌 Project Overview

This project applies K-Means Clustering to segment customers based on their Age, Annual Income, and Spending Score.
The dataset is from a shopping mall and helps in identifying customer groups (e.g., high-income spenders, budget shoppers, etc.) for targeted marketing strategies.

#⚙️ Tools & Libraries

Python

Pandas – data handling

Scikit-learn – K-Means, preprocessing

Matplotlib & Seaborn – data visualization

#🗂️ Dataset

Columns:

CustomerID → Unique customer ID (not used in clustering)

Genre → Gender (not used in clustering)

Age → Customer’s age

Annual Income (k$) → Annual income in thousands

Spending Score (1-100) → Spending behavior score

#🚀 Steps Implemented

Data Preprocessing

Removed irrelevant columns (CustomerID, Genre)

Normalized features (Age, Annual Income, Spending Score)

Elbow Method

Determined the optimal number of clusters (K)

Model Training

Applied K-Means with chosen K

Assigned cluster labels to customers

Visualization

Scatter plots of clusters (Annual Income vs Spending Score)

Cluster-based segmentation insights

#📊 Results

Clear segmentation of customers into distinct groups

Business can use insights for targeted marketing & personalized offers

Example Visualization:

Annual Income vs Spending Score with colored clusters

#📂 Deliverables

Jupyter Notebook: Implementation of clustering

Elbow Plot: Choosing optimal K

Cluster Scatter Plots: Visualizing customer groups

#✅ Outcome

Learned how to apply unsupervised learning (K-Means) to a real-world dataset.

Identified meaningful customer segments for business strategy.
