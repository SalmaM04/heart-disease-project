2+2

6-2

2*2

#Creating Variables

number <- 4

number <- 10

number2 <- 10


#Math with variables

mul <- number + number2

#Vector

c(1, 2, 3, 4, 5)

#Sequence
1:10


# Seq 

seq(1,9,2)

#rep 

rep(1, 10)

#load data

data("mtcars")

#View data

View(mtcars)

mtcars[1,1] #row, column
firstRow <- mtcars[1,] #whole row 1
mtcars[,1] #whole col 1

#Dimensions

n <- nrow(mtcars)
n1 <- ncol(mtcars)

#Summarize the whole data

summary(mtcars)


summary(mtcars$mpg) #important

#coercing a numeric variable as a factor
mtcars$am_new <- factor(mtcars$am)

mtcars$am_new <- factor(mtcars$am, labels = c("automatic", "manual"))

mean_mpg <- mean(mtcars$mpg)

plot(mtcars$mpg)

hist(mtcars$mpg)

hist(mtcars$mpg, 
     main = "Distributions of MPG in our data",
     breaks = 8, #to change a specific number of bars
     xlab = "MPG",
     ylab = "Counts",
     col = "purple")

