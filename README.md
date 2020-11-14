# coursera
Programming Assignment 2: Lexical Scoping 


Hello, with this proyect we can create a path to read a test csv files repository with n samples and obtain the quintile of test scores. First the function creates a vector caching with the total scores and then the second function calculates que quintile score for all the files and skip the one by one calculate


fullscorevector <- function(x = numeric ()) {
  m <- NULL
  set <- function(y){
         x <<- y
         m <<- NULL
}
get <- function() x
setquintile <- function (directory, totalscore, id = 1:500) {
               subset <- list.files(path = "C:/Users/nicolas.reyes/Desktop/R/R/testfiles", full.names = TRUE)
               data <- data.frame()
               for(i in 1:500) {
               data <- rbind(data, read.csv(testfiles[i]))}
               sapply(data, quantile) m <<- quintile }
getquintile <- function()m
list(set = set, get = get, setquintile = setquintile, getquintle = getquintile)
}
