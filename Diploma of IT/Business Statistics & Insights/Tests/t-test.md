---
tags:
  - wsta1250
---
### Definition
A $t$-test is a tool for evaluating the [[Key Terms|means]] of one or two populations using hypothesis testing when $\sigma$ is unknown and so is estimated using the sample standard deviation.

The types of $t$-tests include:
1. A one-sample $t$-test is used to determine whether a population mean differs from a hypothesized value.
2. An independent 2-sample $t$-test is used to determine whether two groups differ from *each other*.
3. A paired or dependent samples $t$-test is used to determine whether the mean difference between paired measurements is statistically significant.
### Criteria
1. The distribution must be approximately normal.
2. The sample data must be independent.[^1]
3. The measurements are [[1.2 Categorizing and Presenting Variables|continuous]].
4. The observations are a [[Key Terms|simple random sample]].

A one-sample $t$-test can be calculated as:$$t=\frac{\bar{x}-\mu}{\frac{s}{\sqrt{n}}}$$
A two-sample $t$-test can be calculated as:$$t=\frac{\left(\bar{x}_1-\bar{x}_2\right)-\left(\mu_1-\mu_2\right)}{SE}$$
And the standard error formula for a two-sample $t$-test[^2] as: $$SE=\sqrt{s^2_p\left(\frac{1}{n_1}+\frac{1}{n_2}\right)}$$ where: $$s^2_p=\frac{(n_1-1)s^2_1+(n_2-1)s^2_2}{n_1+n_2-2}$$
For the two-sample $t$ test $df$ is calculated as $n_1+n_2-2$.

For two-sample $t$-tests that *don't* assume equal variance, [Welch's two-sample t-test](https://en.wikipedia.org/wiki/Welch%27s_t-test) can be used:$$t=\frac{\bar{x}_1-\bar{x}_2}{\sqrt{\frac{s^2_1}{n_1}+\frac{s^2_2}{n_2}}}$$
The $df$ for Welch's t-test is calculated using the [Welch–Satterthwaite equation](https://en.wikipedia.org/wiki/Welch%E2%80%93Satterthwaite_equation): $$df=\frac{\left(\frac{s^2_1}{n_1}+\frac{s^2_2}{n_2}\right)^2}{\frac{(\frac{s^2_1}{n_1})^2}{n_1-1}+\frac{(\frac{s^2_2}{n_2})^2}{n_2-1}}$$
For a paired $t$-test the $df$ is just $n-1$ and the formula is: $$t=\frac{\bar{d}-\mu_d}{\frac{s_d}{\sqrt{n}}}$$
where:
- $\bar{d}$ - mean of the differences between pairs
- $\mu_d$ - hypothesized mean difference[^3]
- $s_d$ - standard deviation of the differences
- $n$ - number of pairs
- $\frac{s_d}{\sqrt{n}}$ - standard error of the mean difference


An [online tool](https://www.statology.org/t-score-p-value-calculator/) can be used to calculate the [[Key Terms|p-value]].


[^1]: It should be noted that this is true for one-sample and independent two-sample $t$-tests, but *not* for paired $t$-tests. A paired $t$-test specifically requires the observation to be **dependent within pairs**.

[^2]: The standard error formula here assumes equal variances.

[^3]: The value of $\mu_d$ in a paired $t$-test is usually 0. As such, the numerator is usually simplified to $\bar{d}$.

