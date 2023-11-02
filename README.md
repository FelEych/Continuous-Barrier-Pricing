# Continuous-Barrier-Pricing
A project that showcases the pricing of continuous barrier options using Monte-Carlo techniques.

Using Monte Carlo simulations to price continuous barrier contracts yield a bias, whether it is with one asset or more. This is why some numerical techniques are needed in addition to the naive Monte-Carlo procedure. For example, trying to price a down-and-out call with only MC will result in a biased estimator: brownian bridge techniques or barrier shifting methods allow us to recover the unbiasedness of the standard Monte-Carlo procedure in a general setting. 

We start with the case of a single asset, then move on to the case where we deal with several underlyings under complex correlation structures. The .ipynb file continuous_pricing outlines the result developped in the pdf file. I will add more numerical examples that deal with not only accuracy but also performance in the near future: Multi level monte carlo techniques can also be applied to improve the running time of those nice algorithms.
