ProgrammingAssignment2
======================

Procedure for testing this:
  
   source("cachematrix.R")
   a <- makeCacheMatrix(matrix(5:8,2,2))
   cacheSolve(a)
   
 The above steps will caluclate the inverse, as we are executing firsttime.
 
 If you  execute the below command again, It will not calculate inverse again, It will take the result from cache
 
 cacheSolve(a)
