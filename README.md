# A-New-Coefficient-of-Correlation
This notebook has been inspired by a Medium article and a [paper](https://arxiv.org/pdf/1909.10140) by S. Chatterjee from 2020, which both describe a new approach for measuring and quantifying relationships between variables. This new correlation $\xi$ is still far from perfect, but it was created as a means of solving some of the most notable issues with the currently accepted approach. The new coefficient of correlation has the following advantages:
* requires no assumptions on the distributions of the variables,
* it has a simple formula as the classical competitors (Pearson's, Spearman's, Kendall's),
* it is easy to interpretate and measure the degree of dependence between the variables,
* has a simple asymptotic theory under the hypothesis of independence,
* works well with non-monotonic data,
* it seems to be more effective than other tests for detecting oscillatory signals.

<p align='center'>
<img src='https://github.com/msikorski93/New-Coefficient-of-Correlation/assets/45270023/da21e292-cbd6-4af5-b7d8-7d5a14c699d8' width='400'/>
</p>

This example reveals the new correlation $\xi$ does a much better job with identifying the data's trend and how it significantly outperforms the remaining common coefficients.
