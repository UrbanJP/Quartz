A Z-Test is a statistical test where the [[Probability Distribution]] of the [[Test Statistic]] under the [[Null Hypothesis]] can be approximated by a [[Normal Distribution]]. The Z-test is possible because of the [[Central Limit Theorem]]. 

The role of the Z-test is to test whether the difference between a population mean and sample mean, or the difference between two sample means, is [[Significance Level|Statistically Significant]]. This is done by finding the [[Z-Score]] and ultimately conducting the Z-Test. It can also be used to test two sample proportions. 

## Assumptions
To calculate a Z-score, the assumptions are 
1. [[Standard Deviation]] $\sigma$ is known.
2. Population normally distributed or $n>30$ if population distribution unknown or not normal.
3. Observations are [[Independent and Identically Distributed (IID)]] with mean $\mu$ and variance $\sigma^2$.
4. The [[Sample]] distribution is approximately [[Normal Distribution|Normal]] (Always given by [[Central Limit Theorem]]).

## The Z-Test Process
Three processes will be explained. First the Z-test for comparing a population mean and sample mean, second for comparing two sample means, and third for comparing a sample proportion to a hypothesized population proportion.

*Population Mean*
Given a population of size $N$ we hypothesize that the mean of the population is $\mu_0$. Our [[Null Hypothesis]] is $H_0: \mu = \mu_0$ . The [[Alternative Hypothesis]] is $H_1: \mu \neq \mu_0$ for two-tailed test or $H_1: \mu < \mu_0$ or $H_1: \mu > \mu_0$ for a one-tailed test. So far we do not know the actual mean and $\mu_0$ is just a guess. 
Next, we take a sample of size $n<N$. According to assumption $2$, we must either have a normally distributed population or have $n>30$. Once this condition is met, we find the [[Mean]] of the sample and denote this as $\bar x$. Here, $\bar x$ is our best approximation of the population mean. To [[Standardizing|Standardize]] our values, we use the [[Z-Score]] formula for comparing a sample mean and population mean $Z = \frac{\bar x - \mu_0}{\sigma/\sqrt{n}}$. Then using a [[Z-Table]] we complete the test.

