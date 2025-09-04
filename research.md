---
title: Research
---

Broadly, my research has focused on infectious disease reporting and forecasting as part of my work with the [Delphi group](https://delphi.cmu.edu/) at CMU. Prior to my work with Delphi, I also collaborated with Novartis for post-hoc analysis of two of their clinical trials. 

**Bayesian hierarchical modeling for correcting reporting delay in infectious disease forecasting**

My current research focuses on the problem of reporting delays for infectious disease cases. While the best predictor of next week's flu cases would probably be the current cases, not everyone who currently has the flu has gone to the doctor yet, and for those who have, their cases may not have been reported to health authorities or submitted as claims to insurance; this leads to incomplete information to be used for forecasting future cases. My current work involves using Bayesian hierarchical modeling to jointly estimate both the total cases as well as the distribution of reporting delays, in order to predict what the true current case counts are in order to improve forecast accuracy. I have been working with Stan in R, but am working to convert the implementation to use pyro/PyTorch for its additional capabilities relative to Stan. 


**Incorporating spatial information into influenza-like illness forecasting**

This work has been published in [Epidemics](https://doi.org/10.1016/j.epidem.2025.100820).
