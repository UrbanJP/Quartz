 The anova() function for giving [[ANOVA]] tables for [[Linear Model|Linear Models]]. It takes in a linear model like the [[lm()]] function to display the ANOVA table of the linear model. When testing multiple modes, it treats them in a [[Sum of Squares|Type I Sequential Sum of Squares]]. 

## Parameters
#### object =
The single model, or multiple models being included in the anova() function.

#### Test = 
The [[Test Statistic]] to output, the default is [[F-Test|F-statistic]], but other options include [[Chi-Squared Test|Chi-Squared]] which is the default for [[Logistic Regression]] and Poisson regression.

### dispersion =
Applies a dispersion value, more for logistic regression