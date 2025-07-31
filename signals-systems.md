# Signals & Systems - Core Concepts

## Continuous vs Discrete Time
- Continuous: defined at all time t (e.g., analog signals).
- Discrete: defined only at integer samples (e.g., digital signals).

## LTI Systems
- Linearity: T[a·x1(t) + b·x2(t)] = a·T[x1(t)] + b·T[x2(t)]
- Time-invariance: shifting input shifts output equally.

## Convolution
- Integral of input * system impulse response.
- Discrete: y[n] = Σ x[k] · h[n-k]

## Laplace vs Fourier
- Fourier: frequency analysis of periodic/stationary signals.
- Laplace: handles growth/decay—broader use in control systems.
