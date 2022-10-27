# Topics in Statistical Computing
## The Monte Carlo Method
When an i.i.d. random sample $\mathbf{X}_1, \ldots, \mathbf{X}_n$ is obtained from $f$, we can approximate $\mu$ by a sample average:
$$
\hat{\mu}_{\mathrm{MC}}=\frac{1}{n} \sum_{i=1}^n h\left(\mathbf{X}_i\right) \rightarrow \int h(\mathbf{x}) f(\mathbf{x}) d \mathbf{x}=\mu
$$

in R, we can z
