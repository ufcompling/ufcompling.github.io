---
layout: page
title: CDR(NN)
description: A regression technique for temporally diffuse effects.
img: /assets/img/cdr_header.png
importance: 1
category: ongoing
github: https://github.com/coryshain/cdr
---

In many real world time series, events trigger "ripples" in a dependent variable that unfold slowly and overlap in time (temporal diffusion).
Recovering the underlying dynamics of temporally diffuse effects is challenging when events and/or responses occur at irregular intervals.
Continuous-time deconvolutional regression (CDR) is a regression technique for time series that directly models temporal diffusion of effects (Shain & Schuler, 2018, 2021) as a funtion of continuous time.
CDR uses machine learning to estimate continuous-time impulse response functions (IRFs) that mediate between predictors (event properties) and responses.
Given data and a model template specifying the functional form(s) of the IRF kernel(s), CDR finds IRF parameters that optimize some objective function.
This approach can be generalized to account for non-stationary, non-linear, non-additive, and context-dependent response functions by implementing the IRF as a deep neural network (CDRNN; Shain, 2021).


### Publications

Shain, Cory and Schuler, William (2018). Deconvolutional time series regression: A technique for modeling temporally diffuse effects. _EMNLP18_.

Shain, Cory and Schuler, William (2021). Continuous-time deconvolutional regression for psycholinguistic modeling. _Cognition_.

Shain, Cory (2021). CDRNN: Discovering complex dynamics in human language processing. _ACL21_.
