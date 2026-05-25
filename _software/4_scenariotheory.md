---
layout: page
title: ScenarioTheory.jl
description: Violation probability bounds from scenario theory
img: 
importance: 4
category: software
github: https://github.com/zinoex/ScenarioTheory.jl
---

**ScenarioTheory.jl** is a Julia library for computing bounds from Scenario Theory (Campi & Garatti). Given the number of samples, the desired confidence, and the number of decision variables/support constraints/compressed size, it computes the violation probability — i.e. the probability of a change of compression.

Note: the package does *not* solve scenario optimization or compression problems itself; it provides the theoretical bounds needed to interpret their solutions.

## Supported Theory Types

- **Scenario Optimization** — classical bounds based on sample count and decision variables
- **Wait-and-Judge Scenario Optimization** — bounds based on the number of support constraints
- **One-Tail Change of Compression** — generalized compression-based bounds
- **Two-Tail Change of Compression** — two-sided bounds on violation probability

## Motivation

Computing these bounds is numerically unstable (large binomial coefficients, large exponents of values in `[0, 1]`). This package handles the numerics robustly so you don't have to.

[View on GitHub](https://github.com/zinoex/ScenarioTheory.jl)
