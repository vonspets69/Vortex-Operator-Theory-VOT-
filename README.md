First public release: April 2026

Author: Matti S. Kärki

# Vortex Operator Theory (VOT)

A dynamical resonance framework for modeling the nontrivial zeros of the Riemann zeta function.

---

## Overview

**Vortex Operator Theory (VOT)** is a research prototype that explores a non-classical approach to the zeros of the Riemann zeta function.

Instead of treating zeros as static spectral points, VOT models them as **outputs of a dynamical resonance system** driven by prime-based arithmetic input.

The framework combines:

* a **prime-driven signal** ( A_0(t) )
* **local spectral analysis** (time–frequency structure)
* a **vortex ontology**:

  * shell
  * 0-point
  * flow
* an **event system**:

  * anchor (visible contact)
  * bridge (weak attempt)
  * transition
* a **hybrid architecture**:

  * V1 (global scaffold)
  * precision (local sharp correction)
  * rescue (flexible correction)
  * local_rescue (targeted patch)

---

## Key Idea

> Zeta zeros are not modeled as static points,
> but as outcomes of evolving resonance structures.

---

## Unified Structure

The current version combines two layers:

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

* connect the spectrum of ( H ) to zeta zeros
* eventually relate to ( \xi(1/2 + iE) )

⚠️ Not yet proven.

---

### 2. Empirical Vortex Architecture (current working model)

* STFT-based local spectrum
* purity surface (low leakage prioritized)
* drifting key paths (dynamic programming)
* multi-layer / multi-arc structure
* zero-zone (interval-based detection)

---

## Vortex Interpretation

Each event is interpreted through:

* **Shell** → local resonance structure
* **0-point** → attractor center
* **Flow** → direction of alignment

Event roles:

* `shell_contact`
* `shell_approach`
* `shell_transition`
* `shell_failure`

---

## Zero Classification

Each zero is assigned:

* mode:

  * V1
  * precision
  * rescue
  * local_rescue
* role:

  * shell_contact
  * shell_approach
  * etc.
* shell: S1–S5

### Empirical result (first 20 zeros)

* ~85% → shell_contact
* ~15% → shell_approach
* rare → local_rescue

👉 Zeros are **not homogeneous**

---

## Scaling Results

| zeros | @1.0 | @1.5 |
| ----- | ---- | ---- |
| 20    | 17   | 18   |
| 100   | 62   | 70   |
| 300   | 151  | 178  |
| 1000  | 248  | 308  |

Interpretation:

* purely local models fail to scale
* **V1-backed hybrid improves large-scale behavior**

---

## What This Is

* a **research framework**
* a **mechanism discovery model**
* a **structured experimental system**

---

## What This Is NOT

* not a proof of the Riemann Hypothesis
* not a complete spectral theory
* not a final model

---

## Repository Structure

* `preprint/`

  * unified HTML manuscript (operator + vortex)

* `data/`

  * zero classification
  * scaling results
  * hybrid outputs

* `notes/`

  * state summaries and development notes

---

## Current Status

* strong empirical structure at low–mid zeros
* hybrid model shows better scaling than earlier versions
* vortex ontology aligns with observed event structure

Main limitation:

* no rigorous operator–spectrum proof yet

---

## Next Steps

* blockwise classification (1000+ zeros)
* shell scaling laws
* formal vortex constraints
* operator reconstruction from observed structure

---

## Philosophy

VOT suggests that:

* zeros emerge from **structured arithmetic dynamics**
* multiple mechanisms coexist
* global and local structures must be combined

---

## Contributing / Discussion

This repository is open for:

* critique
* mathematical analysis
* alternative interpretations
* collaboration

---

## Status

⚠️ Research preprint
⚠️ Experimental + theoretical hybrid
⚠️ Not a proof of RH

---

## License

(choose one and keep it consistent)

* CC BY 4.0 (recommended for attribution)
  or
* CC0 (public domain)
