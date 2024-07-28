---
layout: page
permalink: /cfp/
title: call for papers
description:
nav: true
nav_order: 1
---

In order to promote a productive workshop in the field of time series analysis and prediction, we invite submissions of papers that address the following topics:

* Building and analysing Foundation Models for Time Series
* Leveraging Pretrained Models of Other Modalities for Time Series
* Multimodal Time Series Models
* Time Series Evaluation and Real-World Applications

We welcome submissions of papers that are either original research contributions or review papers. We also encourage submissions of papers that are under review or have been recently published in other venues.

## submission recommendations

We encourage the authors not to use and submit results based on the typical "MAE/MSE" table of results due to the following reasons:
* due to a bug in the evaluation code these metrics are no longer correct as they have not been corrected in their respective papers;
* the metric reported in these tables is not actually MAE/MSE but rather the normalized-MAE/ normalized-MSE, and the global normalization of data is sporadically reported causing further confusion;
* the tables are reporting point-forecasting metrics that do not take into account the uncertainty of the forecasts that is crucial for decision-making and real-world applications;
* the tables typically compare univariate models to over-parametrized non-linear models in the multivariate setting trained on small datasets that are known to learn spurious correlations and perform worse than the same models in the univariate settings, leading to flawed conclusions;
* the tables compare typically univariate models to overly-simplistic univariate models that do not take into account all the data and inductive biases of forecasting into account, leading to flawed conclusions.

We therefore encourage the authors to consider:
* using a distributional forecasting output head;
* retain the scale of the data when reporting metrics and evaluating;
* give each model all the information it needs to perform well, for example if normalizing a context window (a method predating the RevIN approach), provide the model with the normalization parameters as inputs (as done prior to the explicit method of Non-stationary Transformer);
* when modeling truly multivariate emission models, report probabilistic metrics that take into account the correlations between the variates, why go to the trouble of modeling the correlations if you are not going to use them in the evaluation and predictions? 
* compare univariate models against univariate variants of other models especially when using the standard open datasets, do not use the multivariate models to make your method stand out.

When it comes to implementation, we encourage the authors to make sure that:
* reshaping the variate dimension to the batch dimension prior to modeling and reshaping it back does not lead to a multivariate model and in fact handicaps the univariate model from training datasets with very large number of variates; 
* if you have a univariate model then train it on the M5 dataset; if you cannot then you are not modeling the data correctly.
