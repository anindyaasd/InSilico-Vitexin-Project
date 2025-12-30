# In Silico Analysis: Vitexin vs DNA Gyrase A (GROMACS MD Simulation)

This repository contains the configuration files, command logs, and analysis results from my undergraduate thesis project. The study integrates Molecular Docking and Molecular Dynamics (MD) simulations to evaluate Vitexin as a potential antibacterial candidate targeting *Salmonella typhi*.
## 🛠 Project Overview
- **Objective:** To determine the binding affinity and stability of the Vitexin-DNA Gyrase A complex.
- **Tools Used:** GROMACS (Linux/Ubuntu), AutoDock Vina, PyRx, Python (for topology conversion), xmgrace.
- **System:** Protein-Ligand Complex in water solvent.
## 💻 Workflow Highlights (Linux Environment)
I performed the entire simulation workflow in a **Linux Command-Line Interface**, including:
1.  **Topology Preparation:** Used `pdb2gmx` for protein and Python scripts (`cgenff_charmm2gmx`) for ligand topology generation (CHARMM Force Field).
2.  **System Construction:** Solvation, Ionization, and Energy Minimization.
3.  **Equilibration:** NVT and NPT ensembles (100 ps).
4.  **Production Run:** MD Simulation run.
5.  **Analysis:** RMSD, RMSF, and Hydrogen Bond analysis using GROMACS tools and `xmgrace`.
## 📂 File Description
- `*.mdp`: Molecular Dynamics Parameter files used for minimization and equilibration.
- `commands_log.txt`: The sequence of GROMACS commands executed in the Linux terminal.
- `Analysis_Plots/`: Visualization of RMSD and RMSF stability (images).
## 📊 Key Results
The simulation results indicate that the Vitexin-Protein complex maintains stability with an average RMSD of [Masukkan Angka jika ingat] nm, suggesting a strong binding interaction.

---
*Created by Anindya Salsabila Dwinanda*
