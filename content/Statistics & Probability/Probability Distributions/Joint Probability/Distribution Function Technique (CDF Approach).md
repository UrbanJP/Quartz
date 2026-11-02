The distribution function technique, or the cumulative density function approach, is a technique for finding the [[Joint Cumulative Density Function]] of a [[Random Variable]] $W = g(X_1, X_2, \ldots, X_n)$.

1. First start with the definition of a [[Cumulative Density Function]] $F_W(w) = P(W \leq w)$ 
2. Translate $W \leq w$ into a region of $(X_1, X_2, \ldots, X_n)$ to get $\{g(X_1, X_2, \ldots, X_n) \leq w \}$
3. Construct the integral $$\iint \ldots \int_{\{g(X_1, X_2, \ldots, X_n) \leq w\}} \, f(x_1, x_2, \ldots, x_n) \, dx_1x_2\ldots x_n$$ where $f$ is the [[Joint Probability Density Function]] (Not $W$).
4. 