---
title: 'ivporbit:An R package to estimate the instrumental variables probit model'
tags:
    - limited-dependent variable models
    - Amemiya's Generalized Least Squares estimators
    - R
    - ivprobit
authors: 
    - name: Taha Zaghdoudi
      orcid: 0000-0002-4488-5774
      affiliation: 1
affiliations:
    - name: Faculty of Law, Economics and Management of Jendouba, Tunisia
      index: 1
date: 13 December 2017
bibliography: paper.bib
---

# Summary #
ivprobit [@zaghdoudi] is an open source R package that fit the instrumental variables probit model. The package comprises function that deal with endogeneity misspecification especially when correlation between
regressors and error term is determinited and which produce inconsistent results.  To avoid
this problem, authors applied the instrumental variable method in which they use
the correlated variables as instruments. Nevertheless, a two-stage method are used by
some authors [@blundell2004endogeneity] to fit the probit model but
it produce non efficient result.

However, [@newey1987efficient] expose an efficient way to
estimate limited-dependent variable model by using the Amemiya's
Generalized Least Squares estimators (AGLS) [@Amemiya1978]. Likewise, in the ivprobit package we use the AGLS method and we
include in the two-stage model a continuous endogenous regressor. This
method is used when the maximum likelihood method (MLE) fail to estimate the model.

ivprobit is GPL-3 licensed and can be retrieved from GitHub [Repository](https://github.com/cran/ivprobit)

[ivprobit CRAN](https://cran.r-project.org/web/packages/ivprobit/index.html)

[Archive](https://zenodo.org/record/1183253#.Wo7IEYPOXIU)

# References #
