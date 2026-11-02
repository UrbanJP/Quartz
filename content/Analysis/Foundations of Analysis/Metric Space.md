Not to be confused with a [[Measure Space]] or a [[Measurable Space]]. Intuitively, a metric is a way to understand distance between points (elements) in a set $M$ using a distance [[Function]] $d$. Together $M$ and $d$ form a metric space.

## Formal Definition
a Metric Space is notated as an ordered pair $(M,d)$ where $M$ is a set and $d$ is a metric on $M$. The elements of $M$ are called points. The metric $d$ on $M$ is a [[Arity|bivariate function]] $d: M \times M \to \mathbb{R}$ that satisfies the four following axioms $\forall x,y \in M$:  
$$1. \quad d(x,x) = 0$$
$$ 2. \quad x \neq y \implies d(x,y) > 0$$
$$3. \quad d(x,y) = d(y,x)$$ $$4. \quad d(x,y) + d(y,z) \geq d(x,z)$$

For each axiom in colloquial terms, the first axiom says the distance between a point and itself is equal to zero. For the second, if two points are distinct they have a positive distance between them. For the third, measuring from $x$ to $y$ will give the same distance as measuring from $y$ to $x$. Lastly, the fourth one is the triangle inequality where the *hypotenuse* has a smaller distance than the two smaller sides added together.

Some examples of different distance functions in $\mathbb{R}^3$ [[Euclidean Space]] include the straight-line distance metric and the arclength distance metric.
