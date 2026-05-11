# Universal Approximation Experiments

This repository contains experimental code for studying universal approximation in real-valued, complex-valued, and quaternion neural networks.

The project is part of an ongoing research discussion on how different neural network settings approximate functions over real, complex, and hypercomplex domains.

## Motivation

Universal approximation theorems show that neural networks can approximate broad classes of functions under suitable assumptions.  
This repository explores these ideas computationally, with a focus on:

- real-valued neural networks,
- complex-valued neural networks,
- quaternion-valued neural networks,
- comparison between theoretical assumptions and numerical behavior,
- simple experiments that support presentation and paper development.

## Research Context

The experiments are connected to two main outputs:

1. a presentation on universal approximation,
2. a research paper on quaternion universal approximation, including real and complex cases as supporting foundations.

## Repository Structure

```text
.
├── experiments/
│   ├── real_networks/
│   ├── complex_networks/
│   └── quaternion_networks/
│
├── notebooks/
│   ├── real_case_examples.ipynb
│   ├── complex_case_examples.ipynb
│   └── comparison_experiments.ipynb
│
├── src/
│   ├── models/
│   ├── activations/
│   ├── training/
│   └── utils/
│
├── results/
│   ├── figures/
│   └── logs/
│
├── references/
│
└── README.md
