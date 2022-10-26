# Instructions from Prof. Kramlinger

### Notes - 9/30/2022

{% hint style="danger" %}
The following instructions is directly from Prof. Kramlinger's email.
{% endhint %}

I’d like to follow up to my presentation on Wednesday. The fundamental problem is that:

* LMM methodology requires the covariance matrix to be inverted
* This is easy if it's in block-diagonal form as for simple LMMs
* Time series data, non-nested groups and and spline regression can result in non-block-diagonal covariance matrices
* `lme4` works well in R and Julia, but can't treat such cases
* `nlme` can treat such cases, but doesn't work in Julia

**Therefore**:

* We would like to understand how the LMM estimation works (internally) if the covariance matrix is not block-diagonal
* We would like to fit such models in Julia

**Goal**:

* Produce a handbook that outlines the problem, ...
* how to tackle it, ...
* and offers an implementation in Julia.

**The first steps should be**:

* Get to know Julia (https://julialang.org, https://docs.julialang.org/en/v1/)
* State simple LMM (random intercept model) and implement its estimation (for now, assume we know the variance components / use synthetic data)
* Extend the implementation to time series Demidenko, Section 4.3.4
* Extend to non-Toeplitz matrices

We should meet again and talk about your impressions and take on this. I’d like to share your findings and put each of you to specialized tasks later on.

We can meet again to talk about smaller issues next week, but should schedule a joint meeting for all to discuss the findings someday later.

***
