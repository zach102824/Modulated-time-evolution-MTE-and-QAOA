# Modulated Time Evolution (MTE) and Quantum Approximate Optimization Algorithm (QAOA)

This repository contains the code and data used for the publication "Modulated Time Evolution for Efficient Variational Ground-State Preparation", https://doi.org/10.48550/arXiv.2408.03251

This repository contains three main parts of Python code in the src folder:

1. How to generate the locally adiabatic magnetic field for the Transverse Field Ising model in the even-even spin and spatial parity subspace.
2. How to run optimization for Modulated Time Evolution (MTE).
3. How to run optimization for the related Quantum Approximate Optimization Algorithm (QAOA).

For the 12-site optimization, the calculation was performed on Google Cloud Platform (GCP) with GPU support, using either the PyTorch or JAX package. The optimization was executed on a single Nvidia V100 (16GB) GPU, with the runtime typically completed within a day.

Note that the jaxlib version must correspond to the existing CUDA installation you wish to use. Please refer to the JAX documentation for more details. To maximize speed, it's recommended to run the code on a cloud service like Google Colab or a similar platform, ensuring the use of the latest CUDA-compatible Python packages.

Citation: [![DOI](https://zenodo.org/badge/851833242.svg)](https://zenodo.org/doi/10.5281/zenodo.13763653)

