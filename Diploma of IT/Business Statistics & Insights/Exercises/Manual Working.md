---
tags:
  - wsta1250
---
## Cafe Exercise
Research goal: Establish if the wait time for a cafe is longer than 5 minutes. Suspected wait time is longer. Let $H_0$ be $\mu = 5$ and let $H_1$ be $\mu \gt 5$ 

| Wait times |
| ---------- |
| 6.1        |
| 5.4        |
| 4.8        |
| 6.7        |
| 5.9        |
| 7          |
| 6.3        |
| 5.6        |
| 6.8        |
| 5.2        |
| 6.5        |
| 6          |
| 5.7        |
| 6.4        |
| 5.8        |
| 6.6        |
$\bar{x} = 6.05$
$\alpha = 0.05$
$\mu = 5$
$s = 0.616$

$t=6.818$



























Let the sample mean $\bar{x}$ be the aggregated sum of each observation $x$ over the sample size $n=16$ such that $$\bar{x} = \frac{6.1+5.4+4.8+\ldots\ldots+6.6}{16}$$

Given the known value of $\bar{x}$ being $6.05$ let the sample standard deviation $s$ be equal to the square root of the squared difference between each sample to them sample mean $\bar{x}$ over the sample size $s - 1$ such that $$s=\sqrt{\frac{\sum(x_i-\bar{x})^2}{n-1}}$$ which gives a very small sample standard deviation value of $s=0.61$, showing that these observations are very close to the average.

To compare the means of both groups, a t-test can be applied with the standard significance level of $\alpha=0.05$. So if $t \lt a$ then reject $H_0$. The standard error of the mean $SE$, accounting for the sample spread and group size is $SE=\dfrac{s}{\sqrt{n}}$. The $t$ test can then be substituted as follows $$t=\frac{\bar{x}-\mu}{SE}$$
Where:
$\bar{x}$ = $6.05$
$\mu=5$

In this $t$ test, $\bar{x}-\mu$ measures the difference between the sample average $\bar{x}$ and the expected population average $\mu$. The $t$ score comes out to $6.81$. The $p$ value 

If $SE$ is equal to $0.15$ then $t=\dfrac{6.05-5}{0.15}$ and $1.05\div 0.15$ comes out to $6.81$. 

## Bakery Exercise
### Problem 

A bakery <i>claims</i> its average bread delivery time is **12 minutes**. You suspect it may be longer. Your job is to determine if this is the case or not.

### Working

| Observations (in <u>minutes</u>) |
| -------------------------------- |
| 13.2                             |
| 11.8                             |
| 12.7                             |
| 13.5                             |
| 12.9                             |
| 14.1                             |
| 13.0                             |
| 12.4                             |
| 13.6                             |
| 11.9                             |
| 13.3                             |
| 12.8                             |
| 13.1                             |
| 12.6                             |
| 13.4                             |
Immediately we that $n=15$ and $df=14$ . Further, we can define both null and alternate hypotheses $H_0: \mu=12$ $H_1: \mu\gt 12$. 

The sample mean $$\bar{x}=\dfrac{\sum\limits^n_{i=1}x_i}{n}$$ so $\bar{x} = 12.95$ 

The sample standard deviation $s$ $$s=\sqrt{\frac{\sum(x_i-\bar{x})^2}{n-1}}$$
so $s$ = 0.62

A one-sample t-test with $\alpha=0.05$
1. The standard error value $SE$ is $\dfrac{s}{\sqrt{n}}$ which gives 0.16.
2. The $t$ value is $(12.95 - 12)\div 0.16$ which gives $t=5.93$
3. Therefore 


## Town Nutritionist Exercise

This is from a [video](https://www.youtube.com/watch?v=8Aw45HN5lnA) but I am going to paste the question here.

1. The average weight of all residents from town Greenville is 168 lbs. A nutritionist believes the true mean to be different. She measured the weight of 36 individuals and found the mean to be 169.5 lbs with a standard deviation of 3.9.
	1. State the null and alternative hypotheses.
	2. At a 95\% confidence level, is there enough evidence to discard the null hypothesis? (Use the p-value method)

$H_0: \mu = 168$ and $H_a:\mu \neq 168$. 
$\alpha = c - 1 = 0.05$

The confidence level is going to be $\alpha=5\%$ which is given by the confidence level $c$ with $\alpha=c-1$ and $n=36$ with the sample mean $\bar{x}=169.5$ and $s=3.9$.  

In this case this is a two-tailed z-test since we already have the standard distribution.

## Coffee Shop Wait Time

A coffee shop claims that the **average customer wait time is 5 minutes**. You suspect the wait time is **longer than 5 minutes**.

| Customer | Wait time (minutes) |
| -------- | ------------------: |
| 1        |                 6.2 |
| 2        |                 5.8 |
| 3        |                 7.1 |
| 4        |                 5.5 |
| 5        |                 6.7 |
| 6        |                 4.9 |
| 7        |                 6.4 |
| 8        |                 5.9 |
| 9        |                 7.3 |
| 10       |                 6.0 |

Let $\mu_0=5$ with hypotheses $H_0:\mu=5$ and $H_a:\mu\gt 5$. The significance level $\alpha$ will remain at a standard $0.05$. 


| Derived Values |      |
| -------------- | ---- |
| $n$            | 10   |
| $\bar{x}$      | 6.18 |
| $s$            | 0.72 |
| $SE$           | 0.07 |


## Student Scenario

| Student | Study time (hours) |
| ------- | -----------------: |
| 1       |                2.5 |
| 2       |                3.1 |
| 3       |                2.8 |
| 4       |                2.4 |
| 5       |                3.0 |
| 6       |                2.7 |
| 7       |                2.9 |
| 8       |                3.2 |
| 9       |                2.6 |
| 10      |                2.3 |
| 11      |                3.1 |
| 12      |                2.8 |