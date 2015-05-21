# LinksAndReferences
Collection of useful materials

These guys are providing an overview of the relevancy of some courses in Data Science http://www.quora.com/Is-it-worth-it-to-pay-9-*-49-for-a-data-science-specialization-on-Coursera

Video for the R course
http://blog.revolutionanalytics.com/2012/12/coursera-videos.html

How to read an XML file (can't read a file on an HTTPS location - just remove the s)
R > library(XML)
R > url <- "http://www.statistics.life.ku.dk/primer/mydata.xml" # insert the data location
R > indata <- xmlToDataFrame(url)
R > head(indata) #display the data
R >

My functions: 
hhead(x, n=6)
x – A matrix, data frame, or vector.
n – The first n rows (or values if x is a vector) will be returned. If left empty all is returned

write.csv(MyData, file = "MyData.csv") ## this kinds of exports your matrix into a csv in the directory

* http://cran.rstudio.com/web/packages/dplyr/vignettes/introduction.html 
