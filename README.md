### Introduction

This second programming assignment will require you to write an R
function that is able to cache potentially time-consuming computations.
For this assignment, I created a couple of functions that allow the storage
of a matrix and it's inverse.

The first function, `makeCacheMatrix` creates a special "vector", which is
really a list containing a function to

1.  set the value of the vector
2.  get the value of the vector
3.  set the value of the inverse of a matrix
4.  get the value of the inverse of the matrix

The `cacheSolve` function calculates the inverse of the matrix 
if there is no cache for it.
