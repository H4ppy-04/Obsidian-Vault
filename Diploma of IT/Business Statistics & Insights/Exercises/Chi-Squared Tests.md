---
tags:
  - wsta1250
---
There are two types of Chi-Square tests.
1. ==Chi-Square goodness-of-fit test.== This is the one that will be taught.
2. Chi-Square test of independence

Formula:

$$
\chi^2=\sum_i\frac{(O_i-E_i)^2}{E_i}
$$

## Practice Problems

>[!problem]- Practice Problem 1
>
A university wants to determine whether students' preferred method of studying is **equally distributed** among four methods:
> - Textbooks
> - Online resources
> - Study groups
> - Video lectures
>
>A random sample of **120 students** is surveyed, producing the following results:
>
>
>
>| Study method     | Observed frequency |
>| ---------------- | -----------------: |
>| Textbooks        |                 36 |
>| Online resources |                 24 |
>| Study groups     |                 30 |
>| Video lectures   |                 30 |
>| **Total**        |            **120** |
>The university wants to test whether the four study methods are **equally preferred.**
>
>**At the 5% significance level, perform a chi-squared goodness-of-fit test.**
>
>**Your tasks**
>1. Identify the **categorical variable.**
>2. State $H_0$ and $H_1$.
>3. Calculate the **expected frequency** for each category.
>4. Calculate the chi-squared test statistic.
>5. Determine the degrees of freedom.
>6. Find the p-value.
>7. State your conclusion in context.

>[!problem]- Practice Problem 2
>A six-sided die is rolled **120 times**. If the die is fair, each face should appear equally often.
>The observed results are:
>
>|Face|1|2|3|4|5|6|
>|---|--:|--:|--:|--:|--:|--:|
>|Observed frequency|15|18|22|17|28|20|
>
>Using a **5% significance level**, determine whether there is sufficient evidence to conclude that the die is **not fair**.
>

>[!problem]- Practice Problem 3
>
>A university claims that students' preferred study methods are **equally distributed** among four methods:
>
>- Textbooks
>- Online resources
>- Group study
>- Video tutorials
>
>A researcher surveys **200 students** and gets:
>
>|Study method|Textbooks|Online|Group study|Videos|
>|---|---|---|---|---|
>|Observed|38|62|47|53|
>
At the **5% significance level**, test whether the data provide evidence that >students' preferences are **not equally distributed**.
>
>### Your task
>
>Work through:
>
>1. Categorical variable + its type
>2. H0​
>3. Ha​
>4. Expected frequencies
>5. Observed vs expected table
>6. χ2 statistic
>7. Degrees of freedom
>8. p-value
>9. Decision
>10. Conclusion in context


##### My attempt as p2:

The categorical variable is the face of the die. It is ordinal, but that doesn't matter. 
Since we assume that the die is fair, it each side should (in theory) have an equal probability of landing. So for any given roll the probability of any given face being landed on is $1/n$ where $n$ is the number of possible sides, in this case $6$.

Therefore the null hypothesis is that each side is equal so:
$H_0=p_1=p_2=p_3=p_4=p_5=p_6=\dfrac{1}{6}$
$H_a$ : Not all proportions are as stated in $H_0$.

Next, to calculate the expected frequency $E$ for each value, we multiply $n$ by the hypothesized probability $p$. So in this case, we are tolled that the dice is rolled $120$ times. $120\times 0.166=19.92$ which can be rounded to $20$. 

Next, we calculate the **observed vs expected** table.


| Face     | 1   | 2   | 3   | 4   | 5   | 6   |
| -------- | --- | --- | --- | --- | --- | --- |
| Observed | 15  | 18  | 22  | 17  | 28  | 20  |
| Expected | 20  | 20  | 20  | 20  | 20  | 20  |
We know that the expected value is accurate because the sum is equal to the number of times rolled.

Next, we subtract the expected frequencies from the observed frequency and then subsequently square the result.


| Face | $O$ | $E$ | $O-E$ | $(O-E)^2$ | $(O-E)^2/E$ |
| ---- | --- | --- | ----- | --------- | ----------- |
| 1    | 15  | 20  | -5    | 25        | 1.25        |
| 2    | 18  | 20  | -2    | 4         | 0.2         |
| 3    | 22  | 20  | 2     | 4         | 0.2         |
| 4    | 17  | 20  | -3    | 9         | 0.45        |
| 5    | 28  | 20  | 8     | 64        | 3.2         |
| 6    | 20  | 20  | 0     | 0         | 0           |

Next, we sum the value of $(O-E)^2/E$ which gives 5.3.
Given $df=k-1=5$, the $p$ value for this example is $0.38$. This is above the significance value of $\alpha=0.05$. Since $p=0.35\gt0.5$, there is insufficient evidence to conclude that the die is unfair. 

##### My attempt at p3

The categorical variable in this case is the study method. It's a categorical nominal variable. 

$H_0$: $p_\text{textbooks}=p_\text{online}=p_\text{group}=p_\text{videos}=0.25$
$H_a:$ Not all proportions are as stated in $H_0$.


| Study Method | $O$ | $E$ | $O-E$ | $(O-E)^2$ | $(O-E)^2/E$ |
| ------------ | --- | --- | ----- | --------- | ----------- |
| Textbooks    | 38  | 50  | -12   | 144       | 2.88        |
| Online       | 62  | 50  | 12    | 144       | 2.88        |
| Group study  | 47  | 50  | -3    | 9         | 0.18        |
| Videos       | 53  | 50  | 3     | 9         | 0.18        |

The sum of $(O-E)^2/E$ is equal to $6.12$

$6.12$ gives a p-value of $0.105$

$0.105$ is greater than the significance level of $0.05$. There is insufficient evidence that students study methods are unequal and therefore we fail to reject $H_0$.
