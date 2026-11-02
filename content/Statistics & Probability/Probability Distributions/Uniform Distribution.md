The uniform distribution $X \sim \text{U}(a,b)$ , sometimes called a rectangular distribution, is a probability distribution where each outcome is equally likely. This description gives an intuition for the idea of a uniform distribution, but is not fully accurate. It only works for the discrete case, but not the [[Continuous]] case since for any [[Probability Density Function]] $P(X=x)=0$. Below is a formal definition.

## Formal Definition
#### Discrete Case
Consider a [[Random Variable]] $X$ such that the [[Support]] is $\{a_1,a_2, \ldots, a_n\}$. Then $X$ follows a uniform distribution just in case
$$f_X(x) = \begin{cases} \frac{1}{n} & x \in \{a_1,a_2, \ldots, a_n\} \\
\\0 & \text{otherwise}
\end{cases}$$
is the [[Probability Mass Function]].
#### Continuous Case
Consider a [[Random Variable]] $Y$ such that the support is $[a,b]$. Then $Y$ follows a uniform distribution just in case
$$\int_c^d f_Y(y)dy = d-c \quad \forall d,c \in [a,b] \text{ where } d>c$$

## Properties
Consider the random variable $X \sim \text{U}(a,b)$. Then the following holds true.
[[Expected Value]]
- $E[X] = \mu_X = \frac{a+b}{2}$  
[[Variance]]
- ...