# HW2
Please use D2L to turn in both the PDF output and your R Markdown file.

### Q1. (15 pts) 
Consider the binomial sampling distribution  In classical inference, once you observe data (x), you might write down the 95\% confidence interval for p as

![wald eqn](https://latex.codecogs.com/gif.latex?%5Chat%7Bp%7D%20&plus;/-%201.96%20%5Ctimes%20%5Cfrac%7B%5Chat%7Bp%7D%281-%5Chat%7Bp%7D%29%7D%7BN%7D)

where ![phat](https://latex.codecogs.com/gif.latex?%5Chat%7Bp%7D%20%3D%5Cfrac%7Bx%7D%7BN%7D). This follows from the asymptotic normality assumption of the estimator.

Generate a uniform spacing of p's from .01 to .99, with a step size of .01. Under each value of p, generate a Binomial random number with N=10. Now construct the confidence interval specified above. Since you know the actual value of p, you can confirm if this interval does in facr cover the *true* parameter.
Repeat this 10,000 times for each value of p, and keep track of the frequency of times each of the 10,000 repetitions cover the known parameter. Show a plot of the behavior of the "true" coverage probabilities for the full range of p's (The y-axis will have frequency on it and the x-axis will be over p).

Repeat the exercise with N = {30,50,100}. Conclude with your thoughts on the experiment. Are you surprised?


### Q2. (16 pts) 
For this question we will evaluate and visualize the impact of a prior on the posterior. For each part you should: graph the prior, sampling model, and posterior distributions on the same figure and discuss the implications of the prior on the posterior. When discussing the prior, provide some insight on the parameters in the beta distribution and describe how influential the prior is relative to the data.  For the sampling model, n is the total number of observations and y is the number of sucesses.

#### a. (4 pts)
- prior: beta(1,1)
- sampling model: binomial with n = 11, and y = 0

#### b. (4 pts)
- prior: beta(1,100)
- sampling model: binomial with n = 11, and y = 0

#### c. (4 pts)
- prior: beta(100,1)
- sampling model: binomial with n = 11, and y = 0

#### d. (4 pts)
- prior: beta(.001,.001)
- sampling model: binomial with n = 11, and y = 0
