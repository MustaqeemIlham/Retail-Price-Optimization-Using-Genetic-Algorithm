# Retail-Price-Optimization-Using-Genetic-Algorithm
4. GA Process

Steps used in the algorithm:
- Load and clean dataset
- Filter by selected product
- Train polynomial demand model
- Initialize population of prices
- Evaluate profit (fitness)
- Apply selection
- Apply crossover
- Apply mutation
- Create next generation
- Return best price and best profit


Demand Forecasting (Polynomial Regression)

A polynomial model predicts demand based on price:
   code: demand = intercept + coef1 * price + coef2 * price^2
This models realistic customer behavior (demand drops if price is too high or too low).

Results:
GA converges quickly (within 5–10 generations)
Hybrid GA + demand model produces realistic and profitable prices
The model adapts well to demand fluctuations and price elasticity
Penalty and bounded price range keep prices practical
