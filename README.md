# Full-Alexandrov-Lab-Internship
This repo contains all of the code that I wrote during my time working under Dr. Alexandrov at the University of Nebraska-Lincoln. The code tests doped versions of an NiCo2O4 lattice by intaking three dopants and outputting a data table communicating the new lattice's efficiency at water-splitting.

Doped_material_creation_script and POSCAR_creation_script produce the four necessary input files to run the Vienna Ab-Initio Simulations Package, which is the means by which the actual material simulations and catalytic efficiency were tested.

Run_script enters the files and plugs each input into VASP, which runs on the University supercomputer.

Datatable_creation_script enters the files ran by VASP, extracts the necessary data, and performed calculations in order to format it into a readable table for analysis.
