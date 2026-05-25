---
layout: page
title: StochasticBarrier.jl
description: Toolbox for stochastic barrier functions in noisy systems
img: 
importance: 5
category: software
github: https://github.com/aria-systems-group/StochasticBarrier.jl
collaborators: Rayan Mazouz
---

**StochasticBarrier.jl**, developed in collaboration with **Rayan Mazouz**, is a Julia toolbox for generating stochastic barrier functions for discrete-time stochastic systems with additive Gaussian noise.

## Features

- Supports linear, polynomial, and piecewise-affine uncertain dynamics
- Includes Sum-of-Squares (SOS) and piecewise-constant (PWC) approaches
- PWC engines based on dual LP, CEGS LP, and projected gradient descent
- Benchmark scripts used to reproduce experiments from the toolbox paper

## Applications

- Safety verification of stochastic systems via barrier certificates
- Reproducible benchmarking workflows for SOS and PWC methods
- Experiment pipelines with Docker-based setup

[View on GitHub](https://github.com/aria-systems-group/StochasticBarrier.jl)
