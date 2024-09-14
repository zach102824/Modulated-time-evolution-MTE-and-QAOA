\section*{Modulated Time Evolution (MTE) and Quantum Approximate Optimization Algorithm (QAOA)}

This repository contains the code and data used for the publication "\href{https://doi.org/10.48550/arXiv.2408.03251}{Modulated Time Evolution for Efficient Variational Ground-State Preparation}."

The repository includes three main Python code sections in the \texttt{src} folder:

\begin{enumerate}
    \item \textbf{Generating Locally Adiabatic Magnetic Fields}: Code for creating locally adiabatic magnetic fields for the Transverse Field Ising Model in the even-even spin and spatial parity subspace.
    
    \item \textbf{Optimization for Modulated Time Evolution (MTE)}: Scripts to run optimization processes using the MTE method.
    
    \item \textbf{Optimization for the Quantum Approximate Optimization Algorithm (QAOA)}: Scripts to run optimization processes using the QAOA method.
\end{enumerate}

For the 12-site optimization, calculations were performed on Google Cloud Platform (GCP) with GPU support, utilizing either the PyTorch or JAX packages. The optimization was executed on a single Nvidia V100 (16\,GB) GPU, typically completing within a day.

To maximize speed, it is recommended to run the code on a cloud service like Google Colab or a similar platform, ensuring the use of the latest CUDA-compatible Python packages.

\textbf{Citation}:

\begin{center}
    \href{https://zenodo.org/doi/10.5281/zenodo.13763653}{\includegraphics[scale=1]{doi_badge.svg}}
\end{center}
