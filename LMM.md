# The Basics of Linear mixed-effects models #

## What is LMM? ##
- LMM or mixed (effect) model or hirechical linear model is a statistical technique that is getting popularity in neuroscience and experimental psychology.
- An LMM describes the relationship between a response variable and other explanatory variables that have been obtained along with the response.
- At least one predictor must be categorical.

## When do we use LMM? ##
- We can use LMM for a within-subject/within-group design, e.g., Participants respond to different tasks, and each task takes 80 trials. 
- Clearly there must be some internal correlations within tasks or participants' responses
- Question: Instead of LMM, which statistics do we usually use for this designs?


![A visualised model speaks more](https://miro.medium.com/max/1400/1*1r_s5QKOk2LRFjazaXghgA.gif)


## Why do we use LMM over the othe approach? ##
- The statistical assumption for LMM is more flexible.
- Taking missing values into account.
- LMM provides the size or the magnitud of an effect.
- Easily done in R.

## Parameters of LMM
The reason why we call it a mixed effect is because it simultaneously includes both *fixed* and *random* effects.

### Fixed effects
- Fixed effects represent population-level effects that should apply across experiments, e.g., reaction time and sleep deprivation or cognitive flexibility and alcohol comsumption. 
- Fixed effects include fixed intercept and fixed slopes


### Random effects
- Random effects model the variability of the general fixed effects across different levels of some grouping factors. 
- Anyone would like to offer an example of what kind of variation we might get in an experiment?
- Random effects include random intercepts and random slopes

[Visualisation of fixed effect and random effect](https://journals.sagepub.com/doi/full/10.1177/2515245920960351)
--
### Summary
- LMM as an advanced stats that becomes more popular in experimental psychology, especially reaction time studies.
- LMM avoides the multicolinearity issue and missing values, and provide estimates for individual effect.
- It can be easily run LMM and compare models in R, making the analysis more transparent. 
- There is no standardised practice for running LMM, you can apply it freely as long as you have justified your decision-makings.

### Recommended papers on LMM

1. Barr, D. J. (2013). Random effects structure for testing interactions in linear mixed-effects models. *Frontiers in psychology*, 4, 328.
2. Brown, V. A. (2021). An Introduction to Linear Mixed-Effects Modeling in R. *Advances in Methods and Practices in Psychological Science*, 4(1), 2515245920960351.
3. Meteyard, L., & Davies, R. A. (2020). Best practice guidance for linear mixed-effects models in psychological science. *Journal of Memory and Language*, 112, 104092.






