The expected value $E[X]$ (sometimes $\mu_x$), also called the expectation, is the value we would expect a [[Random Variable]] to output if we completed a [[Trials and Experiments|Trial]].

## Formal Definition
### Discrete Case
The expected value is the [[Weighted Average]] of a [[Tuple]] of data points $(x_1, x_2, \ldots , x_n)$ and their respective weights which are the probabilities $(p_1, p_2, \ldots , p_n)$. This comes out to be
$$E[X] = \sum_{i=1}^{n}p_i x_i$$

### Continuous Case
In the continuous case, the expected value becomes
$$E[X] = \int_{- \infty}^{\infty}xf(x) dx$$
where $f(x)$ is the [[Probability Density Function]] of the [[Random Variable]] $X$.