# Quantum amplitude encoding of polynomial functions using MPS

This repository explores the application of Matrix Product States (MPS) for amplitude encoding of various polynomial functions. The study includes an analysis of fidelity variations across different bond dimensions for different polynomial families. Additionally, it focuses on the fundamental case of the linear function, which plays a crucial role in our paper.

### Approach

While one could compute the MPS of a polynomial directly for a specified bond dimension and subsequently transform it into a quantum state using established methods (see https://arxiv.org/abs/1908.07958), this approach can become computationally expensive based on the chosen bond dimension.

To address this, we propose an efficient method for preparing the linear function \(f(x) = x\). Then, by utilizing Quantum Singular Value Transformation (QSVT), we can perform polynomial transformations on the amplitudes, allowing us to obtain the desired polynomial quantum state. 
