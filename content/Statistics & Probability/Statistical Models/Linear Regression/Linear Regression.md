Linear regression is a statistical model that estimates a relationship between a [[Response Variable]] and one or more [[Predictor Variable|Predictor Variables]]. It uses a [[Linear Combination]] of predictors, typically just one line, to best fit the data. If there is only one predictor the model is a simple linear regression. If there are multiple predictors the model is a multiple linear regression.

In the case with only one predictor variable, the linear model is
$$y_i = \beta_0 + \beta_1 x_i + \varepsilon_i$$ and for multiple predictors we have
$$ y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \ldots + \beta_n X_n$$

Each $\beta_i$ is called a parameter and these parameters are estimated by [[Parameter Estimators|Parameter Estimation]] methods like [[Ordinary Least Squares]].