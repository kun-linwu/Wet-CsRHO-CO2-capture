# Understanding Water Enhancement of $CO_2$ Adsorption in Zeolite Cs-RHO

[![DOI](https://zenodo.org/badge/845934445.svg)](https://zenodo.org/doi/10.5281/zenodo.13565267)

This project provides the computational and experimental framework used to characterize the extraordinary 3.2-fold enhancement of $CO_2$ adsorption in Cs-RHO zeolite under humid conditions compared to dry states. By integrating molecular simulations with spectroscopic data, we elucidate a cooperative "push-pull" mechanism where water and $CO_2$ work together to translocate $Cs^+$ cations and unblock the zeolite framework. The repository includes scripts for density functional theory (DFT), ab initio molecular dynamics (AIMD), and theory-guided Rietveld refinement to facilitate the study of water-resilient carbon capture materials.

## Technical Skills Used
- Computational Chemistry: Implementation of Density Functional Theory (DFT) and Ab Initio Molecular Dynamics (AIMD) using the VASP package.
- Structural Analysis: Theory-guided Rietveld refinement integrating DFT-derived atomistic structures with experimental PXRD data.
- Data Visualization: Generating 1D and 2D distance histograms to quantify molecular interactions.

## Features
The primary feature of this project is the discovery of a cooperative "push-pull" mechanism that enables Cs-RHO to function more effectively when wet than dry. Unlike conventional zeolites where water competes with $CO_2$, our data demonstrates that water solvates and "pulls" $Cs^+$ cations away from their blocking positions in the double eight-membered ring (D8R), while $CO_2$ simultaneously "pushes" them toward single eight-membered ring (S8R) sites.

## The Process
To provide a molecular-level explanation, we performed extensive AIMD simulations at 303 K across various ensembles to track cation translocation. We projected the distance of $Cs^+$ cations relative to the D8R center into axial and radial components, allowing us to quantify the exact displacement required to unblock the pores. These simulation trajectories were then fed back into the Rietveld refinement process to iterate toward the final structural model.

## What I've Learned
This investigation taught me that competitive adsorption is not an absolute rule in zeolite science; rather, chemical design can turn competition into cooperation. I learned how to identify "water-tolerant" bonding sites by leveraging the higher quadrupolar moment of $CO_2$ compared to the dipolar nature of water. This project also highlighted the critical role of framework flexibility, as the relaxation of the distorted D8R proved essential for opening the apertures for $CO_2$ transport.

On a technical level, I gained experience in resolving the interplay between kinetics and thermodynamics. While the selective bonding site is a thermodynamic feature, the translocation of the $Cs^+$ cation acts as a kinetic "gate" that, when opened by water, increases the adsorption/desorption rate by 3-fold. This project reinforced the value of using a multi-technique approach to solve complex problems in materials science.

## Future Improvements
- Machine Learning Potential Development: Develop neural network potentials to extend simulation timescales beyond the 20 ps accessible via AIMD.
- Broader Cation Screening: Apply the push-pull analysis to other alkali-exchanged forms like Na-RHO to investigate slow transport kinetics.
- Catalytic Application Exploration: Investigate the observed $C-O$ bond weakening in humid conditions for potential $CO_2$ conversion or activation.
- High-Pressure Evaluation: Test the stability of the cooperative mechanism under 4 bar $CO_2$ to simulate more industrial carbon capture environments.

## Videos- cation translocation
https://github.com/user-attachments/assets/91803572-6110-45e9-8a3d-1f69fd16eea7

