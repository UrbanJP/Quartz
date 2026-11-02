The law of total variance is a rule about [[Variance]] where, for a [[Random Variable]] $Y$, we can split up the variance into an explained component and an unexplained component. The portion that is explained is the variance of group [[Mean|Means]]. The unexplained portion is the mean of within-group variances.

This straightforwardly allows for the partitioning of the [[Total Sum of Squares]] for [[ANOVA]] $$SST = SS_{\text{between}} + SS_{\text{within}}$$
See [[ANOVA]] for a more rigorous breakdown.

## Formal Definition
$$\text{Var}(Y) = E[\text{Var}(Y|X)] + \text{Var}(E[Y|X])$$
