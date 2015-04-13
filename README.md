# LinksAndReferences
Collection of useful materials

Video for the R course
http://blog.revolutionanalytics.com/2012/12/coursera-videos.html

How to read an XML file (can't read a file on an HTTPS location - just remove the s)
R > library(XML)
R > url <- "http://www.statistics.life.ku.dk/primer/mydata.xml" # insert the data location
R > indata <- xmlToDataFrame(url)
R > head(indata) #display the data
