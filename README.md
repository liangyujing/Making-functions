```
##自己定义函数   Making your own functions

john <- function(x) {(8/(1+x^2))*exp(-2*x)}
peter <- function(x) {0.5+log(x/(1+x))}
nicholas <- function(x) {1+sin(3*x)}
john(2)  #当x为2时，john多大

myx <- c(1.2,1.7,2.2,2.5,2.9)
john(myx)

y<- john(myx)
plot(myx,y)
```
