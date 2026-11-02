The frequency-severity model, or the collective risk model, is a model for estimating the [[Pure Premium]]. It is calculated by summing All the severity claims
$$ S = \sum_{i=1}^N X_i$$ where $N$ is the number of [[Claim|Claims]] (frequency) and each $X_i$ is a [[Random Variable]] that corresponds to the severity of a given claim. All $X_i$'s are [[Independent and Identically Distributed (IID)]].


## Shortcomings
The pros of the frequency-severity model is that it is simple and easy to use, but a downside is that it severity and frequency are two variables that usually depend on different [[Rating Variable|Rating Variables]]. This is why sometimes frequency and severity are analyzed independently first then joined together. We can choose, for example, to model severity with a [[Lognormal Distribution]] (Because severity is often right skewed with a small number of highly sever claims), but model frequency with a [[Poisson Distribution]].