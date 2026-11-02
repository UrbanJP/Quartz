A transition matrix measures all the possible transitions of a [[Markov Chain]]. It is a [[Square Matrix]] where each row represents a possible state for the system. The transition matrix $P$ tells us the probabilities of each state at time $t+1$ if the current time is $t$. The $p_{ij}$ element of $P$ represents the probability of going to state $j$ at time $t+1$ if we are at state $i$ at time $t$. We can also write this as $p_{i \to j}$ which is a less common but intuitive notation.

This can be extrapolated to time $t+n$ for an $n$-step matrix $P^{(n)}$.  The $n$-step matrix is equal to $P^n$ which is the transition matrix $P$ multiplied by itself $n$ times under [[Matrix Multiplication]].

## Formal Definition
Given a Markov chain with $m$ states, its decision matrix is an $m \times m$ [[Matrix]] where the $p_{ij}$ element is $P(Y_{t+1} = j | Y_t = i)$, the probability of being in state $j$ at time $t+1$ given we are in the state $i$ at $t$. Both $Y_t$ and $Y_{t+1}$ are [[Random Variable|Random Variables]] in the Markov chain.

## Examples
Consider a Markov chain with three states, $A$, $B$, and $C$. Since there are $3$ states, we can define a $3 \times 3$ decision matrix as follows
$$P = \begin{matrix} A \\ B \\ C \end{matrix}
\begin{bmatrix} 0.5 & 0.4 & 0.1 \\
0.3 & 0.4 & 0.3 \\
0.2 & 0.1 & 0.7 \end{bmatrix}$$
For element $p_{jk}$ this represents the probability of going from state $i$ at time $t$ to state $j$ at time $t+1$