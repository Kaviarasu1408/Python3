## Linear Algebra

## 1. L2 Norm(Eucliden Norm)
- L2 Norm is the shortest distance from A to B.
- you can cut diagonally[Shortest distance].
- sqr(3)+sqr(4) = sqr(9+16) = 5.

    ![alt text](Images/L2Norm.png)

## 2. L1 Norm(Manhattan Norm)
- L1 is the you need to walk along the street to reach from A to B[horizontal + vertical].
- You cannot cut diagonally.
- sum of the absolute values.

    ![alt text](Images/L1Norm.png)

- **Distance Matrices** : Euclidean distance.

    ![alt text](Images/numpy_Vector.png)

- **EigenValues & EigenVectors** :
- Eigen vector like a direcion..that doesn't change.
- Eigen values are like how much it is strches or shrik.

    ![alt text](Images/eigenVal.png)

- **Singular Value Decomposition** : Using SVD we can break the matrix into 3 pieces and we can reconstruct.

    ![alt text](Images/numpy_svd.png)

- **Loss function**: Loss function is used to check how wrong our model is.Types of Loss functions.

- Mean Squared Error: common for predicting numbers.
- Mean Absolute Error: treat everything equally
- Binaray cross entropy: Yes/No and spam/Not spam
- categorical cross entropy: predict more than 2 classes. predict if a photo is a dog, cat or rabbit.