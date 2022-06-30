# Creating-Histogram-of-Integers
This shows how to create histogram  of 1000 numbers from a Poisson distribution 
### Histogram of Integers ###
values<-rpois(n = 1000, lambda = 1.70)
hist(values, main = "Histogram", xlab = "Random numbers from a Poisson with mean 1.7",
     col = terrain.colors(6))

hist(values, breaks = (-0.5:8.5), main = "Histogram from Poisson", xlab = "Random numbers from a Poisson with mean 1.7",
     col = terrain.colors(6))
