1) What makes numPy.shape() different from numPy.size()?
Ans) numpy.shape() is usedto get complete structural shape of our 2D array
Numpy.shape array have an attribute called shape that returns a tuple with each index having the number of corresponding elements 
Numpy.size() will give us how many elements are present in total
Syntax: nump.size(are, axis = none)
2)  In NumPy, describe the idea of broadcasting.
Ans) The term broadcasting refers to the ability of NumPy to treat arrays of different shapes during arithmetic operations. Arithmetic operations on arrays are usually done on corresponding elements. If two arrays are of exactly the same shape, then these operations are smoothly performed
Example:-import numpy as np 

a = np.array([1,2,3,4]) 
b = np.array([10,20,30,40]) 
c = a * b 
print c
3) What makes Python better than other libraries for numerical computation?
Ans) Top 5 Python Libraries And Packages For Numeric And Scientific Applications are
  1) SciPy (Scientific Numeric Library)
  2) Pandas (Data Analytics Library)
  3)  IPython (Command Shell)
  4) Numeric Python (Fundamental Numeric Package)
  5) Natural Language Toolkit (Library For Mathematical And Text Analysis)
4) How does NumPy deal with files?
Ans) NumPy introduces a simple file format for ndarray objects. This . npy file stores data, shape, dtype and other information required to reconstruct the ndarray in a disk file such that the array is correctly retrieved even if the file is on another machine with different architecture
5) Mention the importance of NumPy.empty() .
Ans) The empty() function is used to create a new array of given shape and type, without initializing entries
Syntax:-numpy.empty(shape,dtype=float,order='c')
