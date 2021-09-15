[![Paper](https://img.shields.io/badge/paper-arXiv%3AXXXX.YYYYY-B31B1B.svg)](https://arxiv.org/abs/XXXX.YYYYY)
[![DOI](https://zenodo.org/badge/323956305.svg)](https://zenodo.org/badge/latestdoi/323956305)


# Balls and Walls: A Compact Unary Coding for Bosonic States

Hatem Barghathi, Caleb Usadi, Micah Beck, and Adrian Del Maestro

[arXiv:XXXX.YYYYY](https://arxiv.org/abs/XXXX.YYYYY)

### Abstract
We introduce a unary coding of bosonic occupation states based on the famous ``balls and walls'' counting for the number of configurations of $N$ indistinguishable particles on $L$ distinguishable sites.  Each Fock state is represented by an integer with a human readable bit string that has a compositional structure allowing for the efficient application of operators that locally modify the number of bosons. By exploiting translational and inversion symmetries, we identify a speedup factor of order $L$ over current methods when generating the basis states of bosonic lattice models.  The unary coding is applied to a one-dimensional Bose-Hubbard Hamiltonian with up to $L=N=20$, and the time needed to generate the ground state block is reduced to a fraction of the diagonalization time. For the ground state symmetry resolved entanglement, we demonstrate that variational approaches restricting the local bosonic Hilbert space could result in an error that scales with system size.

### Description
This repository includes links, code, scripts, and data to generate the figures for the associated paper on compact unary coding for bosonic states.

### Requirements
The data in this project was generated via exact diagonalization.  Everything included in the [data](https://github.com/DelMaestroGroup/papers-code-UnaryBosonicBasis/tree/main/data) directory was generated via:

* [ED for the Bose-Hubbard model and entanglement entropy measures](https://github.com/DelMaestroGroup/Bose-Hubbard_diagonalize)

### Support
The creation of these materials was supported in part by the National Science Foundation under Award No. DMR-1553991.

[<img width="100px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](http://www.nsf.gov/awardsearch/showAward?AWD_ID=1553991)

### Figures

#### Figure 01: Time Scaling
<img src="https://github.com/DelMaestroGroup/papers-code-UnaryBosonicBasis/blob/main/figures/TimeScaling.svg" width="400px">

#### Figure 02: Entanglement Measures
<img src="https://github.com/DelMaestroGroup/papers-code-UnaryBosonicBasis/blob/main/figures/EntanglementMeasures.svg"  width="400px">

#### Figure 03: Restricted Occupation Numbers
<img src="https://github.com/DelMaestroGroup/papers-code-UnaryBosonicBasis/blob/main/figures/RestrictedOccupationNumber.svg" width="400px">

<!--This figure is relesed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.-->

