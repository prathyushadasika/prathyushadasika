# prathyushadasika
This function creates a special "matrix" object that can cache its transpose.
makeCacheMatrix <- function(x = matrix()) {
  transpose <- NULL
  set <- function(y) {
    x <<- y
    t(x) <<- NULL
  }
  get <- function() x
  settranspose <- function(transpose) t(x) <<- transposematrix has not changed), then it should retrieve the inverse from the cache.
  getInverse <- function() inv
  list(set = set,
       get = get,
       settranspose = settranspose,
       gettranspose = gettranspose)
}
matrix has not changed, then it should retrieve the transpose from the cache.
source("ProgrammingAssignment2/cachematrix.R")
my_matrix <- makeCacheMatrix(matrix(1:4, 2, 2))
my_matrix$get()
my_matrix$get()
[,1] [,2]
[1,] 1 3
[2,] 2 4
my_matrix$gettranspose()
NULL
