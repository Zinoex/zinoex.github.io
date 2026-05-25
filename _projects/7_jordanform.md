---
layout: page
title: JordanForm.jl
description: Educational Jordan form computations for exact arithmetic
img: 
importance: 7
category: software
github: zinoex/JordanForm.jl
collaborators: Adrien Banse
---

**JordanForm.jl**, developed in collaboration with **Adrien Banse**, is a Julia package for computing Jordan normal forms and their similarity transformations.

The package is intended for educational use. Since Jordan decomposition is highly sensitive to perturbations, it is designed for integer and rational matrices rather than floating-point numerical workflows.

## Features

- Computes Jordan form factorizations `A * S = S * J`
- Returns both transformation matrix and Jordan structure
- Focused on exact-arithmetic educational examples
- Useful for teaching linear algebra and linear systems theory

## Notes

- Jordan form is not numerically stable in floating-point arithmetic
- Best suited for symbolic or exact matrix inputs

[View on GitHub](https://github.com/zinoex/JordanForm.jl)
