# Deep Hedging with Quantum Computing

This repository summarizes and highlights the key contributions of the paper **"Quantum Deep Hedging"** by Cherrat et al. (2023), which explores the integration of quantum computing and reinforcement learning to solve the deep hedging problem in realistic financial markets.

## Overview

Traditional hedging models like Black-Scholes assume frictionless markets, which limits their applicability in the real world where transaction costs, slippage, and illiquidity exist. Deep Hedging uses reinforcement learning to adaptively learn hedging strategies under these constraints. This paper extends that idea using **Quantum Neural Networks (QNNs)** to potentially improve performance and model expressivity with fewer parameters.

## Key Contributions

- **Quantum Deep Hedging Framework**: Combines deep reinforcement learning with quantum circuits.
- **Trainable Quantum Architectures**: Introduces two QNN designs:
  - **Orthogonal layers**: Efficient, interpretable layers based on Hamming-weight-1 subspaces.
  - **Compound layers**: Richer expressivity via transformations in exterior algebras.
- **Algorithm Integration**: Implements QNNs in both policy-search and actor-critic reinforcement learning paradigms.
- **Real Hardware Deployment**: Models tested on Quantinuum’s H1 quantum processors show consistency with classical simulations.
- **Gradient Trainability Proofs**: Theoretical analysis shows the architectures avoid the barren plateau problem.

## Citation

Cherrat, E. A., Raj, S., Kerenidis, I., et al. (2023). *Quantum Deep Hedging* (arXiv:2303.16585). [arXiv Link](https://doi.org/10.48550/arXiv.2303.16585)

## Author of Summary

Evan Gray
