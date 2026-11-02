The Marginal Cumulative Density Function, or Marginal Cumulative Distribution Function (Marginal CDF) is the [[Cumulative Density Function]] of at least one but not all of the [[Random Variable|Random Variables]] in a [[Joint Cumulative Density Function]].

For example, let's say we have the cumulative density function $F_{XYZ}(x,y,z)$. Potential marginal density functions we could find would be $F_X(x)$ and $F_{XZ}(x,z)$. In the first example this would be to focus only on $X$ and ignore $Y$ and $Z$ while in the second case we focus on both $X$ and $Z$ while ignoring $Y$.

## Formal Definition
Given a Cumulative Density Function $F_{X_1 X_2 \ldots X_n}(x_1, x_2, \ldots , x_n)$ the marginal cumulative density function $F_{X_{a_1} X_{a_2} \ldots X_{a_m}}(x_{a_1}, x_{a_2}, \ldots , x_{a_m})$, for some $m < n$ where each $X_{a_i} \in \{X_1, X_2, \ldots , X_n \}$, is equal to $$F_{X_{a_1} X_{a_2} \ldots X_{a_m}, \ X_{b_1}, X_{b_2}, \ldots , X_{b_{n-m}}}(x_{a_1}, x_{a_2}, \ldots , x_{a_m}, \infty, \infty, \ldots , \infty)$$
where each $X_{b_i}$ is also in $\{X_1, X_2, \ldots , X_n \}$. This equates to the probability
$$P(X_{a_1} \leq x_{a_1}, \ X_{a_2} \leq x_{a_2}, , \ \ldots \ X_{a_n} \leq x_{a_n}, \quad X_{b_1} \leq \infty , \ X_{b_2} \leq \infty , \ \ldots \ , X_{b_{n-m}} \leq \infty)$$
The role of the $X_b$'s is to represent all the random variables in the original CDF that are not in the marginal cumulative density function. All of these values are less than or equal to infinity.