A $\sigma$-algebra for a set $\Omega$ is a non-empty set of [[Subset|Subsets]] of $\Omega$ [[Closure|Closed]] under countable union, countable intersection, and complement. In probability theory, the $\sigma$-algebra is called the event space.

## Formal Definition
Consider a non-empty set $\Omega$. A $\sigma$-algebra $F$ is a set of subsets of $\Omega$ satisfying the following criteria:
$$1. \quad |F| > 0$$
$$2. \quad \forall A \in F, \quad A^c \in F$$
$$3. \quad \forall \mathscr{A} \subseteq F, \quad \bigcap_{A \in \mathscr{A}} A \in F$$
$$4. \quad \forall \mathscr{A} \subseteq F, \quad \bigcup_{A \in \mathscr{A}} A \in F$$
In simpler terms, the first condition is that the $\sigma$-algebra F has a cardinality greater than one. This just means it is non-empty. The second condition is stating that the complement of any set in F is also in F. The third condition is that F is closed under [[Cardinality|countable]] intersections and the fourth countable unions.

For any given set $\Omega$, it's not guaranteed that there exists a unique $\sigma$-algebra. But for each [[Measure Space]] and [[Measurable Space]] there exists a unique $\sigma$-algebra. Instead of being derived from a definition, axiom, or defined set, $\sigma$-algebras are chosen based on how the experimenter decides to set up their experiment. In probability theory, for example, this can lead to results where various outcomes are possible and in the [[Sample Space]], but when these outcomes are [[Arguments]] for the probability function $P()$ the probability is undefined. 

## Examples in Probability
Let $\Omega = \{ 1, 2, 3, 4, 5, 6\}$ be a [[Sample Space]]. We can define a $\sigma$-algebra $F= \{ \Omega , \emptyset , \{ 1, 2, 3 \} , \{ 4, 5, 6 \} \}$. The [[Measurable Space]] $(\Omega , F)$ can be used to model a dice roll. All the outcomes of the dice roll are listed in the sample space, but the $\sigma$-algebra $F$, also called the event space in probability, does not count rolling an individual number as its own event. Rather the event space here is tracking whether a high number (4 or higher) or a low number (3 or lower) is rolled. Including the probability function $P()$ as the measure for the measurable space $(\Omega , F)$ we get the [[Measure Space]] $(\Omega, F, P)$. But since the event space does not include individual outcomes like $\{ 2 \}$ and $\{ 3 \}$, $P( \{ 2 \} )$ and $P( \{ 3 \})$ are undefined even though intuitively we would assign each the value $\frac{1}{6}$.

Typically for finite discrete sample spaces $\Omega$ the $\sigma$-algebra is chosen to be the [[Power Set]] $\mathscr{P}(\Omega)$.