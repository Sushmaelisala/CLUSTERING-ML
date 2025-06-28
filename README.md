# CLUSTERING-ML
This project implements a machine learning-based system for efficient car assignment using various regression technique.

<h1>The Art of Clustering</h1>
This project demonstrates unsupervised machine learning using clustering algorithms. It involves grouping data points based on similarity without predefined labels. Techniques like K-Means,K-Medoids,Hierarchical with Single and Complete are applied to visualize and interpret patterns within the dataset.

<h1>🧠 Objective</h1>
- Analyze behavioral data like Instagram visit scores and online spending ranks to cluster users into groups such as:

- High spenders influenced by social media

- Casual users with average or low spend

- Passive users are not influenced by Instagram

<h1>🛠️ Clustering Algorithms Used</h1>

K-Means Clustering – Partitions data into K groups by minimizing the variance within each cluster.

K-Medoids Clustering – Similar to K-Means but uses actual data points (medoids) as cluster centers, making it more robust to outliers.

<h1>Agglomerative Hierarchical Clustering</h1>

Single Linkage – Merges the closest pair of clusters based on the shortest distance.

Complete Linkage – Merges clusters based on the farthest distance between points.

<h1>📊 Dataset Features</h1>

Instagram visit score: A numerical value indicating user engagement with the platform.

Spending_rank (0 to 100): A normalized spending score.

User ID and assigned Cluster

<h1>📈 Visualizations</h1>

Cluster Scatter Plots: Each algorithm shows colored plots representing user groups.

Dendrograms: Visual representations from hierarchical clustering to help decide the number of clusters.

Cluster Annotations: Brief user persona descriptions for each cluster (e.g., high usage, high spenders vs. low activity, low spenders).

<h1>🧠 Technologies Used</h1>

- Python
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn (if plots are included)
- HTML export from Jupyter

<h1>📊 Project Highlights</h1>
- Exploratory data analysis
- Model selection and training
- Performance metrics evaluation
