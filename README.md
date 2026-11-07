# Markowitz Mean–Variance Optimisation

Implementation of Markowitz (1952) mean–variance portfolio selection. It covers:

- estimation of the expected-return vector $\mu$ and covariance matrix $\Sigma$ from historical returns;
- the **efficient frontier**, obtained by solving $\min_w w^\top \Sigma w$ subject to $w^\top \mu = \mu_p$ and $w^\top \mathbf 1 = 1$;
- the optimal portfolio for each target return, with its volatility.

Short positions are allowed: the weights are not constrained to $w_i \ge 0$.

## Contents

| File | Description |
|---|---|
| `2. Markowitz et tel data.ipynb` | Estimation, efficient frontier and plots |
| `DEMO delta markowitz.pdf` | Write-up of the derivation and results |

## Assumptions

Single-period horizon; investors are rational, risk-averse and only care about mean and variance; all investors share the same information.
