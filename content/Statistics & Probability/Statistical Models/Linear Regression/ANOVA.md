Consider a collection of students who all take an exam. All the students score differently on the exam, but why? This question is the core of [[Linear Model|Linear Modeling]]. Why is there a difference in scores? or, the same question formulated more rigorously, how much of the [[Variance]] can we explain? 

To answer the question we can say the students studied a different number of hours or not every student spends the same amount of time in class or something along those lines. These are numeric [[Predictor Variable|Predictor Variables]]. On the other hand, say there are different teaching methods $A, B,$ and  $C$, or different students took the class during different terms, Fall, Spring, and Summer. These are [[Categorical Variable|Categorical]] [[Predictor Variable|Predictor Variables]]. ANOVA is a type of [[Linear Model]] that has a [[Continuous]] [[Response Variable]] with [[Categorical Variable|Categorical]] [[Predictor Variable|Predictors]].

## Types of ANOVA
ANOVA tests are all [[Linear Model|Linear Models]], but they can be broken up into two categories. One-way ANOVA and Factorial ANOVA. A one-way ANOVA only has one predictor with two or more [[Level|Levels]]. It tests whether at least one group mean differs from the rest. A factorial ANOVA has two or more categories where each predictor is tested for an independent effect on the response and also every combination of variables are tested together for a conjoined dependence effect on the response. If a factorial ANOVA contains $n$ categorical predictors, then there are $\sum_{i=1}^n\binom{n}{i}$ [[Combination|Combinations]] of variables to consider. 

A special case of the factorial ANOVA is when $n=2$. This is called the two-way ANOVA.

## Breakdown of ANOVA
$SS_{\text{between}}$
This is the [[Variance]] of means between groups? Why do some group(s) have higher or lower averages? Why do the group means vary between each other? This is explained by the value of the category. 

An example is teaching methods $A$, $B$, and $C$. If teaching method $A$ is better, the group of individuals that learned through method $A$ would have a higher mean score on exams. So the variance between groups is explained by the group [[Predictor Variable]], in this case the predictor is the teaching method

$SS_{\text{within}}$ 
Consider all the variances within each group. $SS_{\text{within}}$ is the [[Expected Value]] of these variances. This is not explained. 

Considering the teaching methods example again, for any teaching method, we do not know why individuals score higher or lower if they are in the same group (being in the same group means being exposed to the same teaching method). Even though in group $A$ everyone was taught through the same method, some students scored higher and some lower. This can be for a wide number of reasons which is why this variance is unexplained.