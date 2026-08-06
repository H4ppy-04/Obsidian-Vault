---
tags:
  - wsta1250
---
A $z$-test is for when we know the population standard deviation $\sigma$ is known and want to figure out $\mu$. 

Assumptions: 
 - Sample mean is drawn from a Normal distribution
 - Hypothesized population mean
 - Sample mean is known

The test statistic is $$z=\frac{\bar{x}-\mu_0}{\sigma/\sqrt{n}}$$

The denominator here is the $SE$ (standard error) of the first value $\bar{x}$.

[This calculator](https://www.statology.org/z-score-to-p-value-calculator/) can be used to derive the $p$ value from a $z$-test.

For excel (from [statology](https://www.statology.org/how-to-find-a-p-value-from-a-z-score-in-excel/))

#### Two-tailed Test
**=1 - NORM.DIST(Z, $\bar{y}$, $\sigma$, TRUE)**

#### One-tailed Test
**=NORM.DIST(Z, $\bar{y}$, $\sigma$, TRUE)**