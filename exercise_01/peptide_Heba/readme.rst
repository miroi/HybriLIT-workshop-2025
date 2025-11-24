===========
Exercise 01
===========

MOPAC
~~~~~
This exercise is utilizing the MOPAC (Molecular Orbital PACkage) semiempirical quantum chemistry program.
See http://openmopac.net/.  

1IYT
~~~~
1IYT is the Alzheimer's disease amyloid beta-peptide, see https://www.rcsb.org/structure/1IYT

This is simple, steps-restricted geometry optimization of the 1IYT peptide.
MOPAC runs few geometry steps from its pre-optimized structure. 

In this exercise, user can increase number of geometry cycles, or change the Hamiltonian.

solvent effect
~~~~~~~~~~~~~~
Program employs the Conductor-like Screening Model (COSMO) to approximate the effect of a solvent model surrounding the small peptide molecule.

visualisation
~~~~~~~~~~~~~
You can display the resulting aux-file using fresh Avogadro2 build.
(See also https://discuss.avogadro.cc/t/avogadro2-can-not-properly-read-mopac-aux-file/7232.)

