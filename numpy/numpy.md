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

- **Shape:** it returns the dimensions. 

![alt text](Images/numpy_shape.png)

- **size:** it returns the size of the array

![alt text](Images/numpy_size.png)

- **ndim :** it returns the array dimensions whether it is one or two dimensions.

- **dtype:** it returns the datatype of the array.It supports various data types like Integer,float, complex.while creating we can specify.

![alt text](Images/numpy_dtype.png)
![alt text](Images/numpy_dtype1.png)

- **Tuple to array:** conversion of tuple to array.

![alt text](Images/numpy_tuple.png)

- **zeros and ones :** print the zeros and ones based on the input.

- **arange :** it arranges the number based on the range.

![alt text](Images/numpy_Arrange.png)

- **modify the array:** modify the array using arr[3] = 5,arr[1:3] = [1,2,3]

- **convert an array:** we can convert the array to another data type using astype function.

![alt text](Images/numpy_datatypeConversion.png)