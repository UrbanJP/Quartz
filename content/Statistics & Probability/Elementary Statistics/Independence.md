If two events $A$ and $B$ are independent this means that the [[Probability]] of $A$ occurring is unaffected by whether or not $B$ occurs and vice versa. If $B$ occurs the probability of $A$ remains the same, and if $B$ does not occur $P(A)$ is still the same. 

This can be further applied to [[Random Variable|Random Variables]].

## Formal Definition
Two [[Event|Events]] $A$ and $B$ are independent [[biconditional|iff]] $P(A|B) = P(A)$ and $P(B|A) = P(B)$. From this it follows that $P(A \cap B) = P(A)P(B)$.
$$\begin{align*} &P(A|B) = \frac{P(A \cap B)}{P(B)} & &\text{Definition of Conditional Probability} \\
&\frac{P(A \cap B)}{P(B)} = P(A) & &\text{From Definition of Independence} \\
&P(A \cap B) = P(A)P(B) & &\text{Multiply both sides by P(B)}
\end{align*}$$

We say that $n$ random variables are independent if
$$P(X_1 \leq x_1, X_2 \leq x2, \ldots, X_n \leq x_n) = \prod_{i=1}^n P(X_i \leq x_i) \qquad \forall x_i, \ldots, x_n \in \mathbb{R}$$
