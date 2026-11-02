The Peano Axioms are the building blocks to defining equality and counting on the [[Set]] of [[Natural Numbers]].

$$1. \quad 0 \in \mathbb{N}$$
$$2. \quad \forall x \in \mathbb{N}, \quad  x=x$$
$$3. \quad \forall x,y \in \mathbb{N}, \quad x=y \implies y=x$$
$$4. \quad \forall x,y,z \in \mathbb{N}, \quad (x=y \wedge y=z) \implies x=z$$
$$5. \quad \forall a,b \quad (b \in \mathbb{N} \wedge a=b) \implies a \in \mathbb{N}$$
$$6. \quad \forall n \in \mathbb{N}, \quad S(n) \in \mathbb{N}$$
$$7. \quad \forall m,n \in \mathbb{N}, \quad S(m) = S(n) \implies m=n$$
$$8. \quad \forall n \in \mathbb{N}, \quad S(n) \neq 0$$

Axioms 2-4 are essentially saying that equality defined on the [[Natural Numbers]] is an [[Equivalence Relation]]. Axiom 5 is [[Closure]] under equality. Axioms 6-8 is defining the successor function $S()$ (essentially a [[Function]] for counting). Axiom 6 specifically is closure under the successor function. For axiom 7, if two numbers have the same successor then they are the same number. Axiom 8 is that 0 is not a successor. It is the [[Foundations/Functions & Relations/Least Element]] of the set $\mathbb{N}$ with the function $S()$ defined on $\mathbb{N}$.