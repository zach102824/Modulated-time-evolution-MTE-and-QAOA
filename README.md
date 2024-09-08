# Modulated time evolution (MTE) and Quantum approximate optimization algorithm (QAOA)
This repository contains the code and data used for publication " Modulated time evolution for efficient variational ground-state preparation" ,
https://doi.org/10.48550/arXiv.2408.03251

This repository contains three main parts of python code in the src folder
1. How to generate the locally adiabatic magnetifc field for the Transvserse field Ising model in the even-even spin and spatial parity subspace.
2. How to run optimzation for modulated time evolution(MTE).
3. How to run optimzation for the related Quantum approximate optimization algorithm (QAOA).

For the 12-site optimization, the calculation was performed on Google Cloud Platform (GCP) with GPU support, using either the PyTorch or JAX package.The optimization was executed on a single Nvidia V100 (16GB) GPU, with the runtime typically completed within a day.

To achieve optimal speed, it is recommended to run the code on a cloud service such as Google Colab or a similar platform.
