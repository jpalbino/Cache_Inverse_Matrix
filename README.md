Cache_Inverse_Matrix
====================

This "R" script do the following
1.The function "makeCacheMatrix" creates a special "matrix" object that can cache its inverse.
2.CacheSolve: This function computes the inverse of the special "matrix" returned by function makeCacheMatrix, depicted above. 
If the inverse has already been calculated (and the matrix has not changed), then the cachesolve must retrieves the inverse from the cache.

How it works:
First, download this script to your "R" working dyrectory.
After that, load the script in "R" using the command line: source("inverse_matrix.R").
Next, create a matrix, for example, using the command: original <- matrix(rnorm(36), nrow = 6).
Call the function "makeCacheMatrix" using the command line in "R": cache_matrix <- makeCacheMatrix(original).
To return the matrix, use the command line: cache_matrix$get(). This command will too display the matrix.
Now, use the command line cacheSolve(cache_matrix) to return and see the inverse matrix.
If you use the same above command a second time, the result matrix will be the same!

I worked hard to make this script. I hope it is well done. But, any contributions will be ok!
Enjoy it!


