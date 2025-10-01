# numpy-and-pandas
# What is NumPy?
NumPy (Numerical Python) is a fundamental package for scientific computing in Python. It provides:

Efficient multi-dimensional arrays (ndarray)

Mathematical functions to operate on arrays

Tools for integrating with C/C++ and Fortran code

Support for linear algebra, Fourier transforms, and random number generation
# Core Features of NumPy
   # 1. Creating Arrays

      import numpy as np
   
      a = np.array([1, 2, 3])           # 1D array
      b = np.array([[1, 2], [3, 4]])    # 2D array
# 2. Array Operations

      a = np.array([1, 2, 3])
      print(a + 1)        # [2 3 4]
      print(a * 2)        # [2 4 6]
# 3. Array Attributes

      print(a.shape)      # (3,)
      print(a.dtype)      # int64 (or int32 depending on system)
# 4. Useful Functions

      np.zeros((2, 3))    # 2x3 array of zeros
      np.ones((2, 3))     # 2x3 array of ones
      np.eye(3)           # 3x3 identity matrix
      np.arange(0, 10, 2) # [0 2 4 6 8]
      np.linspace(0, 1, 5)# [0. 0.25 0.5 0.75 1.]
# 5. Indexing and Slicing

      a = np.array([10, 20, 30, 40])
      print(a[1:3])       # [20 30]
# 6. Broadcasting
Allows operations on arrays of different shapes.

   a = np.array([[1], [2], [3]])
   b = np.array([10, 20, 30])
   print(a + b)
# 7. Linear Algebra

   A = np.array([[1, 2], [3, 4]])
   B = np.array([[2, 0], [1, 2]])
   print(np.dot(A, B))     # Matrix multiplication
   print(np.linalg.inv(A)) # Inverse of A
# Why Use NumPy?
Speed: Much faster than native Python lists

Memory efficiency

Rich ecosystem: Used in pandas, scikit-learn, TensorFlow, etc.

