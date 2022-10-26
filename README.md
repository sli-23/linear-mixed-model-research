# Linear Mixed Model Research

- [Linear Mixed Model Research](#linear-mixed-model-research)
  - [Introduction](#introduction)
    - [Theory of Linear Mixed Models](#theory-of-linear-mixed-models)
  - [Contents](#contents)
  - [Reference](#reference)

## Introduction
Linear mixed models are an extension of simple linear models to allow both fixed and random effects, and are particularly used when there is non independence in the data, such as arises from a **hierarchical structure**. 

The core of mixed models is that they incorporate **fixed and random effects**. 
* A **fixed effect** is a parameter that does not vary.
* **Random effects** are parameters that are themselves random variables.

### Theory of Linear Mixed Models
$$
\underbrace{y}_{\text{outcome}} = \underbrace{X}_{\text{predictor}} \overbrace{\beta}^{\text{fixed-effects}} + \underbrace{Z}_{\text{design matrix}} \overbrace{u}^{\text{random-effects}} + \underbrace{u}_{\text{residuals}}
$$
In more specific,
$$
\overbrace{y}^{N \times 1} = \overbrace{\underbrace{X}_{X \times p} \quad \underbrace{\beta}_{p \times 1}}^{X \times 1} + \overbrace{\underbrace{Z}_{N \times qJ} \quad \underbrace{u}_{qJ \times 1}}^{N \times 1} + \overbrace{\varepsilon}^{N \times 1}
$$

**Example**:


## Contents
1. [Non-Parametric Models](Non-parametric.md)

## Reference
1. https://stats.oarc.ucla.edu/other/mult-pkg/introduction-to-linear-mixed-models/
2. 