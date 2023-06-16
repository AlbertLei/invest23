---
title: "Quick Q&A"
---

1. Explain why the "Nearest Neighbors" algorithm fails in a high-dimensional setting. 

1. True or False?
Suppose we are interested in learning about a relationship between *X* and *Y*.
The estimate b₂ in a linear regression that **controls for many variables** is usually a more reliable measure of a causal relationship than b₁ from a univariate regression on *X*.

1. In R, what is the difference between `lm(y ~ x*z)` and `lm(y ~ I(x*z))`? Suppose both `x` and `z` are numeric variables.

1. If we use ten-fold cross-validation as a means of model selection, the cross-validation estimate of test error is biased upwards or downwards?

1. Why can't we use the standard bootstrap for some time series data?

1. Consider model selection among linear models. Why best subset selection may not achieve a
lower test RSS than forward selection? 

1. You perform ridge regression on a problem where your second predictor, x₂, is measured in dollars. You decide to refit the model after changing x₂ to be measured in cents. Which one will change, the estimated β₂ or the estimated y? 

1. In tuning a LASSO model, as one increases λ from 0, what will happen to the training RSS?

1. What are potential advantages of BART over random forests and boosting?


## Answers

1. For a uniform cube in a high-dimensional space (say p≥50), more than 99% percent of the mass are in the boundary of the cube. So, it usually makes no sense to find a ball centered at X
that contains 10% of the data points.

1. False.   
   Adding lots of extra predictors to the model can just as easily muddy the interpretation of *b* as it can clarify it. One often reads in media reports of academic studies that "the investigators controlled for confounding variables," but be skeptical!

1. An interaction term between a numeric `x` and `z` is just the product of `x` and `z`. The difference is that in the first model, `lm` processes the `*` operator between variables and automatically includes main effects, whereas in the latter model, the expression inside the `I()` function is not parsed as a part of the formula, but rather is simply evaluated.

1. It's uncertain. There are competing biases: 
    
    - on one hand, the cross-validated estimate is based on models trained on smaller training sets than the full model, which means we will tend to overestimate test error for the full model.
    -On the other hand, cross-validation gives a noisy estimate of test error for each candidate model, and we select the model with the best estimate. This means we are more likely to choose a model whose estimate is smaller than its true test error rate, hence, we may underestimate test error. In any given case, either source of bias may dominate the other.


1. The usual bootstrap algorithm samples i.i.d., so there is no serial autocorrelation (unlike what is observed in most time series). This makes the set of resampled time series very very different from the sorts of time series we actually get in the real world.

1. Best subset selection fits the data too hard and is very likely to lead to overfitting.
We only know that best subset selection will have the lowest training RSS.

1. Both.

1. Increasing λ will generally lead to a simpler model, and so training RSS will increase.

1. As a Bayesian method, BART draws samples from a posterior distribution and hence provides standard errors and posterior confidence intervals for any quantity of interest.
