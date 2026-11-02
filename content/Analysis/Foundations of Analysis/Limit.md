The limit "$\lim_{x \to a} f(x)$" is read as "the limit of the function $f(x)$ as $x$ approaches $a$". Limits are beneficial to answer the following question: as the function $f(x)$ approaches $a$ on the $x$-axis what value does it approach on the $y$-axis?

## Formal Definition
The limit $\lim_{x \to a} f(x)$ is said to exist and equal $L$ if and only if
$$ (\forall \varepsilon > 0) (\exists \delta > 0) \quad \text{such that} \quad (\forall x \in \mathbb{R})(0< |x-a|< \delta) \implies |f(x)-L| < \varepsilon$$
In other words, for all $\varepsilon$ greater than $0$, there is some number $\delta$ such that for every number $x$, if the distance between $x$ and $a$ is less than $\delta$ then the distance between $f(x)$ and $L$ is less than $\varepsilon$.


Here is a thorough breakdown of this definition.

Let's consider both the beginning and end of the definition. For every single number $\varepsilon > 0$, the distance between $f(x)$ and $L$ is less than $\varepsilon$. Regardless of how small $\varepsilon$ is; it could be equal to $2, 0.0043, 0.000000001$, or any other number, the distance between $f(x)$ and $L$ is less than $\varepsilon$.

But there is a condition that must be satisfied first. The distance between $x$ and $a$ must first exist (be greater than zero) and also be less than some number $\delta$.