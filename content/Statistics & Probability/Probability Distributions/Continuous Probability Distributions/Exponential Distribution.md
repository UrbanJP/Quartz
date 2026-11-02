The exponential distribution $X \sim \text{Exp}(\lambda)$ is a [[Probability Distribution]] of the distance between points in a [[Poisson Point Process]]. It has the [[Memoryless Property]] for [[Random Variable|Random Variables]] where it is a specific example of the [[Gamma Distribution]].

$$\begin{matrix} \text{Probability Mass Function} && \text{Cumulative Distribution Function} \\
f(x) = \begin{cases} \lambda e^{-\lambda x} & x \geq 0 \\
0 & x<0 \end{cases}
&& 
F_X(x) = \begin{cases} 1-e^{-\lambda x} & x\geq 0 \\ 0 & x<0 \end{cases}
\end{matrix}$$
