# coursera
Programming Assignment 2: Lexical Scoping 
Assignment: Caching the Inverse of a Matrix

Hello, with this code we can:
1. Get a matrix
2. set the inverted matrix o matrix1 (any matrix)
3. Get the inverser matrix of any cachet matrix


makeCacheMatrix <- function(x = matrix()) {
  matrix1 <- NULL
  set <- function(y){
    x <<- y
    Inverse_matrix <<- NULL
  }
  get <- function() x
  set_inverse <- function(solveMatrix) {
  getInverse <- function() Inverted_matrix 
  list(set = set, get = get, set_inverse = set_inverse, getInverse = getInverse)
}

Assignment: Ge the inverse matrix
Then with this coded we can:
1. If there are a inverse matrix get it
1. If there is not a inverted get the inverse matrix of a cached matrix

cacheSolve <- function(x, ...) {
  MyInverse <- x$getInverse()
    if(!is.null(matrix1)){
     return(myInverse)
  }
  data <- x$get()
  inverted_matx <- x$getInverse(myInv)
 }

