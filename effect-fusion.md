@def title = "Effect fusion priors"

# Effect fusion priors

First introduced by Daniela Pauger and Helena Wagner in [this 2019 paper](https://projecteuclid.org/journals/bayesian-analysis/volume-14/issue-2/Bayesian-Effect-Fusion-for-Categorical-Predictors/10.1214/18-BA1096.full)[^1], effect fusion priors are designed to induce sparsity on the differences between the coefficients that represent the effects for each level of a categorical variable.

My colleague [Javier Aguilar](https://jear2412.github.io) and I are currently developing an extension of that core idea and software to support it. Our main goal is to may this technique more accessible to applied researchers. An overview of these research directions can be found on [this poster](/assets/fxfus-poster.pdf), which I presented at [Bayesian Methods for the Social Sciences II](https://bayesforshs2.sciencesconf.org).

We are currently developing implementations of the prior for [**Turing**](https://turinglang.org/) and [**Stan**](https://mc-stan.org). In the meantime, a basic **R**-based sampler for the prior, which I used for the plots in the poster, can be found [here](https://gist.github.com/lunafazio/d8cf6a0dec24b02b89e0c2f98b4f4902).

[^1]: Actually, the earliest record I can find of their idea is their 2014 contributed paper for the [29th International Workshop on Statistical Modelling](http://www.statmod.org/workshops_archive_proceedings_2014.htm), followed by a [2017 arXiv preprint](https://arxiv.org/abs/1703.10245), but I think the "official publication" is meant to be the one linked above.