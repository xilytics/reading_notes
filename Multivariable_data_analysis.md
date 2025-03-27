### Four 'articles of faith' that may cause serious problems
1. Overrating accuracy if we ignore false positives
2. Replacement of causation with correlation
3. The idea that sampling bias is eliminated when the issues still remain
4. Letting the 'data speak' and ignoring the presence of spurious correlations

### Two different approaches towards analysis
1. Statistical or data models: A researcher specified model that is then estimated using the data available to assess model fit and ultimately its acceptability.
- Challenges: correctly specify a model form that represents the process being examined, and perform the analysis correctly to provide the explanation and predition desired.
- The researcher must take some assumptions as to the nature of the process and specify a model form that best replicates its operations.
- Examples: MANOVA, logistic regressions, etc.
- The researcher must recognize that any conclusions are about the proposed model and not really about the underlying process.
- Usually for explanation, is theory based, structured, type of data analyzed are well defined, collected for purpose of the research.

2. Data mining or algorithm models: The focus is not on the specified model, but the technique of explanation.
- The fundamental premise here is that the process being studied is inherently so complex that specification of a precise model is impossible.
- Rather, the emphasis is on the algorithms, how they can represent any complex process and how well they ultimately predict the outcomes.
- Examples: neutrual networks, decision trees and even cluster analysis - where the result is a prediction, not a generalization to the population.
- Usually for prediction, heuristic-based, unstructured, exploratory, undefined, generally analysis using data available.

### Metric Measurement Scales
- Interval scales, examples: Temperatures in Fahrenheit or Celcius.
- Ratio Scales, represent the highest form of measurement precision.

### Measurement error and multivariate measurement
- Measurement error: the degree to which the observed values are not representative of the true values.
- All variables used in multivariate techniques must be assumed to have some degree of measurement error.
- To assess the degree of measurement error: 1. Check validity (ask the right question, collect the right data) 2. Check reliability (if asked multiple times, will this remain consistent).
- Multivariate Measurement: summated scales, several variables are joined in a composite measure to represent a concept. The core reason to do this is the assumption that a composite measure reflect the true response more accurately than a single one does.

### Managing the Multivariate Model
- Managing the variate: Taking care of multicollinearity - when focused on only predictions it has no real impact, but when the goal is **explanation** of the individual variables' impact, we want to assess the impact for any individual independent variable. The constant challenge: Including more variables as predictors to increase overall predictive power versus the **multicollinearity** introduced by more variables which makes it more difficult to attribute the explanatory effect to specific variables.
- Specifying the Variate Variables - A solution for the above is often dimensional reduction - forming composites and the researcher then uses the composites in further analysis rather than the original variables.
- Specification of the variate is critical  --- including too many variables may hinder may hinder the ability of the model to recover more generalized effects and thus the efficacy of the results.
- The possibility of several alternative models increases as the number of variables grows larger. So researchers should **try a number of alternative models** in specifying their research.
  

### Managing the dependence model
- Single equation forms: Multiple regresstion, discriminant analysis, ANOVA, and logistic regression. All of them provide an approach for specifying a single variate's relationship with an outcome variable.
- Multiple equation forms: relate different equations to one another
- General linear model: can estimate canonical correlation, multiple regression, ANOVA, MANOVA and discriminat analysis...an error distribution following the normal distribution.


### Statistical significance vs. statistical power
- Statistical errors: Type I alpha, false positive, the probability of rejecting the null hypothesis when it's true (不应该拒绝零假设但是拒绝了，随机因素可能是造成差异的原因）; Type II, beta, probability of not rejecting the null hypothesis when it's actually false (the power of the statistical inference test)（应该拒绝零假设但是没拒绝）.
- Power: the probability that statistical significance will be indicted if it's present, when the null hypothesis is false, and that we should rejecting the null hypothesis. 1-beta
- We must strike a balance between the level of alpha and the resulting power as they are inversely related.
- 3 factors that impact on statistical Power: Effect size, significance level, sample size. Cohen suggests that studeis be designed to achieve **alpha levels of at least .05 with power levels of 80 percent**. Smaller effect size to be expected, bigger sample sizes are likely needed.



