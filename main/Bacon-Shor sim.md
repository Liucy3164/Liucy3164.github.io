---
layout: default
title: Bacon-Shor codes simulation
permalink: /projects/Bacon-Shorsim/
---

# 💻 Simulations on Error Analysis of Planar Ion Crystals and Ion Chains Implementing the Bacon–Shor Code (on going)

[1]: https://doi.org/10.1126/sciadv.adp2008
[2]: https://iopscience.iop.org/article/10.1088/1367-2630/ab84b6

Building on both experimental research and theoretical foundations for implementing and comparing Bacon–Shor codes with trapped ions [[1]], we focus on studying heating errors and possible improvements when implementing quantum circuits on 2D ion crystals or other ion structures. Since stronger in-plane confinement is required due to ion configurations, however, the results show that additional heating errors arise because the lowest vibrational modes are no longer the center-of-mass modes.

In the poster below, we provide an analysis of a possible background setup for a 2D planar ion crystal, including normal-mode frequencies and mode participations for different ions.

We also highlight the potential of optical tweezers for controlling collective motional modes [[2]]. In addition, we propose a possible improvement in theoretical gate fidelity by introducing tweezers on ions that are not directly involved in gate operations. Looking ahead, we are interested in implementing more localized confinement when the system allows for additional ancilla qubits or overhead resources.

Furthermore, we have implemented the Bacon–Shor codes in Python using the Qiskit package, and we aim to build upon the work in [[1]] to simulate errors with modified gate and ion structures. The details of these ongoing efforts are presented in the poster.

Finally, I am also interested in exploring the fundamental mathematical framework for designing or improving current error-correcting circuits in the future, which could be directly applied across various quantum computing platforms.

<embed src="{{ 'graphs/QEC poster.pdf' | relative_url }}" 
       type="application/pdf" 
       width="200%" 
       height="1200px" 
       style="border-radius:24px;" />



