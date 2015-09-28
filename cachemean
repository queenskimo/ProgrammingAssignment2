cachemean <- function(x, y) {
        m <- x$getmean()
        if(!is.null(m)) {
                message("getting cached data")
                return(m)
        }
        data <- x$get()
        m <- mean(data, y)
        x$setmean(m)
        m
}
