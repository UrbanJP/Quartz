Not to be confused with a [[Measure]] Function. A measurable function is a [[Function]] mapping the two sets from two [[Measurable Space|Measurable Spaces]] that maintains the structure of two spaces.

Consider a function $f: A \to B$. Take any subset $\beta$ of $B$ where $f$ can output each element (In other words any subset $\beta$ of $B$ in the [[Codomain]]). If the set of elements in the [[Domain]] that output the elements of $\beta$ (for all $\beta \subseteq B$) are in the [[Sigma Algebra]] of $A$ then $f: A \to B$ is a measurable function.

## Formal Definition
Let $(\Omega, F)$ and $(X, T)$ be measurable spaces. A measurable function $g: (\Omega, F) \to (X, T)$ is a function $g: \Omega \to X$ that satisfies the following condition; for any [[Set]] $B \in T$, the [[Inverse Image]] of $B$ under the function $g$ is in the [[Sigma Algebra]] $F$.

For any set $B$ in the [[Sigma Algebra]] $T$, $\{ \omega \in \Omega | g(\omega) \in B \}$ is in $F$.

## Example
Let $\Omega = \{ 1, 2, 3 \}, \, F = \mathscr{P}(\Omega), \, X = \{4,5,6\}$, and  $T = \mathscr{P}(T)$ where $\mathscr{P}()$ is the [[Power Set]]. We now have two measurable spaces $(\Omega, F)$ and $(X,T)$. We can now define a function $f$ as:
$$ f(x) = \begin{pmatrix} 1 \to 4 \\
2 \to 5 \\
3 \to 6 \end{pmatrix}$$
We can check the set $B_1 = \{ 4, 5 \} \in T$. The two numbers that output $4$, and $5$ when input into $f$ are $1$ and $2$, so since the set $\{1, 2 \}$ is in $F$, the inverse image of $B_1$ under the function $f$ is in $F$. Since this condition is satisfied for all sets in $T$ under the function $f$, the function $f$ is a measurable function.