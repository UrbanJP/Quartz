The Cumulative Density Function (CDF) of a [[Random Variable]] $X$ evaluated at $x$ is the [[Probability]] that $X$ takes on a value less than or equal to $x$. For multiple random variables $X$, $Y$, and $Z$ the cumulative density function evaluated at their respective points would be $$F_{XYZ}(x,y,z) = P[X \leq x, \ Y \leq y, \ Z \leq z]$$
## Formal Definition
A Cumulative Density Function for $\mathbb{X}$ is a [[Function]] $F: \mathbb{R}^p \to [ 0,1 ]$ given by $$ F_{X_1 X_2 \ldots X_n}(x_1, \ldots , x_p) = P[X_1 \leq x_1, \ X_2 \leq x_2, \ \ldots , \ X_p \leq x_p ]$$
Sometimes $F_{X_1 X_2 \ldots X_n}$ is shortened to simply $F$. Since values of $F$ represent the [[Probability]] of an [[Event]] these values must each be in between 0 and 1 inclusive due to [[Kolmogrov Axioms]].

For a single [[Random Variable]] $X$ the [[Distribution Function]] is $F(x) = P[X \leq x]$.


# Finding CDF
### Finding CDF from the PDF
If we have the [[Probability Density Function]] $f(x)$ then we can derive the cumulative density function $F(x)$, the probability of $X$ being less than or equal to $x$, by the following integral.
$$F_X(x) = P(X \leq x) = \int_{- \infty}^{x}f(t) dt$$
Here $t$ is used as the integrating variable for mathematical soundness since $x$ cannot both the bound and the integrating variable, but $f(t)$ is treated the same as $f(x)$.

### Finding CDF from CDF
CDF approach for finding CDF of a variable $W = h(X)$.
