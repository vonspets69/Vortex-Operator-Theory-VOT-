First public release: April 2026
Author: Matti S. Kärki

# Vortex Operator Theory (VOT)

A dynamic spectral framework for the Riemann hypothesis.

## Overview

This repository presents **Vortex Operator Theory (VOT)** as a research program for interpreting the Riemann hypothesis through a dynamic operator model.

The central idea is that the nontrivial zeros of the Riemann zeta function may be viewed not only as a static set of points, but as spectral resonances of a self-adjoint operator driven by arithmetic input.

In schematic form:

```text
primes -> K(t) -> A0(t) -> H -> spectrum ≈ {γ_n}
```

where:

- `K(t)` is a prime-source distribution based on the von Mangoldt structure,
- `A0(t)` is a dynamic zero-point field,
- `H` is the proposed operator,
- `{γ_n}` denotes the ordinates of the nontrivial zeros.

## Core operator model

The framework works in the Hilbert space

```math
\mathcal H = L^2(\mathbb{R}/L\mathbb{Z})
```

with the operator

```math
H = -i\frac{d}{dt} + \frac12 + A_0(t).
```

The prime input is encoded as

```math
K(t)=\sum_{p,k}\log p\,\delta(t-k\log p).
```

The dynamic field is defined by

```math
\frac{dA_0}{dt}=-\alpha A_0+\beta\sin(\omega t)K(t).
```

with causal solution

```math
A_0(t)=\beta\sum_{p,k:\,k\log p\le t}\log p\,e^{-\alpha(t-k\log p)}\sin(\omega k\log p).
```

## Main approximation

The average location of the zeros is approximated by

```math
\gamma_n^{(0)}=\frac{2\pi (n-11/8)}{W\!\left((n-11/8)/e\right)}.
```

This is a Lambert-`W` inversion of the main term of the Riemann–von Mangoldt formula.

## Central conjecture

The key conjectural relation is

```math
A_0(T)\sim S(T),
```

where `S(T)` is the oscillatory part of the argument of the zeta function.

If this identification can be justified rigorously, the zero ordinates may be interpreted as the combination of a main asymptotic term and a dynamic correction term.

## Current status

This repository does **not** claim a proof of the Riemann hypothesis.

At present, VOT should be read as a **research program** with the following open tasks:

1. Construct the operator `H` on firm analytic grounds.
2. Prove that the dynamic field `A0(t)` corresponds to the oscillatory term `S(T)`.
3. Derive the required trace identity from the operator model.
4. Clarify whether the resulting spectral picture can be made fully rigorous.


## Author

**Matti S. Kärki**

If you cite or discuss this work, please attribute the repository and author clearly.

## License
This work is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0).


## Disclaimer

This repository is intended for mathematical discussion, critique, and development. It presents a speculative operator framework motivated by spectral interpretations of the zeta zeros and should not be represented as a proven result.


