## Statistical Guides

This repo contains guides and notes on practical statistical methods. 

If you have comments, praise, critique or questions, we would love to hear from you. Contact the author directly, reach out to Rune.Haubo.Christensen _at_ regionh.dk or make a pull request.

## Contents

### Causal Inference

1. [`Kaplan-Meier as an IPCW estimator`](causal_inference/KM_as_IPCW_estimator.pdf) 
   - Describes how the Kaplan-Meier estimator is identical to and can be thought of as a inverse probability of censoring weighted (IPCW) estimator of the empirical cumulative distribution function (eCDF). The covers continuous and discrete time and provides examples in **R** demonstrating computations and equivalence to the conventional Kaplan-Meier estimator.
1. [`Methods to adjust for dependent censoring using IPCW`](causal_inference/dependent_censoring_and_ipcw.pdf) 
   - Illustrates methods to adjust for censoring on estimation of survival using a small data example. The note first illustrates adjusting for censoring assuming that the censoring process is independent of covariates, next, it illustrates how to adjust for dependent censoring assuming that the censoring process depends on a covariate. In particular, the method is demonstrated (1) using a Cox model for the censoring process or (2) using a logistic regression to model the censoring process. 

### Survival Analysis

1. [`Survival estimation with proportional hazards models`](survival_analysis/cox_survival_curve.pdf)
   - A primer on survival estimation with proportional hazard models using the **survival** package in **R**. 


### RCT Analysis

1. [`Linear and mixed-effects models for RCT analysis`](RCT_analysis/01_rct_models.pdf) Describes linear and mixed-effects models for the analysis of randomized controlled trials with examples in in **R** in the setting of a two-group, parallel trial. Upon describing a general linear RCT model with possibly correlated errors several aspects and special cases of the model are described including:
   1. General linear multivariate RCT model
   1. Assuming zero baseline treatment differences
   1. Mixed-effects equivalent of the multivariate general model
   1. The Mixed Model for Repeated Measurements (MMRM) special case
   1. The ANCOVA model (conditional on baseline values)
   1. Two-sample $t$-tests for end-of-trial values of change-scores (marginal models) 
    

### Miscellaneous

1. [`Risks, Rates and Ratios`](miscellaneous/risk_rates_and_ratios.pdf)
   - Summarize estimators and standard errors of risks, rates and odds
   - Summarize estimators for _ratios_ and _differences_ of risks, rates and odds
   - Summarize likelihood based derivation using binomial and Poisson models
1. [`Exponentials and Logarithms`](miscellaneous/exponentials_and_logarithms.pdf)
   - Properties of exponentials and logarithms
   - Rate of change
   - Changing base
   - Derivatives of logarithmic functions
   - On the value of $e$

