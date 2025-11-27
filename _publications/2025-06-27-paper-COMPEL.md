---
title: "Port-Hamiltonian reduced order modelling of the 2D Maxwell equations"
collection: publications
category: manuscripts
permalink: /publications/2025-06-27-paper-COMPEL
date: 2025-06-27
venue: "COMPEL - The international journal for computation and mathematics in electrical and electronic engineering"
paperurl: /files/papers/2025-COMPEL.pdf
bibtexurl: /files/bibtex/2025-COMPEL.bib
citation: "Gouzien Mattéo, Poussot-Vassal Charles, Haine Ghislain, Matignon Denis (2025) <i>Port-Hamiltonian reduced order modelling of the 2D Maxwell equations.</i> COMPEL - The international journal for computation and mathematics in electrical and electronic engineering; X(X):PP–PP"
doi: "10.1108/compel-10-2024-0421"
---

## Purpose  

This study aims to develop a systematic and efficient method for modeling and reducing the computational complexity of the Maxwell equations in 2D. By maintaining the port-Hamiltonian structure in both the full order model (FOM) and reduced-order model (ROM), this approach ensures that the essential dynamical properties are preserved. The ultimate goal is to create a reduced order model that is suitable for rapid simulations, control and analysis in electromagnetic applications, such as waveguides, which involve boundary control and observation, as well as interface discontinuities.

## Design/methodology/approach  

This research introduces an ROM procedure for the 2D Maxwell equations within a port-Hamiltonian framework. Using a mixed finite element method, the high-fidelity FOM is generated, which retains the original structure of the Maxwell equations. Model reduction is then achieved through the Loewner framework, allowing for a low-complexity model that is computationally efficient while preserving the port-Hamiltonian properties. A lifting operator is employed to recover the FOM’s internal variables from the reduced model, validating the accuracy of the ROM in reproducing the FOM’s dynamic behavior.

## Findings  

The proposed methodology effectively reduces the dimension of the Maxwell system by approximately 35 times, significantly decreasing computational time while maintaining high fidelity in the key output responses. Simulation results demonstrate that the reduced model accurately replicates the full order model’s dynamics and power balance. The approach also highlights the advantages of using a port-Hamiltonian structure for energy tracking, with ROMs exhibiting only minor discrepancies due to truncation. The findings validate the ROM as a reliable and efficient approximation of the original high-dimensional system, suitable for complex electromagnetic configurations.

## Originality/value  

This work provides a novel approach to reducing the 2D Maxwell equations within a port-Hamiltonian framework, preserving essential structure and dynamical properties. By leveraging the Loewner framework with a unique focus on passivity preservation, the method offers a practical solution for efficient simulation and control in electromagnetic systems. This ROM methodology, with its reduced computational burden and enhanced accuracy, is valuable for applications in electromagnetic field simulations and control design, where high computational efficiency and structure preservation are critical.
