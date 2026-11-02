Variance $(\sigma^2)$ is a statistical measure that shows how spread out data is from the [[Arithmetic Mean]]. Lower values mean the data is close together while a higher variance means the data is more spread out. 

The formula for finding variance utilizes the [[Expected Value]].
$$ \text{Var}(X) = E[(X - \mu)^2]$$
After algebraic manipulation we get the following
$$\begin{align} \text{Var}(X) &= E[(X-E[X])^2] \\
&= E[X^2 - 2XE[X] + E[X]^2] \\
&= E[X^2] - 2E[X]E[X] + E[X]^2 \\
&= E[X^2] - 2E[X]^2 + E[X]^2 \\
&= E[X^2] - E[X]^2
\end{align}$$

## Algebraic Properties
