---
tags:
  - wsta1250
---

>[!abstract]
>This paper covers everything that is taught in WSTA1250 (Business Statistics). This course is an introductory statistics course. It covers the basics of statistical analysis including standard deviation, sampling, types of studies, variable categories, graphical displays and how to calculate them and types of statistical analyses.

### Criterion of a Sample

A sample, as opposed to a population, is an isolated subset of some broader data. Samples must necessarily share similar characteristics with the target population. In this case we are defining a characteristic to mean anything that is statistically relevant that could affect the outcome of the study. The sample should not be biased toward any specific characteristic, lest the data be skewed toward observations with that specific characteristic, with an observation being any atomic data point within a sample set. 

Furthermore, the sample size should be sufficiently large as to give accurate information about the target population. Generally, this would be $n \ge 25$, and in surveys the respondent rate should be at least $75\%$. When selecting a specific sample, to ensure that it's reflective of the target population, it should be random. A random sample  is where each member of the target population has an *equal chance* to be selected. A way to get a random sample may be to do an *in-person* sample. For instance, going to a cafe or the campus library. Alternatively, for an even more reliable approach, one might enumerate between every n$^\mathrm{th}$ student within the total population. In theory, to get a representative sample, one should aim for a random sample that shares similar characteristics to the target population, that is sufficiently large to give accurate information.

It should also be noted that one should always aim to select the biggest sample size possible. The larger the sample size, the better the estimates that one will receive. Of course this is a general rule and not universally true, but serves as a decent guideline when selecting sample sizes. 

### Observational and Experimental Studies

An observational study has no intervention by the investigator, nor is there any treatment imposed. An example would be something where you don't have the ability to change any factor during the study. On the other hand, an experimental study permits the investigator to have some control of the determinant. In this case a determinant is simply defined as "a single number calculated from a square matrix that measures generalized variance...".

### Types of Variables

A variable is a measurement that is taken from any study that is conducted, such as gender, age or income. Variables can be split up into two primary types, and then further split into secondary types. Overall, these include categorical and numerical types. Categorical data describes qualities and groups. Numerical data describes quantities and numbers. Within categorical data, there exists types categorical-ordinal, and categorical-nominal. Categorical-ordinal data describes values that have order to them. For instance, income brackets or age groups. Categorical-nominal data describes values that inversely do not have any order to them such as race or gender.  On the other hand, within numerical data, there exists numerical-discrete data which consists of distinct, countable whole values. There exists then numerical-continuous which takes any value within a given range, including decimals such as weight, age, and temperature. 

### Presenting Variables

A statistician needs to know how to present different types of variables, for instance a pair of categorical variables, and what is the best way to illustrate this link visually. A common way of doing this would be to use a cluster bar chart. A cluster bar chart is a type of bar chart that has multiple categorical variables - often two or more. The reason why it is called a cluster is because there is a cluster of bars within a single "column".  When presenting a pair of numerical variables, this is where one would be wise to use a scatter-plot. This is also a type of plot where one may investigate if there is a correlation between the X and Y axis. For instance, if the $y$ value increases as the $x$ axis increases then this would be known as a positive linear correlation. The angle of the correlation would indicate how "strong" or "weak" it is. However, if the $y$ value decreases as the $x$ axis increases, then this would be known as a negative linear correlation. It is also possible to have non-linear, in which case there would just be a bar that is parallel with the $x$ axis. Furthermore, any curve or parabola is strictly non-linear.

A histogram is a way of presenting data where there is only one numerical variable. In this case the numerical variable can be either discrete or continuous. Histograms can take on different shapes and modes. For instance, uniform, triangle, skewed left, and so forth. However, within this unit most histograms are of a normal shape. When looking at a histogram, on the horizontal axis (which is always labelled the $x$ axis), there exists the numerical variable, with the range of the numerical variable. On the vertical axis, which is the $y$ axis, is the frequency, which can also be called the count. On a histogram, the bar with the greatest height is where the "mode" is. The mode is just the most frequent observation (or the category that simply has the highest count).



Skewed histograms are just histograms that take on a similar format, but have a directional bias. It may be helpful to not look at the direction the histogram is facing but rather observe if the left-hand-side tail of the histogram is extending to the left all the way. In which case, it can be confidently labelled a left-skewed histogram. The inverse is true for a right-skewed histogram. The heuristic in this case is to observe the side of the tail that is being extended. There also exists uniform histograms, which can be easily identified by their rectangular shape. In histograms, the vertical axis will always have a numerical value, and the horizontal will always have the categorical.

In this unit specifically, the class test will have a multiple-choice question on box-plots. Students will need to comment on multiple things. The first is the centre. The centre of the box - also known as the median - will need to be commented on, specifically with which group has the highest and lowest median. The second observation is spreads. Students should comment on both the range and the inter-quotile range, but with a deliberate focus on the IQR. Students are also encouraged to mention any unusual observations. For instance any outliers, which are values that sit above or below the upper and lower fences. Students must observe which categories have outliers. If there are no outliers, this needs to be noted as well. This applies not only to regular box plots but also comparative box plots as well. 



### Summarizing one Numerical Variable

As you'll recall from earlier sections, a numerical variable can either be a discrete numerical variable or a categorical numerical variable. In any case, they can both be summarized with the following metrics, depending on the use case. The first method is known as the "measure of centre". The reason why one may want to measure the centre is because it allows one to know where the "central" tendency is. Such measures include the mean. The mean is defined as the average of all elements in the set. The symbol for a sample mean is $\bar{y}$. The second measure of central tendency is the median, which is the middle value of a set that is in ascending order. 

The second method to summarize a numerical variable is the measure of spread. This is used to calculate how spread out a sample is. This is helpful to know because one might think sample observations are very similar. For instance $[49, 50, 51]$, and $[0, 50, 100]$. Both of these samples have the same $\bar{y}$ value, however they are radically different observations. This is important; only knowing the "measure of  centre" will not give you the entire context. The measure of spread is equally informative and often times both methods should be used together.

Standard deviation is another measure of spread, represented by the letter $s$. This is how spread out the values are from the $\bar{y}$ value. A lower standard deviation means that data is less spread out and more consistent.  This is often why people will say that you get a better estimate with a smaller standard deviation because if there is less variability in the data then that means there is more certainty. 

The next method to measure the spread of data is the range. The range may be calculate by taking the maximum value in the set (including any outliers) and negating the minimum value in the set (also including outliers). This is a fairly simple way to measure spread.

A more sophisticated method is to get the inter-quotile range or IQR. A sample can be divided into quotiles. A quotile is simply representative of a section of a sample, the lower quotile or $Q1$ is the first $25\%$ of a sample, with each observation in ascending order. Given the same sequence, $Q2$ is the next $50\%$ which is the inter-quotile range, followed by $Q3$ which is the upper $25\%$ - also known as the "upper quotile". When excluding the upper and lower quotiles, and just using the IQR, this can given a more accurate reading of the data, because it doesn't account for outliers that may skew the data. To calculate the IQR, you simply negate the upper quotile by the lower quotile. 

Determining if an observation is an outlier, one must calculate the lower and upper fence values, $LF$ and $UF$, respectively. The lower fence is given by $LQ-1.5\times IQR$ and the upper fence is given by $UQ+1.5\times IQR$. If an outlier is above or below these values then it's classified as an outlier. Note that lower fence values *can* be negative.
