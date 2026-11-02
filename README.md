# TBG-from-first-principles

This repository contains atomic and electronic structure data of twisted bilayer graphene (TBG) calculated using the [Siesta](https://iopscience.iop.org/article/10.1088/0953-8984/14/11/302) density functional theory (DFT) package. For commensurate twist angles between $0.78^\circ$ and $21.87^\circ$, the fully relaxed atomic structures and electronic bands of TBG can be found in `relaxed-atomic-structures/` and `DFT-band-structures/`, respectively. Each angle is identified by an integer $N \geq 2$ that denotes how the moir\'e cell lattice vectors are constructed from the primitive graphene lattice vectors ${\bf a}_1$ and ${\bf a}_2$. For example, one moir\'e lattice vector ${\bf \lambda}_1$ is constructed as ${\bf \lambda} = N{\bf a}_1 + (N-1){\bf a}_2$ (for further details, [see Electronic-structure methods for twisted moir\'e layers](https://www.nature.com/articles/s41578-020-0214-0)). The list of angles and integers $N$ can be found in `angles.txt`.

For angles between $0.93^\circ$ and $1.05^\circ$, we provide tight-binding Hamiltonians obtained by Wannierizing the the 20 DFT bands closest to charge neutrality using the [Wannier90](https://www.sciencedirect.com/science/article/abs/pii/S0010465507004936?via%3Dihub). They are located in `tight-binding-hamiltonians/`.

The data in this repository accompanies the following references. Please cite the appropriate references when publishing work that uses the data in the repository:
- Relaxed atomic structures and electronic bands: A. Zhu, D. Bennett, D. T. Larson, M. M. A. Ezzi, E. Manousakis, and E. Kaxiras, Twisted bilayer graphene from first principles: Structural and electronic properties, [Phys. Rev.
B 113, 205125 (2026)](https://journals.aps.org/prb/abstract/10.1103/8gvw-4rgk).
- Electronic bands and wavefunctions: A. Zhu, D. Bennett, D. T. Larson, M. M. A. Ezzi, E. Manousakis, and E. Kaxiras, Wavefunction textures in twisted bilayer graphene from first principles, [Phys. Rev. B 113, L041112 (2026)](https://journals.aps.org/prb/abstract/10.1103/2m63-b51d).
- Tight-binding Hamiltonians: A. Zhu, D. Bennett, D. T. Larson, M. M. A. Ezzi, E. Manousakis, and E. Kaxiras, On the nature of low-energy electronic states in twisted bilayer graphene: a first principles study.

We include a Python Jupyter notebook in each repository that shows examples of how to read and analyze the data.

## Relaxed atomic structures
