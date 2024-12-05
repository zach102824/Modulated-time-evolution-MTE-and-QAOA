# Modulated Time Evolution (MTE) and Quantum Approximate Optimization Algorithm (QAOA)

This repository contains the code and data used for the publication:  
**"Modulated Time Evolution for Efficient Variational Ground-State Preparation"**  
Available at: [https://doi.org/10.48550/arXiv.2408.03251](https://doi.org/10.48550/arXiv.2408.03251)

## Contents
The repository includes three main components in the `src` folder:

1. Generation of the locally adiabatic magnetic field for the Transverse Field Ising model in the even-even spin and spatial parity subspace.
2. Optimization routines for Modulated Time Evolution (MTE).
3. Optimization routines for the related Quantum Approximate Optimization Algorithm (QAOA).

## Computational Setup
- **12-site Optimization**: The calculations were performed on the Google Cloud Platform (GCP) with GPU support. Either the PyTorch or JAX package was used for optimization.  
- **Hardware**: A single Nvidia V100 (16GB) GPU was used, with runtimes typically completing within a day.

## Requirements
- **JAX**: Ensure that the `jaxlib` version corresponds to the existing CUDA installation. Refer to the JAX documentation for details.
- **Optimization Recommendation**: For maximum speed, run the code on a cloud service such as Google Colab or a similar platform, ensuring the use of the latest CUDA-compatible Python packages.

## Citation
[![DOI](https://zenodo.org/badge/851833242.svg)](https://zenodo.org/doi/10.5281/zenodo.13763653)
