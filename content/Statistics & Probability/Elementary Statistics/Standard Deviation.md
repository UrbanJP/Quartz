Standard deviation $(\sigma)$ is a statistical measure that shows how spread out data is from the [[Arithmetic Mean]]. A lower value means the data is close together while a higher value means further apart. Standard deviation is the [[Square Root]] of [[Variance]].


## Formal Definition
### Discrete Case
Say we have a countable data set $x_1, x_2, \ldots , x_n$ that the random variable $X$ can take on where each $x_i$ has probability $p_i$. Then the mean $\mu$, also known as the [[Expected Value]], would be 
$$\mu = E[X] = p_1x_1 + p_2x_2 + \ldots + p_nx_n = \sum_{i=1}^n p_i x_i$$
and the standard deviation would be
$$\sigma = \sqrt{\sum_{i=1}^n p_i(x_i - \mu)^2}$$
### Continuous Case
In the continuous case we have
$$\mu = \int_X p(x)x dx$$
and standard deviation
$$\sigma = \sqrt{\int_X p(x)(x-\mu)^2 dx}$$
where $p(x)$ is the [[Probability Density Function]].