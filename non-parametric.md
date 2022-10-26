# Nonparametric Statistical Models

* [Nonparametric Statistical Models](non-parametric.md#nonparametric-statistical-models)
  * [What is nonparametric statistical models?](non-parametric.md#what-is-nonparametric-statistical-models)
  * [Reference](non-parametric.md#reference)

## What is nonparametric statistical models?

任何一个模型的建立都有其**基础和假设**。而参数模型（parametric models）和非参数模型（Nonparametric models）同样也有。二者主要的区别在于关于对**数据分布**的假设：

* 参数模型对数据分布（distribution，density）有假设
  * 对数据分布有理想的假设，模型更加robust。
  * 利用数据的数量关系及其分布进行检测和预测（tests and inference）
* 非参数模型对数据分布假设自由（distribution-free），但是对数据必须可以排序（rank，score）。
  * 更加关注数据先后顺序，显得更加powerful。
  * 利用数据本身的序列进行检验和预测。

A statistical model for a random observation $Y$ is a family $$\\{ P_f: f \in \mathcal{F} \\}$$ of probability distributions $P_f$, each of which is a candidate for having generated the observation $Y$. The parameter $f$ belongs to the *parameter space* $\mathcal{F}$. The problem of _statistical inference_ on $f$ , broadly speaking, can be divided into three intimately connected problems of using the observation $Y$ to

1. _Estimate_ the parameter $f$ by an estimator $T(Y)$,
2. _Test hypotheses_ on f based on test functions $\Psi(Y)$ and/or
3. _Construct confidence_ sets $C(Y)$ that contain f with high probability

## Reference

1. https://www.zhihu.com/question/22855599
2. Mathematical Foundations of Infinite-Dimensional Statistical Models
3.
