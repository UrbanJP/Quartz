A design matrix $X$ is a matrix consisting of values from [[Predictor Variable|Predictor Variables]]. The motivation is to construct the [[General Linear Model]], a collection of multiple [[Linear Regression]] models.

## Formal Definition
A design matrix $X$ in a linear regression model $y=X \beta + e$ is a matrix where [[Element]] $X_{ij}$ represents the value of the $j^{th}$ variable with the $i^{th}$ object. ~~The columns consist are the [[Range]] of [[Random Variable|Random Variables]] meaning these values are in the [[State Space]] rather than the [[Sample Space]]. This maintains that the design matrix consists of only numerical data.~~

Here, $y$ is a [[Vector]] of [[Response Variable|Responses]], $\beta$ is a vector of coefficients, and $e$ is a vector of [[Random Error]].

## Examples
1. Consider an [[Trials and Experiments|Experiment]] consisting of asking 100 people 20 yes or no questions. Then we can construct this into a design matrix of [[Dimension]] $100 \times 20$ 
$$ X  = \begin{bmatrix} 1 & 1 & 1 & \ldots & 0 \\
1 & 1 & 0 & \ldots & 0 \\
\vdots & \vdots & \vdots & \ddots & \vdots \\
1 & 0 & 0 & \ldots & 0 \end{bmatrix}$$
	Notice that the design matrix consists of only numerical values. The zeroes and ones are used to represent No and Yes for the responses.