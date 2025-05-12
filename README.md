# Nanodisc simulation project
This LAMMPS script simulates the orderphobic behavior of a membrane protein inserted into the lipid bilayer of a nanodisc.
Lipid and Protein particles are course grained to single particles for simplicity.

Periodic_Bilayer.lam uses periodic boundaries to simulate the orderphobic effect of a membrane protein in an infinite lipid bilayer.
Nanodisc_Bilayer.lam introduces fixed x and y boundaries with weak repulsion to represent the orderphobic effect of a membrane scaffold protein within a nanodisc.
The size of the simulated nanodisc can be adjusted by changing the dimensions of the simulation box.  The number of lipids should also be adjusted to compensate for this change in size.

This simulation provides insight into how the size of a nanodisc may affect the behavior of the membrane proteins inserted within them.

Orderphobic effect behavior was modeled according to Katira, s, et al. https://doi.org/10.7554/eLife.13150
Script was adapted from the Brownian Dynamics LAMMPS input script provided by Dr. Kinjal Dasbiswas in PHYS_230
