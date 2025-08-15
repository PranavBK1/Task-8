Objective: Segment mall customers into distinct groups based on purchasing behavior to enable targeted marketing strategies.

📊 Dataset

Source: Kaggle – Mall Customer Segmentation Dataset
Features Used:

Age

Annual Income (k$)

Spending Score (1-100)

🔹 Steps Followed:

Data Loading & Exploration – Loaded dataset, checked structure, and visualized feature distributions.

Optional PCA for Visualization – Reduced features to 2D for easy plotting.

K-Means Clustering – Applied with init='k-means++' for faster convergence.

Elbow Method – Determined optimal K by analyzing WCSS.

Cluster Visualization – Color-coded clusters in feature space.

Evaluation – Used Silhouette Score to assess clustering quality.

📈 Results:

Optimal K: 5

Silhouette Score: ~0.55 (indicates decent separation)

Insight: Customers are clearly grouped by income and spending patterns, enabling better marketing targeting.

🛠 Tech Stack:

Python

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – K-Means, PCA, Silhouette Score
