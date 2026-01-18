# chaos-lyapunov-logistic-map
# Chaos and Lyapunov Exponents in the Logistic Map

This project investigates how deterministic nonlinear systems can exhibit
chaotic behaviour due to exponential sensitivity to initial conditions.

Using the logistic map as a case study, I analysed stability around fixed
points via linearisation and quantified chaos by computing Lyapunov exponents.
The project combines analytical reasoning with numerical simulation.

## Key ideas
- Linearisation of nonlinear dynamics to assess fixed-point stability
- Exponential divergence of nearby trajectories in chaotic regimes
- Lyapunov exponents as a quantitative measure of sensitivity to initial conditions
- Practical numerical issues, including saturation and floating-point precision limits

## Implementation
- Numerical simulation of the logistic map for varying parameter values
- Estimation of Lyapunov exponents via time-averaged logarithmic growth rates
- Comparison of naive trajectory separation with more stable averaging-based methods

## Files
- `chaos_lyapunov_logistic_map.ipynb`: Python/Colab notebook containing simulations and plots
- `Chaos and Lyapunov Exponents Report.pdf`: Written exposition of theory, derivations, and results

This was an independent project motivated by an interest in dynamical systems
and the limits of long-term prediction in deterministic models.
