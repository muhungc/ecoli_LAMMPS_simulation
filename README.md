# ecoli_LAMMPS_simulation
This directory contains the files for the non-equilibrium MD simulations of E.coli cells by Chang et al., 2025. We use LAMMPS software and its REACTOR (bond/react) module to develop our model to simulate the chromosomes and cytosolic crowders (ribosome/polyribosomes) of E.coli cell interior for different conditions. The LAMMPS scripts in each sub-directory read the initial configuration from restart files and perform time integration using the Brownian dynamics integrator in LAMMPS. The template and map files required for REACTOR are placed in "reaction_template" directory. 

one_nuc_react: Single chromosome case with all reactions activated.

one_nuc_noreact: Single chromosome case with all reactions disabled.

one_nuc_rif_treat: Single chromosome case with ribosome-RNAP binding and polysome treadmilling are disabled. All other reactions are activated. 

two_nuc_react: Two chromosome case with all reactions activated.

two_nuc_noreact: Two chromosome case with all reactions disabled.
