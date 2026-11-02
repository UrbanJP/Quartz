An equivalence relation is a [[Relation]] that is [[Reflexivity|Reflexive]], [[Symmetric Relation|Symmetrical]], and [[Transitivity|Transitive]]. An example is equality (=). These three terms are defined for [[Arity|Binary]] relations.


## Eight Examples of Relations
There are $2^3$ [[Combination|Combinations]] for the kinds of relations we can make with the three properties of reflexivity, symmetry, and transitivity. Here is one example of each combination.


Reflexive, Symmetric, and Transitive (Equivalence Relation)
- The equality relation (=) is an equivalence relation.

Reflexive and Symmetric but not Transitive


Reflexive and Transitive but not Symmetric
- The less than or equal to ($\leq$) relation is both reflexive and transitive but not symmetric. Since every number is equal to itself, for all numbers $x$, $x \leq x$. If $x \leq y$ and $y \leq z$ then $x \leq z$ satisfying transitivity. But a counterexample for symmetry is $2 \leq 3$ because $3 \not \leq 2$.

Symmetric and Transitive but not Reflexive


Reflexive only


Symmetric only
-  Let $R(a,b)$ be the relation "$\neq$". 
- Since for any number $b$ it is equal to itself, this relation is not reflexive. 
- It is symmetric because $a \neq b \implies b \neq a$. 
- Initially this relation seems transitive, but it is not. If we can find at least one example that is not transitive then the entire relation is not transitive. The transitive requirement is this: $\forall a,b,c \in X \, \, [(a \neq b \land b \neq c) \implies a \neq c]$. The counterexample is when $a=c$. Because $R$ is [[Irreflexive]] it cannot be transitive. 

Transitive only
- The less than ($<$) relation is only transitive. For all $a$ it is not the case that $a<a$ and if $a<b$ then $\neg (b<a)$.

None
- Let $R(a,b)$ be the relation "$a$ is the [[Foundations/Functions & Relations/Least Element]] of $b$". 
- __Reflexivity__: Since, by the second axiom of [[Zermelo-Fraenkel Set Theory]], sets cannot contain themselves, then $a$ cannot be the least element of itself and hence $\neg R(a,a)$ negating reflexivity.
- __Symmetry__: Since $b$ is necessarily a set but $a$ is not necessarily a set, then there exists a value $a$ and set $b$ where $R(a,b)$ but not $R(b,a)$. In this case $a$ has no least element.
- __Transitivity__: Let $R(a,b)$ and $R(b,c)$. Since sets cannot contain themselves under [[Zermelo-Fraenkel Set Theory|ZFC]], the least element of $b$ is not equal to $b$, therefore $a \neq b$. Because $b \neq a$ and $b$ is the least element of $c$ then $\neg R(a,c)$ negating transitivity.
- Another example is the relation $\in$.