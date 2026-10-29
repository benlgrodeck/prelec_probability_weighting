# Prelec Probability Weighting

An interactive classroom visualization of the one-parameter Prelec probability weighting function:

w(p) = exp(−(−ln p)^α)

## Use

Download `index.html` and open it in any modern web browser. No installation, build step, or internet connection is required for the visualization.

- Adjust α from 0.10 to 1.00 to see how the inverse-S curve changes.
- Compare the weighting curve with the linear benchmark w(p) = p.
- Observe the fixed point p = w(p) = 1/e.
- Read selected probabilities and their corresponding decision weights in the table.

The initial setting is α = 0.60. At α = 1 the model is linear. The endpoints are defined as w(0) = 0 and w(1) = 1. Decision weights describe the influence of probabilities on choice, not a change in the actual chance of an outcome.

## Reference

Prelec, D. (1998). The Probability Weighting Function. Econometrica, 66(3), 497–527.
