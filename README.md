# Linear Mixed Model Research

### Preface

{% hint style="warning" %}
This research notebook contains Chinese and English.
{% endhint %}

{% hint style="info" %}
This research notebook is for learning and doing research with Prof. Kramlinger in UC Davis. All notes are from online and textbook and will be referenced at the end of each notes.
{% endhint %}



### Introduction

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

{% tabs %}
{% tab title="Example #1" %}

{% endtab %}

{% tab title="Second Tab" %}

{% endtab %}
{% endtabs %}

### Reference

1. https://stats.oarc.ucla.edu/other/mult-pkg/introduction-to-linear-mixed-models/
2.
