---
layout: default
title: Bosonic logical qubits
permalink: /projects/Bosonicsim/
---

# 💻 Simulations of gate sets for logical qubits encoded in bosonic qubits.

[1]: https://www.nature.com/articles/s41467-017-00045-1

Following [[1]], one can examine my Julia code implementing the L-BFGS and Nelder–Mead optimization methods for the logical X gate (or encoding gate) in a bosonic system. By representing the pulse shape as a Fourier series, I first determined the Fourier coefficients in a discrete manner, including high-frequency components up to fourty times the fundamental frequency. This allows the Fourier pulses to exhibit rapid and significant changes in amplitude. Subsequently, I compared the fidelities obtained from the discretized pulse shapes and from the continuous Fourier-series pulse constructed using the same optimized coefficients. The results show only negligible discrepancies.

By modifying the definition of fidelity, the Hilbert-space dimension, and the maximum number of iterations (maxiter), one can simulate other gate sets or encoding processes.

👉 [Simulations of gate sets for logical qubits encoded in bosonic qubits (RK4)](https://github.com/Liucy3164/Simulations-of-gate-sets-for-logical-qubits-encoded-in-bosonic-qubits)

👉 [Simulations of gate sets for logical qubits encoded in bosonic qubits (piecewise propagation)](https://github.com/Liucy3164/Simulations-of-gate-sets-for-logical-qubits-encoded-in-bosonic-qubits)

Fundamentally, the RK4 method offers fourth-order accuracy but requires dense timesteps, especially for strongly anharmonic Hamiltonians. In contrast, piecewise propagators using the midpoint Hamiltonian are second-order accurate, remain exactly unitary, and are computationally more efficient.

This repository contains my Julia notebooks (`.ipynb`) for simulating gate sets of logical qubits encoded in bosonic modes.  
You can open the notebooks directly in Jupyter using the Julia kernel.
