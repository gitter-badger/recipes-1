# Financial Recipes

Models and Pricing
------------------

- Heston stochastic volatility model
- Black-Scholes
- Vasicek
- Hull-White for interest rates [1-factor, 2-factor]
- Garman-Kohlhagen for FX
- CEV (constant elasticity of variance) model
- Bachelier model
- SABR model
- A DSL for models (and basis for stochastic sampling)

Computational ingredients/components
------------------------------------

- Brownian bridge 
- Quasirandom number generation
  * Sobol numbers
  * van der Corput numbers
- Pseudorandom number generation
- Monte-Carlo simulation
- Longstaff-Schwartz (for American options);

Finite differencing for PDE solving 
-----------------------------------

- binomial trees, lattices

Risk
----

- Value at Risk
- “Greeks” — sensitivities to designated parameters (risk factors)
  * Automatic differentiation
  
Date/time 
---------

- Day count conventions 
- Data conversion


Notes on Parallelism
--------------------

- Vectorisation


