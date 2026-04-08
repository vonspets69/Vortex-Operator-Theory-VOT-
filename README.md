First public release: April 2026

Author: Matti S. Kärki

# Vortex Operator Theory (VOT)

A dynamical resonance framework for modeling the nontrivial zeros of the Riemann zeta function.

---

## Overview

**Vortex Operator Theory (VOT)** is a research program exploring whether the zeros of the Riemann zeta function can be understood as outcomes of a **prime-driven dynamical system**.

Instead of treating zeros as static spectral points, VOT models them as:

> **emergent structures of a constrained resonance field**

The framework integrates:

* arithmetic input (primes)
* dynamical signal ( A_0(t) )
* local spectral geometry
* vortex-based structure (shell / 0-point / flow)
* event system (anchor / bridge / transition)
* hybrid modeling (global + local mechanisms)
* and now: a **rigorous spectral operator core**

---

## Two-Layer Structure

VOT is explicitly divided into two layers:

### 1. Operator Program (long-term goal)

* Prime input:
  [
  K(t) = \sum_{p,k} \log p , \delta(t - k \log p)
  ]

* Dynamic field:
  [
  \frac{dA_0}{dt} = -\alpha A_0 + \beta \sin(\omega t) K(t)
  ]

* Operator:
  [
  H = -i \frac{d}{dt} + \frac12 + A_0(t)
  ]

Goal:

* derive zeta zeros from spectral properties of ( H )
* connect to ( \xi(1/2 + iE) )

⚠️ Not proven.

---

### 2. Empirical Vortex Architecture (current working model)

* Gaussian-windowed local spectrum (STFT)
* purity functional ( \mathcal P(T,\omega) )
* dynamic programming → drifting paths
* multi-layer, multi-arc model
* zero-zone detection (interval-based)

---

## Vortex Ontology

Each local structure is interpreted via:

* **Shell** → local resonance layer
* **0-point** → attractor center
* **Flow** → directional alignment

Event roles:

* `shell_contact` (anchor)
* `shell_approach` (bridge)
* `shell_transition`
* `shell_failure`

---

## Hybrid Model

The current best-performing structure:

```
final model = V1 backbone + local corrections
```

Components:

* **V1** → global scaffold (scales better)
* **precision** → sharp local corrections
* **rescue** → flexible adjustment
* **local_rescue** → targeted fixes

---

## Zero Classification

Each zero is assigned:

* mode: V1 / precision / rescue / local_rescue
* role: shell_contact / shell_approach / etc.
* shell: S1–S5

### Key empirical insight

> Zeros are not homogeneous.

* majority → shell_contact
* minority → shell_approach
* rare → rescue-required

---

## Scaling Results (current)

| zeros | @1.0 | @1.5 |
| ----- | ---- | ---- |
| 20    | 17   | 18   |
| 100   | 62   | 70   |
| 300   | 151  | 178  |
| 1000  | 248  | 308  |

Interpretation:

* purely local models degrade with scale
* hybrid structure improves robustness
* global scaffold (V1) is essential

---

## NEW: Rigorous Spectral Core

We now have a **formal operator-theoretic core**:

### Construction

From purity functional:
[
\mathcal P(T,\omega)
]

define smoothed reduction:
[
F_\beta(T)
==========

\frac{1}{\beta}\log\int e^{\beta \mathcal P(T,\omega)},d\omega
]

then:
[
V_\beta(T) = -F_\beta(T)
]

and operator:
[
H_\beta = -\frac{d^2}{dT^2} + V_\beta(T)
]

---

### Proven result

If ( \mathcal P \in C^2 ) on a compact domain:

* ( V_\beta \in C^2 \subset L^\infty )
* ( H_\beta ) is **self-adjoint**
* spectrum is **discrete**

👉 This is the first rigorous mathematical core of VOT.

---

### Interpretation

* 0-points → maxima of (F_\beta)
* maxima → minima of (V_\beta)
* minima → spectral localization

---

## What is Proven vs Open

### Proven (mathematically)

* construction of self-adjoint operator ( H_\beta )
* discrete spectrum
* well-defined potential from ( \mathcal P )

---

### Empirical (observed)

* vortex structure
* hybrid scaling behavior
* zero classification patterns

---

### Open (core problem)

[
\mathrm{spec}(H_\beta) \stackrel{?}{=} {\gamma_n}
]

This is the exact RH-critical step.

---

## Repository Structure

```
preprint/
  vot_preprint_arxiv_style.html
  vot_formal_core_spectral.html

data/
  zero_classification.json
  scaling_results.json

notes/
  state_summary.txt
```

---

## What This Is

* a structured research program
* a hybrid of empirical + theoretical work
* a candidate framework for RH-related structure

---

## What This Is NOT

* not a proof of RH
* not a finished theory
* not parameter-free

---

## Next Steps

* spectral approximation:
  [
  \lambda_n(H_\beta) \approx \gamma_n
  ]

* shell invariants

* large-scale classification (1000+ zeros)

* operator reconstruction from ( A_0 )

---

## Philosophy

VOT suggests:

* zeros arise from **structured arithmetic dynamics**
* multiple mechanisms coexist
* global + local structure is necessary

---

## Status

⚠️ Research preprint
⚠️ Partial rigor (operator core only)
⚠️ Main theorem still open

---

## License

Recommended:

* CC BY 4.0
  or
* MIT (if code-focused)
