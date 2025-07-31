## Numpy

- It is library.It is used for array and matrix

```
    import numpy as np
    one_d_arr = np.array([1,2,3,4])
    two_d_arr = np.array([[1,2,3],[4,5,6],[7,8,9]])
    print(one_d_arr)
    print(two_d_arr)

```

## 1. Numpy Attribute.

- **Shape :** it returns the dimensions. 

    ![alt text](Images/numpy_shape.png)

- **Size :** it returns the size of the array

    ![alt text](Images/numpy_size.png)

- **Ndim :** it returns the array dimensions whether it is one or two dimensions.

- **Dtype :** it returns the datatype of the array.It supports various data types like Integer,float, complex.while creating we can specify.

    ![alt text](Images/numpy_dtype.png)
    ![alt text](Images/numpy_dtype1.png)

- **Tuple to array :** conversion of tuple to array.

    ![alt text](Images/numpy_tuple.png)

- **Zeros and Ones :** print the zeros and ones based on the input.

- **Arange :** it arranges the number based on the range.

    ![alt text](Images/numpy_Arrange.png)

- **Modify the array :** modify the array using arr[3] = 5,arr[1:3] = [1,2,3]

- **Convert an array :** we can convert the array to another data type using astype function.

    ![alt text](Images/numpy_datatypeConversion.png)

- **Math Operation :** we can perform math operation like add,sub,multiply and divide.

    ![alt text](Images/numpy_math.png)

- **Matrix Multiplication :** Multiplying two vectors.

    ![alt text](Images/numpy_matrixMult.png)

- **Transpose :**

    ![alt text](Images/numpy_transpose.png)

- **Filtering :**

    ![alt text](Images/numpy_filtering.png)

- **reshaping array :**

    ![alt text](Images/numpy_reshaping.png)

- **Indexing and Slicing:**

    ![alt text](Images/Slicing.png)

## 2. Linear Alebra

- **L2 Norm(Eucliden Norm)**

    ![alt text](Images/L2Norm.png)

- **L1 Norm(Manhattan Norm)**

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