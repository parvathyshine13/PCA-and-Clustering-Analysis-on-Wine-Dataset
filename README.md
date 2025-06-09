# PCA and Clustering Analysis on Wine Dataset

## 📌 Overview
This project explores how Principal Component Analysis (PCA) can be used for dimensionality reduction, and how clustering techniques behave both before and after PCA transformation. The dataset used is the classic Wine dataset, which includes 13 features describing various chemical properties of wines derived from three cultivars.

## 🔧 Tools and Libraries Used
- Python  
- NumPy, Pandas – Data manipulation  
- Seaborn, Matplotlib – Visualization  
- Scikit-learn – PCA, clustering, and evaluation  
- Jupyter Notebook – Analysis environment  

## 📊 Exploratory Data Analysis
- Loaded and inspected the structure of the dataset.
- Checked for missing values and outliers.
- Plotted histograms, box plots, and density plots to understand feature distributions.
- Created a correlation heatmap to identify strongly related features.

## 🔍 Principal Component Analysis (PCA)
- Standardized the dataset to ensure zero mean and unit variance.
- Applied PCA to reduce the dimensionality of the dataset.
- Identified the optimal number of principal components using a scree plot and cumulative explained variance.
- Transformed the original dataset into the principal component space.

## 📈 Clustering on Original Data
- Applied K-Means clustering to the original (non-PCA) dataset.
- Determined the optimal number of clusters using the Elbow Method.
- Evaluated clustering quality using metrics such as Silhouette Score and Davies-Bouldin Index.
- Visualized cluster assignments with scatter plots.

## 🔄 Clustering on PCA-Transformed Data
- Applied K-Means clustering to the PCA-transformed dataset.
- Visualized the clusters in the reduced 2D component space.
- Evaluated and compared clustering performance using the same metrics.

## 📌 Analysis and Comparison
- Compared clustering results between original and PCA-transformed datasets.
- Discussed observed changes in cluster separation and compactness.
- Analyzed how dimensionality reduction affected interpretability and performance.
- Highlighted the trade-offs of using PCA for unsupervised learning tasks.

## ✅ Conclusion and Insights
- PCA improved clustering visualization by reducing noise and dimensional complexity.
- Silhouette scores showed that PCA did not significantly degrade clustering performance.
- PCA is useful when dealing with high-dimensional data, especially for visualization and speeding up algorithms.
- For this dataset, clustering with and without PCA both yielded meaningful groupings, but PCA aided in clearer separation when plotted in 2D.
