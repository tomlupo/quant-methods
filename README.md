# Quantitative Methods

A collection of quantitative finance methods and algorithms implemented in Python.

## Methods

### Monte Carlo Simulations
`monte_carlo_simulations/`

Geometric Brownian Motion (GBM) simulations comparing price paths with and without parameter uncertainty. Demonstrates how estimation error in drift parameter affects confidence intervals.

### Trade Calculation with Stochastic Rounding
`trade_calculation_stochastic_rounding/`

Portfolio rebalancing with stochastic lot rounding. Rounds trade sizes to valid lot sizes while preserving expected values through probabilistic rounding.

### Regression Methods for Index Tracking
`regression_methods/`

Portfolio weight optimization using different regression approaches:
- OLS (Ordinary Least Squares)
- Ridge (L2 regularization)
- Lasso (L1 regularization)
- Elastic Net (L1 + L2)

### Index Tracking
`index_tracking/`

Jupyter notebooks demonstrating index replication and sparse portfolio optimization.

## Installation

```bash
pip install -e .
```

## Requirements

- Python 3.9+
- numpy, pandas, scipy, matplotlib

## License

MIT
