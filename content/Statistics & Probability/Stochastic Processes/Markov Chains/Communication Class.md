The communication class of a state $k$ in a [[Markov Chain]] is the [[Set]] of all states that communicate with $k$. States $k$ and $j$ communicate if we can get from one directly to the other and vice versa.

## Formal Definition
If one state leads to another we denote it as $k \to j$. We say that $k$ communicates with $j$ [[Biconditional| if and only if]] $k \to j$ and $j \to k$. This is denoted as $k \leftrightarrow j$.

The communication class denoted as $\mathbb{C}_k$ of state $k$ is defined as the following.
$$ \mathbb{C}_k = \{ j \in \mathbb{S} \, | \, k \longleftrightarrow j \}$$
