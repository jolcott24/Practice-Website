## Basic R Code
Hi Everyone! This is a short introduction to coding with R. 

### Getting Started

First we need to download R. You can do this at the following [Link](https://cran.uni-muenster.de/bin/windows/base/R-4.0.0-win.exe)

Next, we must learn some of the basics of R code. First, R can act as a calculator. For example:

```markdown
2 + 4
```

Try **running** this code, which you can do with ctrl + enter or by hitting the Green "Run Button" (see image below) ![Green Button](https://lh3.googleusercontent.com/proxy/1dONBYph1LF8aiE4xD98UMlYzWAfvVqKRQ_JJRf-9EscdKI-3R3HSI_8TIVVG3PWOzK0Rad1qIxsaTbSuI1K7BcEQwGkU2_WMr5S1vE7w7qVYCpn_RA)

This line of code should print the number 6 located in the "Script Results" section 

```
[1] 6
```

One of the most important concepts in programming is the idea of **variables.** Variables store information, and are super useful in reducing the amount of code you need to write. Lets look at an example of some math using variables. 

```r
a <- 10 
b <- 5
a + b
[1] 15
```

The `<-` stores the variable `a` as the number 10. So now, any time you use a in a command, R knows that `a` represents 10. 

If you wanted to change the value of `a`, simply write a new line of code giving a new value to `a`. R will use the most recent version of the variable for all the code you write with variables. For example: 

```r
a <- 2000
a + b 
[1] 2005
```

# For Loops
Perhaps one of the most important concepts of programming is the idea of **for loops.** In its most basic form, a for loop allows you to repeat a section of code for a specified number of times. For example, if I wanted to sum every integer between 1 and 10, I would write the following code: 

```r
sum <- 0
for (i in 1:10) {
  sum = sum + i
}
sum
[1] 65
```

R can be used to tackle difficult statistical problems and can be used to create amazing graphs. Often times, less code is better. As Dr. Suess once said:
> Sometimes the questions are complicated and the answers are simple.

