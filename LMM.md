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






