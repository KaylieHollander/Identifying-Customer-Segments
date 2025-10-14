# Identify Customer Segments
This project applies unsupervised machine learning to identify distinct customer segments based on demographic and behavioral data. The objective is to uncover meaningful groupings that can guide targeted marketing strategies, improve customer engagement, and inform business decisions.
The project involves data cleaning, preprocessing, dimensionality reduction, and clustering, producing interpretable segment profiles that can be used to tailor customer outreach.

# Methodology

**Techonologies Used:**
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

1. Data Cleaning and Preparation

- Imported and examined two datasets: a general population dataset and a customer dataset.
- Removed redundant columns and standardized column names across both datasets.
- Handled missing values through imputation and feature-wise filtering.
- Encoded categorical variables and normalized numerical features for comparability.

2. Dimensionality Reduction

- Applied Principal Component Analysis (PCA) to reduce feature dimensionality while retaining maximum variance.
- Determined the number of components explaining 80% of the data variance.
- Generated a reduced feature set to improve clustering performance and interpretability.

3. Clustering

- Implemented K-Means clustering to segment customers based on PCA-transformed features.
- Used the elbow method and silhouette scores to determine the optimal number of clusters.
- Assigned cluster labels to customers and interpreted the resulting groups.

4. Segment Profiling and Interpretation
   
- Compared cluster distributions between the general population and customer base.
- Identified segments with higher representation among customers for future targeted campaigns.
- Visualized results with scatter plots and component contributions to enhance interpretability.
