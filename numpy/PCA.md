## PCA with Eigenvalues (Dimensionality Reduction)

- We will reduce the data from 4 dimensions to 2 dimensions using PCA.
- Instead of writing complicated algorithms from the scratch, use sklearn.
- Using Sklearn we can import a model, train it, predict with it, evaluate it, preprocess and visulize the data.
- PCA is a ready made tool that understand your data better, remove noise and redundancy and reduce the data num columns keeps only important data, perform dimensionality reduction.
- using sklearn we can load the datasets which is load_iris.
- Finds the new directions, sort these directions based on eigen values, keep on the top ones and discard the rest.
- Apply PCA, we are telling PCA to reduce the data from 4D -> 2D.
- fit() calculates the eigen vectors and eigenvalues.
- transform() project the data into 2D.

E.g : 
- Compress big image into smaller size without losing pattern.

![alt text](Images/PCA.png)
