# Second day at AI Fellowship
___

## Objective
1. Today we are meant to learn the numpy library of python.
2. This is my first day so i also have to evaluate the worth of the course.
____

## Notes:
______________________________________________

1. [array creation and manipulation](#array creation and manipulation)  
2. [Random number Generations](#Random number Generations)  
3. [Shaping of arrays](#Shaping of arrays)  
4. [Indexing and slicing](#Indexing and slicing)  
5. [Broadcasting](#Broadcasting)
_______________________________________________________
### 1. array creation and manipulation
* __np.array__ () is used to create an array
* for multidimentionsal array we pass an list of lists or __Matrix__ to the __np.array__ () function
* for creating a array in range we use funcion __np.arange(start,end ** excluded,stepsize)__
* for creating a n elements equally spaced we can use np.linspace() function
* for creating a matrix of all zeros with n elements use np.zeros()
* for creatinf an identity matrix use np.eye(dimension)   
    > dimension is the dimension for unit square matrix
    
### 2.  Random number Generations
* __np.random.rand(n)__ gives n random numbers from 0 to 1
* __np.array__ supports arithmetic with a number wich is interpreted as  operations on each element  individually
* __np.rand.randint(p,q)__  can be used to create a random integer between p and q
* __np.random.randint(begin,end,(row,column))__  creates an array of random 
* __np.random.seed(num)__ is used to seed the pseudo-random number generation.

### 3. Shaping of arrays
* __np.array__ class has reshape method that is used as __arr.reshape(i,j)__ to reshape the array to i*j matrix  
    > we cannot reshape a small array to an arry having more elements
* __np.array__  has min, max & mean methods to calculate these values
* __np.array__  also have __std__ method for standard deviation.


### 4. Indexing and slicing
* slicing of the array can be done with __\[begin:end(excluded):stepsize]__
* __arr\[::-1\]__ reverses the array
* slice creates an refrence to the original array so any mutation in slice is reflected on original array\.
* __arr\.copy()__ method can be used to create an independent copy of the array
* slicing of matrix can be done using __matrix/[rowstart:rowend:rowstep,colstart:colend:colstep\]__  
    > ends are excluded ie upto but not included
    

### 5. Broadcasting
* this is numpy feature that allows any arithmetic operation on array variable to be reflected on the elements of the array
* two matrix of same shape can be added together
* two matrix of compatible type can be multiplied together
* __mat.T__ can be used to transpose the matrix
* inverse matrix can be calculated by using __np.linalg.inv(matrix)__ function
* __np.linalg.det(matrix)__ is used to calculate the determinant of the matrix
* __np.linalg.norm( matrix)__ gives the magnetude of the array
* __np.linalg.dot(mat1,mat2)__ performs dot multiplicaton ie mat1.mat2
* __np.linalg.cross(mat1,mat2)__ performs dot multiplication

### Post-Scriptum

