Consider a [[Joint Probability Density Function]] $f_{XY}(x,y)$. The marginal probability density functions (Marginal PDFs) $f_X(x)$ and $f_Y(y)$ would be the probability of all $x$ values and all $y$ values respectively. 

## Finding the Marginal PDF
For a joint probability density function of two variables the marginal pdf of $X$ and $Y$ are defined as
$$f_X(x) = \int_{-\infty}^{\infty}f(x,y)dy \qquad \qquad
f_Y(y) = \int_{-\infty}^{\infty}f(x,y)dx$$
Essentially, for any marginal pdf of a variable $X_a$ we integrate with respect to all variables except for $X_a$. If we have a joint probability density function $f_{X_1X_2 \ldots X_n}(x_1, x_2, \ldots x_n)$ then to find $f_{X_i}(x_i)$ we integrate
$$\int_{-\infty}^{\infty} \ldots \int_{-\infty}^{\infty} 
f_{X_1X_2 \ldots X_n}(x_1, x_2, \ldots x_n) \
dx_1 \, \ldots dx_{i-1} dx_{i+1} \ldots dx_n$$
leaving out $\int dx_i$. 

See [[Multiple Integral]] for finding bounds. To check if a marginal PDF is correct, make sure none of the values are negative and that the integral of the newly found function with respect to the marginal [[Random Variable]] is equal to 1 on its numerical interval. An explanation of this is given below.

## Geometrical Explanation

**Using Tikzpicture

## Examples
1. Let $f_{XY}(x,y) = \frac{4y-x}{20}$ where $0 \leq y \leq 2$ and $0 \leq x \leq 3y$ be a joint probability distribution. Find $f_X(x)$ and $f_Y(y)$.

The [[Support]] is the double shaded region shown [here](https://www.desmos.com/calculator/7inkkskgoa). We construct the following integral
$$f_X(x) = \int_{-\infty}^{\infty}f(x,y)dy = \int_{x/3}^2 \frac{4y-x}{20}dy$$
Upon solving this integral we get the [[Expression]] $$\frac{x^2}{180}-\frac{x}{10}+\frac{2}{5} \quad \text{on the interval} \quad 0 \leq x \leq 6$$
This is the marginal PDF. To double check we construct an integral with respect to $x$ using the interval of $x$ for our bounds. We check if this integral is equal to 1.
$$\int_0^6 \frac{x^2}{180}-\frac{x}{10}+\frac{2}{5} =1$$
