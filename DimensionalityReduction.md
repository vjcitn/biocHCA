# Dimensionality reduction class

A general (virtual?) class to store the results of a dimensionality reduction method.

Specialized classes for specific methods, for now PCA.

It should have three slots:

- Sample factors (n x k matrix)
- Gene loadings (p x k)
- Standard deviation explained by each component (k vector)

Issues:

- We need a slot that can be either NULL or matrix, Matrix, HDF5Matrix, DelayedMatrix, etc.
- We need subsetting operations
- Usually, PCA is done on a subset of genes

