# unsupervised-learning
### A3: Unsupervised learning with PCA, t-SNE, k-means, AHC and SOM
**Objective**
Apply and compare the results from five different unsupervised learning techniques:

 - Principal Component Analysis (PCA) 
 - t-distributed Neighbor Stochastic Embedding (t-SNE)  
  - k-means Agglomerative 
  - Hierarchical Clustering (AHC) 
-   Self-Organizing Maps (SOM)

**Data**
The unsupervised learning techniques must be applied on two datasets:
1. Synthetic dataset (A3-data.txt):
o Features: 4 variables, 1 class
o Patterns: 360 patterns
o The class information must “not” be used in the unsupervised learning, only
to identify the classes in the plots
2. Search a dataset from the Internet, with the following characteristics:
o Features: at least 6 variables, and a class attribute
o The class attribute must refer to, at least, 4 different classes
o Patterns: at least 200 patterns
o The class information must “not” be used in the unsupervised learning, only
to identify the classes in the plots

**Unsupervised learning**
- PCA: find and plot the PCA projection in two dimensions, using a different color
for each class
- t-SNE: find and plot the t-SNE projection in two dimensions, using a different
color for each class
- k-means: use k-means to classify the patterns in k = 2, 3, ..., K classes, and
compare the obtained classes with the real ones
- AHC: use the unweighted average (UPGMA) and complete linkage (CL) methods
of AHC, using as input the matrix of Euclidean distances between the original
patterns, and use different colors to represent the patterns in each original class.
You have to plot the resulting dendrogram.
- SOM: use SOM to visualize the data, using different settings (topology and size
of the map, learning rate, neighborhood function, etc.). For the “best” map, also
calculate the component planes. The minimum size for the SOM architecture must
have at least 100 neurons.

**Guidelines**
You may use any software you want —except Weka and Rapidminer— to
calculate PCA, t-SNE, k-means, AHC and SOM
