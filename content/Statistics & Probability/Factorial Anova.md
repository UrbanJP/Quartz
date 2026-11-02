Factorial ANOVA is a type of [[ANOVA]] where tests are not only of factors independently, but that factor dependence is tested between each other.


## R Code

```{r}
anova = aov(y ~ a + b)
factorial_anova = aov(y ~ a * b)
# aov(y ~ a * b) is the same as aov(y ~ a + b + a:b)
```

