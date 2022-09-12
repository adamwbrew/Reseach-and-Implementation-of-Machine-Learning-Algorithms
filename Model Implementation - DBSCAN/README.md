# DBSCAN - Density-Based Spatial Clustering of Applications with Noise

## Table of Contents
- [DBSCAN Presentation](#DBSCAN-Presentation)
- [DBSCAN Implementation](#DBSCAN-Implementation)
- [K Means Algorithm Comparision](#K-Means-Algorithm-Comparision)
- [Modules](#Modules)
  - [Pandas](#Pandas)
  - [NumPy](#NumPy)
  - [Matplotlib](#Matplotlib)
  - [Seaborn](#Seaborn)
  - [Sklearn](#Sklearn)
  - [Kneed](#Kneed)
- [Dataset](#Dataset)
  

## DBSCAN Presentation
'DBSCAN_Presentation.pdf' is a PDF formated presentation summarizing **Density-Based Spatial Clustering of Applications with Noise (DBSCAN)** encompassing:
 - Data Processing Steps
 - DBSCAN Model Creation
 - Hypertuning min_samples
 - Hypertuning epsilon
 - DBSCAN and K Means Model Comparsion
 - Model Conclusion with Sources

## DBSCAN Implementation
'DBSCAN_Implementation.ipynb' is a Juypter Notebook documented in Python and Markdown language analyzing the '2021-11-ml-09-k-means-animals-dataset.csv' dataset using DBSCAN primarily using the sklearn.cluster.DBSCAN() function in conjuction with sklearn.metrics.silhouette_score() and numerious other functions listed in Modules. 

## K Means Algoithm Comparision
'K_Means_Comparison.ipynb' is a Juypter Notebook documented in Python and Markdown language analyzing the '2021-11-ml-09-k-means-animals-dataset.csv' dataset using the K Means algorithm of sklearn.cluster.KMeans() to show comparisions of clustering in the file 'DBSCAN_Presentation.pdf'. 

## Modules
Python modules needed for both 'DBSCAN_Implementation.ipynb' and 'K_Means_Comparison.ipynb'.
### Pandas 
<href>https://pandas.pydata.org</href>
### NumPy 
<href>https://numpy.org</href>
### Matplotlib
<href>https://matplotlib.org</href>
  - matplotlib.pyplot
  - matplotlib.colors.ListedColormap
### Seaborn
<href>https://seaborn.pydata.org</href>
### Sklearn
<href>https://scikit-learn.org/stable</href>
  - sklearn.cluster.KMeans
  - sklearn.cluster.DBSCAN
  - sklearn.decomposition.PCA
  - sklearn.impute.SimpleImputer
  - sklearn.neighbors.NearestNeighbors
  - sklearn.metrics.silhouette_score
  - sklearn.preprocessing.StandardScaler
### Kneed
<href>https://pypi.org/project/kneed</href>
  - kneed.KneeLocator

# Dataset 
'2021-11-ml-09-k-means-animals-dataset.csv' is a CSV file of penguin data which is used in both 'DBSCAN_Implementation.ipynb' and 'K_Means_Comparison.ipynb' to recognize unseen clusters in the datset.  