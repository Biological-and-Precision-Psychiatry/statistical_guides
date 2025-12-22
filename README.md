## Statistical Guides

This repo contains guides and notes on practical statistical methods. 

If you have comments, praise, critique or questions, we would love to hear from you. Contact the author directly, reach out to Rune.Haubo.Christensen _at_ regionh.dk or make a pull request.

## Contents

### RCT analysis

Notes related to analysis of Randomized Controlled Trials

1. [`01_rct_models`](RCT_analysis/01_rct_models.pdf): 
   Describes linear and mixed-effects models for the analysis of randomized controlled trials with examples in in **R** in the setting of a two-group, parallel trial. Upon describing a general linear RCT model with possibly correlated errors several aspects and special cases of the model are described including:
   a. Assuming zero baseline treatment differences
   b. Mixed-effects equivalent of the multivariate general model
   c. The Mixed Model for Repeated Measurements (MMRM) special case
   d. The ANCOVA model (conditional on baseline values)
   e. Two-sample $t$-tests for end-of-trial values of change-scores (marginal models) 
