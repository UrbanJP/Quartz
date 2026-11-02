Despite the name, a random variable is not random and is not a variable. Instead it is a [[Function]] with the [[Domain]] being the [[Sample Space]]. The sample space consists of all possible [[Event|Events]]. The [[Range|Range]], is a numeric value to represent each [[Event]].

The motivation for introducing random variables is to "mathematize" the process of doing probability and statistics. We can consider, for example, $P(X=1)$ and $P(X=0)$ in place of $P($"The switch is on"$)$ and $P($"The switch is off"$)$. "The switch is on" and "The switch is off" are [[Element|Elements]] of the sample space, the domain of $X()$. On the other hand, $1$ and $0$ are in the range of $X()$. 

Another consideration is that it straightforwardly allows for consideration of the [[Pushforward Measure]] which is the [[Probability Distribution]].

## Formal Definition
A random variable is a [[Measurable Function]] $X: \Omega \to E$ mapping from a [[Sample Space]] $\Omega$ in $(\Omega, F, P)$ to a [[Set]] $E$ in the measurable space $(E, \varepsilon )$. The notation is often written as $X : (\Omega, F, P) \to (E, \varepsilon)$.

Traditionally in statistics $E = \mathbb{R}$ or $E = \mathbb{N}$. Sometimes people will make the inaccurate statement that $E$ is the sample space. $E$ is instead called the [[State Space]], target space, observation space, or value space.

## Examples
1. Consider rolling a die. The sample space consists of actual events like "rolling a 1", "rolling a 2", etc. Note that "1" is not in the domain because "1" is not an event. "1" is not a thing that can happen, but we cannot do math with "rolling a 1". Because of this we represent "rolling a 1" as the number "1". We get the following mapping
$$X() \quad = \quad \begin{matrix} \text{Domain} & & \text{Range} \\
\text{Rolling a 1} & \to & 1 \\
\text{Rolling a 2} & \to & 2 \\
\text{Rolling a 3} & \to & 3 \\
\text{Rolling a 4} & \to & 4 \\
\text{Rolling a 5} & \to & 5 \\
\text{Rolling a 6} & \to & 6
\end{matrix}$$



2. Assume all [[Sigma Algebra|Sigma Algebras]] are [[Power Set|Power Sets]]. Let $\Omega = \{$"Rolling a one", "Rolling a two", $\ldots$, "Rolling a six"$\}$ and $E = \{ 1, 2, 3, 4, 5, 6 \}$. We define the random variable $X(\omega)$ to be $X : \Omega \to E$ where each roll number outputs its corresponding integer (e.g. "Rolling a three" $\to$ $3$).

3. We can also find certain probabilities with respect to $X(\omega)$ such as $P(X=5)$, $P(1<X<6)$, and $P(X \in \{1, 5, 6 \})$. Given that a random variable satisfies the [[Inverse Image]] conditions of a [[Measurable Function]], these probabilities are defined as such:
$$1. \quad P(X=5) := P( \{ \omega \in \Omega \,| \, X( \omega )=5 \}) $$
$$2. \quad P(1<X<6) := P( \{ \omega \in \Omega \,| \, 1< X(\omega )<6 \}) $$
$$3. \quad P(X \in \{1, 5, 6 \}) := P( \{ \omega \in \Omega \, | \, X( \omega ) \in \{1,5,6 \} \}) $$
