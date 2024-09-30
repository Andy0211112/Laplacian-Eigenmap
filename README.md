# Laplacian eigenmaps
## Introduction

Sometimes, we often face to data lying in a very high-dimensional space made us hard to analyze. The solution to understand the data is dimensionality reduction like principal components analysis (PCA) or multidimensional scaling, which perform a linear mapping while Laplacian eigenmaps that generate nonlinear maps.

The idea of Laplacian eigenmaps is first to construct a graph contained the neighborhood information (weights and connection) of the data set. Then we can find a low-dimensional representation of the data set which preserves *"local"* neighborhood information in a certain sense. And such algorithm is as simple as described.

This locality-preserving character makes it to be stable when the data has some outliers or noise. Also, we found this algorithm can be also viewed as some kind of clustering.
more details: https://github.com/Andy0211112/Laplacian-Eigenmap/blob/main/Report.pdf
