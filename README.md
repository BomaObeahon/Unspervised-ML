# machine_learning_project-unsupervised-learning

Overview:

In this project, we will perform a full unsupervised learning machine learning project on a "Wholesale Data" dataset. The dataset refers to clients of a wholesale distributor and includes the annual spending in monetary units (m.u.) on diverse product categories.
The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.

EDA - Exploratory Data Analysis & Pre-processing:
Tasks:
Data Import: Import the dataset and the necessary Libraries in Python for the task at hand.
Data Cleaning: Checked the dataset for any missing or incorrect data. There were no missing or duplicated values.
Data Description: Generated summary statistics such as mean, median, and standard deviation for each column of the dataset. 
Data Visualization: Created various visualizations such as scatterplot, boxplots, pairplots, and heatmap to understand the relationships and trends between the different variables in the dataset. 
Outlier Detection: Checked for any outliers in the dataset and they were.
Correlation Analysis: Calculated the correlation between different variables in the dataset to determine which variables are highly correlated and which ones are not. For example, "Grocery" and "Detergents_Paper" had a correlation of 0.92 which indicates a strong positive correlation.

Conclusion:

1. It is best practice to allow the algorithm choose the optimal number of clusters required when using K-Means in Unsupervised Machine Learning, this can be done by using the Elbow Method. WCSS(within cluster sum of squares) is used to determine the optimal number of clusters.The approach consists of looking for a kink or elbow in the WCSS graph. Usually, the part of the graph before the elbow would be steeply declining, while the part after it – much smoother. In this instance, the kink comes at the 5 clusters mark. So, we’ll be keeping a five-cluster solution.

2. The Silhouette Score of 0.35495 in K-Means Clustering implies that the clustering has produced moderately well-separated clusters.

3. The output "Principal Components (Explained Variance Ratio)" indicates the proportion of variance in the original dataset explained by each principal component obtained through PCA.Principal Component 1 explains approximately 44% of the variance in the dataset. Principal Component 2 explains approximately 28% of the variance in the dataset.The explained variance ratio tells how much information (variance) is retained in each principal component compared to the original dataset. In this case, Principal Component 1 captures the highest amount of variance, followed by Principal Component 2.
4. The Silhouette Score of 0.239 in Hierarchical Clustering indicates that the clusters are reasonably well-separated, but there may still be some overlap between clusters or room for improvement in cluster separation.