A multiple integral is a [[Definite Integral]] over a multivariate [[Function]]. For functions $f(x,y)$ and $f(x,y,z)$ we can construct double and triple integrals
$$\int_a^b \int_c^d f(x,y) \, dydx \qquad \qquad
\int_a^b \int_c^d \int_j^k f(x,y,z) \,dy dz dx$$
This can be extrapolated to $n$ variables
$$\int \int \ldots \int_D f(x_1,x_2 \ldots, x_n) \,\, dx_1 dx_2 \ldots dx_n$$
where $D$ is the domain restricting the bounds.

Multiple integrals are calculated in chunks starting with the innermost integral first and ending with the outermost integral. Start at the middle and move outwards.
$$\left[ \int \left[ \int \ldots \left[ \int_D f(x_1,x_2 \ldots, x_n) \,\, dx_1 \right] dx_2 \ldots \right] dx_n \right]$$

## Finding Bounds
In general, when finding the bounds of a multiple integral we write the inner integral in terms of the outer variables. This leaves the outermost bounds as constants.
$$ \int_{x=a}^{x=b} \int_{y=g(x)}^{y=h(x)} \int_{z=\delta(x,y)}^{z=\sigma(x,y)} f(x,y,z) \,dz dy dx$$
For this integral, because it is in $dz dy dx$ form, we first find the $z$ bounds. Traveling only through the $z$ axis, we enter the region $D$ from $z=\delta(x,y)$ and exit through $z=\sigma(x,y)$. We then collapse $D$ into $\mathbb{R}^2$ with variables $(x,y)$. Travelling only through the $y$-axis, we enter the collapsed region of $D$ from $y=g(x)$ and exit through $y=h(x)$. We collapse $D$ again from $\mathbb{R}^2$ to $\mathbb{R}$. This time we travel through the $x$-axis entering from $a$ and exiting at $b$.
