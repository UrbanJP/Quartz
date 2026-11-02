Ordinary least squares (OLS) is a method to estimate the values of $(\beta_0, \beta_1)$ in a [[Linear Regression]] model. This method finds the values of $\hat \beta_0$ and $\hat \beta_1$ ([[Parameter Estimators]] of $\beta_0$ and $\beta_1$) that minimizes the [[Residual Sum of Squares (RSS)]]. Upon derivation this comes out to be
$$\hat \beta_1 = \frac{S_{XY}}{S_{XX}} = \frac{\sum(x_i - \bar x)(y_i - \bar y)}{\sum (x_i - \bar x)^2} 
\qquad \qquad \qquad 
\hat \beta_0 = \bar y - \hat \beta_1 \bar x_i$$
As the name suggests, the estimates will be the values with the least squared error.
## Derivation
To minimize, we take [[Partial Derivative|Partial Derivatives]] with respect to $\beta_0$ and $\beta_1$ of $RSS$ and equate to zero.

$$\frac{\partial RSS}{\partial \beta_0} = -2\sum_{i=1}^n(y_i - \beta_0 - \beta_1x_i) = 0$$
$$\frac{\partial RSS}{\partial \beta_1} = -2\sum_{i=1}^n x_i(y_i - \beta_0 - \beta_1x_i) = 0$$
From this we can derive the [[Parameter Estimators]] for $\beta_0$ and $\beta_1$. After re-arranging the equations we get


## Assumptions
Underlying the ordinary least squares are several assumptions for all $i$.
$$1. \quad  E[\varepsilon_i] = 0$$
$$ 2. \quad Var(\varepsilon_i) = \sigma^2$$
$$ 3. \quad \varepsilon_i \text{ are independent of each other}$$
$$ 4. \quad \varepsilon_i \sim N(0,\sigma^2)$$
The first is that the expected value of each error term is zero. The second is the homoscedasticity condition, that variance is constant. The third condition is that error terms are not dependent on any other error term. Lastly, the error is distributed normally with expected value and variance from assumptions $1$ and $2$.
