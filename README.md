# Efficient quantum amplitude encoding of polynomial functions

# Quantum Polynomial Amplitude Encoding with MPS

This repository explores the application of Matrix Product States (MPS) for amplitude encoding of various polynomial functions. The study includes an analysis of fidelity variations across different bond dimensions for different polynomial families. Additionally, it focuses on the fundamental case of the linear function, which plays a crucial role in the research.

## Approach

While one could compute the MPS of a polynomial directly for a specified bond dimension and subsequently transform it into a quantum state using established methods, this approach can become computationally expensive based on the chosen bond dimension.

To address this, we propose an efficient method for preparing the linear function \(f(x) = x\) by utilizing Quantum Singular Value Transformation (QSVT). Following this, we employ QSVT for polynomial transformations, allowing us to obtain the desired polynomial quantum state with improved efficiency. 

## Notebook Contents

- The exact preparation of the linear function using an MPS with a bond dimension of 2.
- Fidelity analysis when using an MPS with a bond dimension of 1 (product state).

Explore the provided notebooks for a detailed understanding of the methodology and results.


