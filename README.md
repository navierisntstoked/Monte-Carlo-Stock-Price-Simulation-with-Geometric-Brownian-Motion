# Monte Carlo Stock-Price Simulation Using GBM

One-paragraph project summary.

![Percentile bands](figures/gbm_percentile_bands.png)

## Key Findings

- 10,000 simulated one-year price paths
- 0.09% error between simulated and analytical expected terminal price
- Exact agreement to two decimals for the theoretical and simulated median
- Terminal standard deviation increased from $10.83 to $33.02 as volatility
  increased from 10% to 30%
- Increasing volatility widened and skewed the distribution without changing
  the theoretical expected terminal price

## Model

GBM equation and parameter definitions.

## Methods

Explain vectorized path generation, percentile calculation, common random
numbers, and analytical validation.

## Results

![Terminal distribution](figures/terminal_price_distribution.png)

![Volatility sensitivity](figures/volatility_sensitivity.png)

Summarize the numerical findings.

## Assumptions and Limitations

Discuss constant parameters, normal log returns, continuous paths, and why the
results are conditional scenarios rather than market forecasts.

## Running the Notebook

1. Clone the repository
2. Install `numpy` and `matplotlib`
3. Open and run the notebook from top to bottom
