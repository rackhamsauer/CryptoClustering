# CryptoClustering
Clustering and PCA Analysis
This repository contains the clustering and PCA analysis, where the goal was to apply K-Means Clustering and Principal Component Analysis (PCA) to analyze a dataset, determine the number of clusters, and evaluate price changes within specific time frames.

Overview
In this project, I performed the following steps:

K-Means Clustering:
I started by applying K-Means to the dataset and created an elbow graph to determine the optimal number of clusters. I initially chose 4 clusters based on the elbow method, which showed a significant drop in inertia at that point.
Principal Component Analysis (PCA):
After selecting 4 clusters, I proceeded with PCA to reduce the dimensionality of the data. The analysis yielded two results:
Three clusters that accounted for 89.5% of the variance.
Four clusters determined via the elbow method, as a confirmation.
Data Visualization:
After performing PCA, I graphed the PCA-transformed dataset. However, the graph had fewer data points, making it harder to visualize distinct clusters. In contrast, the K-Means graph (with more data points) made it easier to distinguish the clusters.
Price Change Analysis:
I examined the percentage change in price over a 7-day and 24-hour time frame. The results indicated that the price change percentage seems to increase within the 7-day time frame but is not as strongly affected by the 24-hour time frame.
Tools and Resources Used
K-Means Clustering for determining clusters.
PCA (Principal Component Analysis) for dimensionality reduction.
Matplotlib for graphing and visualization.
Pandas for data manipulation.
ChatGPT, Stack Overflow, and Peers for troubleshooting and problem-solving during the process.
Key Observations
Elbow Method and K-Means:
The elbow method helped determine the optimal number of clusters. After testing different cluster counts, I chose 4 clusters as the most appropriate.

PCA and Explained Variance:
PCA with 3 clusters explained 89.5% of the variance in the dataset. This allowed me to reduce the complexity of the dataset while retaining a significant amount of information.

Data Visualization:
The PCA visualization made it harder to see distinct clusters due to fewer data points, whereas the K-Means clustering graph was more effective for distinguishing the clusters.

Price Change Analysis:
The 7-day price change percentage increased over time, but the 24-hour price change was less affected, indicating that short-term fluctuations are less significant compared to longer-term trends.

How to Use
Clone the repository to your local machine.
Ensure you have Python, Pandas, Matplotlib, and other required libraries installed.
Run the Jupyter notebook or Python script to replicate the clustering, PCA, and price change analysis.
Review the graphs and analysis to understand the insights derived from the dataset.
Conclusion
This analysis allowed me to apply K-Means Clustering and PCA to reduce the dimensionality and identify clusters within the data. While the PCA visualization was difficult to interpret due to the lower number of data points, the K-Means graph provided clearer insights. The price change analysis also revealed important trends regarding the effect of time frames on price changes.
