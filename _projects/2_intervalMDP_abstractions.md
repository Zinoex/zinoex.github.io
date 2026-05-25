---
layout: page
title: IntervalMDPAbstractions.jl
description: Abstraction-based verification and synthesis via IMDP targets
img: 
importance: 2
category: software
github: zinoex/IntervalMDPAbstractions.jl
---

**IntervalMDPAbstractions.jl** provides abstraction-based methods for verifying stochastic systems and synthesizing correct-by-construction controllers via IMDP-inspired target models.

## Features

- Abstractions from several stochastic system classes (linear, nonlinear, uncertain PWA, Gaussian process, and switched)
- Target models including IMDPs, odIMDPs, and mixtures of odIMDPs
- Integration with IntervalMDP.jl for verification and synthesis on abstract models
- End-to-end abstraction and policy synthesis workflows

## Workflow

1. Model the stochastic dynamics and property specification
2. Discretize state and input spaces and construct a target abstraction model
3. Build the abstract model and solve verification or synthesis problems
4. Evaluate lower and upper satisfaction probability bounds when needed

[View on GitHub](https://github.com/zinoex/IntervalMDPAbstractions.jl)
