# Signals & Systems – Foundations

## What is a signal?
A signal is a function that conveys information—typically represented as voltage or current over time. 
- Analog signals: continuous in time and amplitude (e.g., sine wave).
- Digital signals: discrete in time, often binary (e.g., sampled data).

## Continuous vs Discrete Signals
- **Continuous**: defined at every time t ∈ ℝ
- **Discrete**: defined only at specific t = nT (n ∈ ℤ, T = sampling period)

## Time-Invariant Systems
A system is time-invariant if its behavior doesn't change over time.  
If input x(t) → output y(t), then:  
→ x(t - t₀) should produce y(t - t₀)

## Linearity
A system is linear if:

T[a·x₁(t) + b·x₂(t)] = a·T[x₁(t)] + b·T[x₂(t)]


## LTI Systems
Linear Time-Invariant systems have predictable and powerful behavior:
- Can be described by differential equations
- Response to any input can be determined using **convolution**

## Convolution (Continuous)

y(t) = ∫ x(τ)·h(t - τ) dτ

- h(t): system’s impulse response  
- Convolution describes how the system modifies the input signal

## Why this matters
Understanding signals and systems is essential for:
- Communications (filters, encoders, bandwidth)
- Control systems (feedback, stability)
- Power systems (waveform analysis, signal harmonics)

---
🧠 *My goal:* Master LTI concepts deeply and connect theory to real-world systems (like audio processing or solar signal noise).

