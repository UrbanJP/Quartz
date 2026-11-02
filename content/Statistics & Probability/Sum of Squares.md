A sum of squares is a summation of a squared value e.g. $\sum x_i^2$. This formulation appears a lot in statistical modeling. Some cases are [[Total Sum of Squares]], [[Residual Sum of Squares (RSS)]], and [[Regression Sum of Squares (SSR)]]. 

Whether your data is balanced or unbalanced determines if what type of sum of squares you go with. For ANOVA, balanced data means all factors have the same number of levels. Unbalanced data is any data that is not balanced.
## Types
#### Type I Sum of Squares (Sequential)
Also known as a sequential sum of squares, the type I sum of squares applies an order for evaluating which [[Factor (Statistics)|Factor]] is tested for variance explanation first. For example, in R, if we have (y ~ method + gender), the method is tested for explanation first and then whatever is left over goes to gender. This means that (y ~ gender + method) is likely to give a different result. The anova() function defaults to type I.

#### Type II Sum of Squares (Hierarchical/Marginal)
Tests each of the main effects, but ignores interactions. It tests individually how much each factor explains about the data by itself, but ignores any combination of the factors.

#### Type III Sum of Squares (Partial Sum of Squares)
Tests all individual effects and combinations of effects. It is most beneficial to test if adding a variable helps after everything else is already considered. For type III in R you must use the function car::Anova(..., type=3)