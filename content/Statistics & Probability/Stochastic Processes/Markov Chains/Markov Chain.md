A Markov chain is a random process that has the [[Markov Property]]. Estimating state $n+1$ only depends on state $n$.

$$P(X_{n+1} = k | X_n =j, Past) = P(X_{n+1} = k | X_n =j) = P(X_1 = k | X_0 = j) = P_{jk}$$ 
$$P = \begin{bmatrix}  &  & \\ & P_jk & \\ & \end{bmatrix}$$


## Examples
The probability from going to space $a$ to $b$ is $p$. The probability of going from space $b$ to $a$ is $q$. Then we have that
$$P = \begin{matrix} a \\ b \end{matrix} \begin{bmatrix} 1-p & p \\ q & 1-q \end{bmatrix}$$
