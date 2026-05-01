# Deep Learning and Clustering Analysis of Gene Expression Project
*Completed as a final project Carnegie Mellon University's 36669 Graduate Statistical Genomics and High-Dimensional Inference course*

The objective of this analysis is data exploration and cell-wise clustering of single-cell RNA sequencing data for mouse brains. Different methods of unsupervised learning, including K-means, principal component analysis, Poisson mixture models, and variational autoencoders, were used to see how the analysis changes with varying complexity and statistical techniques.

This analysis aims to answer the following questions:


- Regarding clustering, can the 3005 cells be partitioned into biologically meaningful groups that align with known cell types?
- Regarding visualization, can low-dimensional embeddings provide insight into the underlying structure and separability of the data?

This analysis concluded that the applications of principal component analysis (PCA) with K-Means clustering was the best method for partitioning the cells into biologically meaningful groups that aligned with the known cell types. While more complex methods were used, it is possible that they were capturing dynamics in the gene expression that were not relevant to the clustering of cell types since this analysis focused on unsupervised methods. For visualization, the t-distributed Stochastic Neighbor Embedding (t-SNE) method was the most clear in terms of showing different clusters after applying a clustering method, but it did not help in reducing the noise for clustering with KMeans.


The data originated from the following paper:

Zeisel, A. and Muñoz-Manchado, A. B. and Codeluppi, S. and Lönnerberg, P. and La Manno, G. and Juréus, A. and Marques, S. and Munguba, H. and He, L. and Betsholtz, C. et al. (2015). Cell types in the mouse cortex and
hippocampus revealed by single-cell rna-seq. Science, 347(6226):1138–1142
