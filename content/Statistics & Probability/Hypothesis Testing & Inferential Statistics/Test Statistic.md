The term test statistic has two related meanings. In the first sense, a test statistic is a [[Function]] (more specifically a [[Random Variable]]) that considers a [[Sample Statistic]] of all possible [[Sample|Samples]] of size $n$ for a [[Population]]. Take for example the sample mean. First we fix a size $n$ and take all samples of size $n$. 

The second sense of the term is a particular output of the function $T$. Given a function $T$, which is a test statistic under definition 1, we can input $T(x_1) = \phi_1$ and $\phi_1$ is the test statistic under definition 2. Both senses of the term are used in statistics. It is the value found by converting a [[Sample Statistic]] such as a mean $\bar x$, sample proportion $\hat p$, or sample standard deviation $s$ into a score such as [[Z-Score]], or [[t-Score]]. This allows for a [[Hypothesis Test|Hypothesis Testing]] like through a [[Z-Test]] or [[t-Test]].

## Formal Definition
Function Definition
Consider a [[Population]] $\Theta$ of size $N$. A test statistic $T_{n_i}$ is an [[Injection]] $T_{n_i} : D \to S$ where 
$D = \{ d \, | \, d \text{ is a sample of size } n \}$ and $S = \{ s \, | \, s \text{ is a sample statistic} \}$.

Value Definition
Given a function $T_{n_i}$ and a population $\Theta$, a test statistic is defined as $T_{n_i}(\theta)$ where $\theta \in \Theta$. 