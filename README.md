# assignment_R11849020

library(readr)
getwd()
dengue <- read_csv("dengue_assignment.csv")
View(dengue)

test2014 <- dengue[dengue$year == 2014, ]
sum(test2014$case_number, na.rm = TRUE)

#answer: 15747