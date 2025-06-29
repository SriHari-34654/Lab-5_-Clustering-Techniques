**Goal of the Lab Work**

  To compare and use two clustering algorithms: Agglomerative Hierarchical Clustering, and DBSCAN.
  
  To learn how altering parameters influence the creation of clusters and their quality.
  
  To apply PCA to data dimension reduction and 2D cluster visualization.

**Major findings of clustering and visualizations**

  The 3 to 5 cluster Hierarchical Clustering produced well separated groups. The dendrogram indicated that there were 3 sets of clusters that provided a natural split on the data.
  
  DBSCAN performed best with eps = 2.0 and min_samples = 3, forming 5 clear clusters and detecting fewer noise points.
  
  The visualization based on PCA was useful in comparing the performance and structure of clustering with varying parameters values.


**Challenges Faced and Decisions Made**

  Obtaining the right number of clusters with Hierarchical Clustering needed interpreting of gaps of dendrograms.
  
  DBSCAN needed multiple experiments with eps and min_samples, as small values caused too much noise and large values merged too many points.
  
  Some overlapping of clusters in higher numbers (like 5) showed potential overfitting, which was considered while analyzing results.
  
  The PCA algorithm was selected to reduce the complexity of the feature space, although this could have led to the minor loss of information.
